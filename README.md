# Hi! I am Marko 

## I'm a Software Development Student
```javascript
class SoftwareEngineer {
  constructor() {
    this.name = "Marko";
    this.role = "Software Development Student";
    this.languages = ["HTML/CSS", "JavaScript", "Python"];
    this.interests = ["Web Development", "Machine Learning", "Cloud Computing"];
    this.socialMedia = {
      LinkedIn: "https://linkedin.com/in/marko-villemson",
      GitHub: "https://github.com/Villemson"
    };
  }

  introduceSelf() {
    console.log(`Hi there! My name is ${this.name}. I'm a ${this.role}, passionate about coding and exploring new technologies.`);
    console.log("Here are a few things about me:");
    console.log("- I enjoy learning new programming languages and frameworks.");
    console.log("- My current interests include web development, Osint.");
    console.log("- I love collaborating with others and sharing knowledge.");
    console.log("You can connect with me on the following platforms:");
    for (let platform in this.socialMedia) {
      console.log(`- ${platform}: ${this.socialMedia[platform]}`);
    }
  }
}

let me = new SoftwareEngineer();
me.introduceSelf();

# About Me
- 👨‍💻 Currently studying software development, passionately diving into the world of coding and new technologies.
- 🌱 I'm currently focusing on web development and OSINT.
- 💡 I enjoy learning new programming languages and frameworks.
- 🤝 I love collaborating with others and sharing knowledge.

## Connect with Me
- LinkedIn: [marko-villemson](https://linkedin.com/in/marko-villemson)
- GitHub: [Villemson](https://github.com/Villemson)

