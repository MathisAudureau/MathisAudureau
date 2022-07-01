```ts
export default class MathisAudureau {
  private static DISCORD: string = "Mathïs#1799"

  public static setDiscord(userTag: string) {
    this.DISCORD = userTag
  }

  public static getInfo() {
    return {
      name: "Mathis",
      age: "15 yo",
    }
  }

  public static getLanguage() {
    return {
      front_end: ["HTML", "CSS", "NextJS", "React", "TailwindCSS", "Bootstrap"],
      back_end: ["JavaScript", "TypeScript", "Adonis"],
      discord_bot: ["JavaScript", "TypeScript", "Discord-Factory"]
    }
  }

 public static getMedia() {
    return this.DISCORD
  }
}  
```
