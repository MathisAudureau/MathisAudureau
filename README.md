```ts
export class MathisAudureau {
  private static discord: string = "Mathïs#1799"

  public static setDiscord(userTag) {
    this.discord = userTag
  }

  public static getInfo() {
    return {
      name: "Mathis",
      age: "15 yo",
    }
  }

  public static getLangage() {
    return {
      front-end: ["Html", "Css", "NxtJS", "React", "TailwindCSS", "Bootstrap"],
      back-end: ["Javascript", "Typescript", "Adonis"],
      discord-bot: ["Javascript", "Typescript", "Discord-Factory"]
    }
  }

 public static getMedia() {
    return this.discord
  }
```
