<div align=center>
   <img src="https://capsule-render.vercel.app/api?type=Wave&height=190&section=header&text=YEWON%20GITHUB&fontSize=90&theme=tokyonight&fontAlignY=65&stroke=1E1C3F&strokeWidth=2.5&animation=twinkling"& />   
</div> 


<div align=center>
  <br><br><br><br>
  <h2> Hi, I'm yewon! <img src="https://media0.giphy.com/media/Wj116ZszUZEwRIoz0j/giphy.gif?cid=ecf05e470gr888wut66j8qdpdeemuoue8wxz6bs47d8pls2m&rid=giphy.gif&ct=s" width="50"> </h2>
  
  
  <div align=left>
  <h3> <img src="https://media4.giphy.com/media/TvNa6lOfIXu7uUGQ4F/giphy.gif?cid=ecf05e47ud2k9nlq5g5zz5bux7vhoezpdvt58t5bptpm8mhy&rid=giphy.gif&ct=s"  width="50"> A little more about me...</h3>


```java
public class Developer {
	
	public String[] code;
	public String[] tools;
	public String email;
	public String blog;
	public String bio;
	
	public Developer(String[] code, String[] tools, String email, String blog, String bio) {
		this.code = code;
		this.tools = tools;
		this.email = email;
		this.blog = blog;
		this.bio = bio;
	}
	
	public void introduceDeveloper() {
		
		System.out.println("========================================");
		System.out.println("bio : " + bio);
		System.out.println("code : " + Arrays.toString(code));
		System.out.println("tools : " + Arrays.toString(tools));
		System.out.println("email : " + email);
		System.out.println("blog : " + blog);
		System.out.println("========================================");
		
	}		
}

public class main {

	public static void main(String[] args) {
     
		String[] code = {"Java", "JavaScript", "jQuery","HTML5", "CSS3", "Spring",
				"SpringBoot", "MySQL", "MariaDB"};
		String[] tools = {"EclipseIDE", "IntelliJ", "VisualStudioCode","ApacheTomcat", 
				"Figma", "GitHub", "AWS"};
		String email = "ajdanddl6321@gmail.com";
		String blog = "https://velog.io/@woodybuzz";
		String bio = "안녕하세요! 현재 자바 백엔드 개발자가 되기 위해 열심히 공부하고 있습니다.";
		
		Developer yewon = new Developer(code, tools, email, blog, bio);
		
		yewon.introduceDeveloper();
     
	}

}     
     
```
</div> 
</div> 

