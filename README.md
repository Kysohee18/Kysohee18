<div align="center">

# Hi there, I'm Shahky! 👋

### *"Ngilmu iku kalakone kanthi laku"*
*(Knowledge is achieved through action)*

---

</div>

<div align="center">

## 👨‍💻 About Me

```javascript
class ShahkyProfile {
    constructor() {
        this.name    = "Shahky Yandhana Putra";
        this.role    = "Information Technology Student @ UMY";
        this.code    = ["Software Engineering", "Web Development"];
    }

    getDailyLife() {
        return {
            coding: ["Next.js", "Laravel", "Python", "JavaScript"],
            current_focus: ["System Architecture", "Node.js", "C++"],
            music_playlist: {
                artists: ["The 1975", "LANY", "Perunggu"],
                genre: "Indie Pop & Alternative"
            },
            quote: "Talk is cheap. Show me the code."
        };
    }
}

const me = new ShahkyProfile();
console.log(me.getDailyLife());
