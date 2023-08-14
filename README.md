### Hi there 👋
1.피보나치
-
public static int fibonacci(int n) {
    if (n < 0) throw new IllegalArgumentException("fibonacci: n < 0");
    switch (n) {
        case 0:
        case 1:
            return n;
        default:
            int a = fibonacci(n - 1);
            int b = fibonacci(n - 2);
            return a + b;
    }
}
2. sphereVolume
-
 public static double sphereVolume(double radius) {
        if (radius <= 0) {
            throw new IllegalArgumentException("radius must be non-negative");
        }
        return (4.0 / 3.0) * Math.PI * radius * radius * radius;
    }

3. TrueTest
-
public class TrueTest {
    public static boolean twoMoreTrue(String... values) {
        int trueCount = 0;
        for (String value : values) {
            trueCount = Boolean.valueOf(value) ? ++trueCount:trueCount;
        }
        return trueCount >= 2;
    }

    public static void main(String[] args) {
        System.out.println(twoMoreTrue("true", "true", "false")); 
        System.out.println(twoMoreTrue("true", "false", "false")); 
        System.out.println(twoMoreTrue("false", "false", "false")); 
    }
}

4.오류발생관련
-
java.lang.StackOverflowError(스택오버플로우)
postCondition() 메서드에서 fibonacci(Integer.MAX_VALUE)를 호출하는데 이 때 Integer.MAX_VALUE 는 Integer형 중 가장 큰값으로 피보나치 수열을 수행시 이전 두항의 합은 Integer형 범위 값을 넘어갈 수 밖에 없으므로 에러가 날수밖에 없다

# 👍Skills
### Platforms & Languages
![Java](https://img.shields.io/badge/Java-007396.svg?&style=for-the-badge&logo=Java&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F.svg?&style=for-the-badge&logo=Spring&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB.svg?&style=for-the-badge&logo=Python&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84.svg?&style=for-the-badge&logo=Android&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E.svg?&style=for-the-badge&logo=JavaScript&logoColor=white)

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6.svg?&style=for-the-badge&logo=TypeScript&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26.svg?&style=for-the-badge&logo=HTML5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6.svg?&style=for-the-badge&logo=CSS3&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1.svg?&style=for-the-badge&logo=MySQL&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000.svg?&style=for-the-badge&logo=Oracle&logoColor=white)

### Tools
![Git](https://img.shields.io/badge/Git-F05032.svg?&style=for-the-badge&logo=Git&logoColor=white)
![Eclipse IDE](https://img.shields.io/badge/Eclipse%20IDE-2C2255.svg?&style=for-the-badge&logo=Eclipse%20IDE&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-007ACC.svg?&style=for-the-badge&logo=Visual%20Studio%20Code&logoColor=white)
![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84.svg?&style=for-the-badge&logo=Android%20Studio&logoColor=white)

 
# :mailbox_with_mail: Contacts
[![Gmail Badge](https://img.shields.io/badge/Gmail-d14836?style=flat-square&logo=Gmail&logoColor=white&link=mailto:cjrcjrdl1@gmail.com)](mailto:kimsh1691@gmail.com)
[![Naver Badge](https://img.shields.io/badge/Naver-03C75A?style=flat-square&logo=Naver&logoColor=white&link=mailto:cjrcjrdl1@naver.com)](mailto:rlatngus1691@naver.com)

[![Solved.ac
프로필](http://mazassumnida.wtf/api/v2/generate_badge?boj=cjrcjrdl1)](https://solved.ac/cjrcjrdl1)

[![@cjrcjrdl1's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=@cjrcjrdl1)](https://github.com/anuraghazra/github-readme-stats)

<p>
  <img height="180em" src="https://github-readme-stats-sigma-five.vercel.app/api?username=cjrcjrdl1&show_icons=true&include_all_commits=true&bg_color=30,e96443,904e95&title_color=fff&text_color=fff">
  <img height="180em" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=cjrcjrdl1&layout=compact&bg_color=30,e96443,904e95&title_color=fff&text_color=fff">
</p>
<!--
**cjrcjrdl1/cjrcjrdl1** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:



- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
