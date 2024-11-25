<div align="center">

<h1>Hi <img src="images/Hi.gif" width="40px" />, I'm <a href="https://www.github.com/Spoony1337">Spoony</a>!</h1>
</div>

```java
  public class Spoony extends Human implements Gamer, Developer {

	@Override
	public String getName() {
		return "none";
	}
	
	@Override
	public List<String> getAliases() {
		return Arrays.asList("Spoony", "My Name");
	}

        public Spoony() {
        super("Spoony", "Earth");

        this.addLanguage("Java", "Python", "Javascript", "Kotlin");
        this.addExperience("2 Years+(java)", "3months+(python)", "1week+(kotlin)", "3months+(js)", "Total 2 years+");
     }
   }

	@Override
	public String aboutme() {
		return "I like to learn new things" +
		"\n" + "I like to code Java";
	}
    
	@Override
	public void codingStuff() {
		String[] learning = ["Java", "HTML", "CSS"];
		String tryingTo = "Make good software applications & websites";
	}
	
} 


public abstract class Human {

  @Getter private final String username;
  @Getter private final String country;

  private Set<String> languages = new HashSet<>();
  private Set<String> experiences = new HashSet<>();

  public Human(String username, String placeilive) {
      this.name = username;
      this.country = placeilive;
  }

  public void addLanguage(String... language) {
      this.languages.addAll(language);
  }
  
  public void addExperience(String... experience) {
      this.experiences.addAll(experience);
  }
}
```

<p align = "center"><img src = "https://github-widgetbox.vercel.app/api/profile?username=Spoony1337&data=followers,repositories,stars,commits"></p>
<p align = "center"><img src = "https://github-widgetbox.vercel.app/api/skills?names=java,kotlin,python,html,css,javascript,typescript,dart,c,cpp,csharp,bash,powershell,swift&includeNames=true"></p>

<div align="center">
	
[![Spoony's GitHub stats](https://github-readme-stats.vercel.app/api?username=Spoony1337&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515&count_private=true)](https://github.com/Spoony1337) 
[![My most used languages](https://github-readme-stats.vercel.app/api/top-langs/?username=PaceCodes&layout=compact&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515&count_private=true&langs_count=6)](https://github.com/Spoony1337)
### Profile Visits 

![Visitors](https://komarev.com/ghpvc/?username=Spoony1337&color=blueviolet)
---

</details>

![My github activity graph](https://activity-graph.herokuapp.com/graph?username=Spoony1337&theme=react-dark)

