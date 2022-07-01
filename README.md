```ts
export default class MathisAudureau {
  private static discord: string = "Mathïs#1799"

  public static setDiscord(userTag: string) {
    this.Discord = userTag
  }

  public static getInfo() {
    return {
      name: "Mathis",
      age: "15 yo",
    }
  }

  public static getLangage() {
    return {
      front_end: ["HTML", "CSS", "NextJS", "React", "TailwindCSS", "Bootstrap"],
      back_end: ["JavaScript", "TypeScript", "Adonis"],
      discord_bot: ["JavaScript", "TypeScript", "Discord-Factory"]
    }
  }

 public static getMedia() {
    return this.Discord
  }
```
