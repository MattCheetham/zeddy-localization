### zeddy-localization

This is the community language repository for [Zeddy](https://apps.apple.com/gb/app/zeddy/id1451295003).

If there is a language you'd like to see Zeddy localized to, feel free to submit a pull request.

Please do not add multiple languages in the same pull request — this way, there can be a discussion thread for each language for any changes or tweaks that need to be made, and give others opportunity for peer review.

### Disk Structure
Languages are structured in folders as such:

`en.lproj/Localizable.strings`

Where `en` is replaced by the [ISO 639-1 two-letter language code](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes), and the `Localizable.strings` file is structured as per the English (`en`) version.

Please do not include any other files in a pull request.

There are multiple files in each folder that correspond to different parts of the app, such a Siri localizations and the legacy parts of the app. You should translate all of these.

### Localization

Strings are denoted as `"KEY"` = `"value"`, where the keys remain the same across all languages, and the values are localized. There must be a `;` at the end of each line.

`"alert_login_error_dismiss" = "Okay";`

Where you see a `%@` or `%i` token, this denotes a value that is replaced at runtime — in most cases will be a number. The corresponding localized value must keep the token in the right place to provide the same meaning as the English value.

`"last_updated" = "Last updated: %@";`

`"charger_type" = "%@ charger";`


### Credits

Please append the name you would like to be credited by to the pull request or the comment block at the top of the Localizable.strings file.
