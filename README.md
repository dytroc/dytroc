```kotlin
object Dytro : Human(
    nationality=Nationality.REPUBLIC_OF_KOREA,
    fluentLanguages=setOf(Language.KOREAN, Language.ENGLISH)
), Gamer, Programmer {
    override val favoriteVideoGames = setOf(MobileGames.BLUE_ARCHIVE, PCGames.MINECRAFT)
    
    override val githubUsername = "dytroc"
    override val fluentProgrammingLanguages = setOf(
        ProgrammingLanguage.KOTLIN,
        ProgrammingLanguage.JAVASCRIPT,
        ProgrammingLanguage.TYPESCRIPT,
        ProgrammingLanguage.JAVA,
    )
    override val naiveProgrammingLanguages = setOf(
        ProgrammingLanguage.PYTHON,
        ProgrammingLanguage.RUST,
        ProgrammingLanguage.GO,
    )
}
```
