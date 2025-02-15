### v3.0.0

[2020.07.20; Maikuolan] First stable release for the phpMussel v3 uploads handler ("phpMussel Web").

__*Why "v3.0.0" instead of "v1.0.0?"*__ Prior to phpMussel v3, the "phpMussel Core", "phpMussel CLI-mode", "phpMussel Front-End", and "phpMussel Uploads Handler" ("phpMussel Web") were all bundled together as a single repository (phpMussel/phpMussel). Since phpMussel v3, these each all have their own, separate repositories. I've opted to start releases at this repository (phpMussel/Web) at *v3.0.0*, in order to avoid confusion with previous versions of the "phpMussel uploads handler" which exist outside this repository.

### v3.0.1

[2020.07.31; Maikuolan]: Improved the way that the (generated by ...) notice, displayed at the footer of HTML pages, is rendered.

[2020.10.09; Maikuolan]: Aesthetic patch + added a new theme.

### v3.1.0

[2020.10.30; New Feature; Maikuolan]: Added the ability to specify a custom assets path to the instantiated Web object.

[2020.12.04; Maikuolan]: Maintenance release (dependencies update, repository cleanup, etc).

### v3.1.1

[2021.03.03; Maikuolan]: Maintenance release.

### v3.1.2

[2021.04.27; Maikuolan]: Added missing fullmoon template file.

[2021.05.01; Bug-fix; Maikuolan]: Log truncation not being calculated properly; Fixed.

[2021.05.28; Maikuolan]: Performed some minor refactoring.

### v3.2.0

[2021.06.10; Maikuolan]: Added a configuration directive for returning a 415 status code for when an upload is blocked due to its filetype being blacklisted.

### v3.2.1

[2021.10.30; Maikuolan]: Code-style cleanup: Public before private properties, magic before public before private methods.

### v3.2.2

[2022.02.01; Bug-fix; Maikuolan]: Failed to correctly determine the client's IP address under certain circumstances (e.g., multiple choices available via HTTP_X_FORWARDED_FOR); Fixed.

[2022.02.14; Maikuolan]: Maintenance release.

### v3.2.3

[2022.07.28~08.11; Maikuolan]: Added L10N for Persian/Farsi, Hebrew, Malay, and Ukrainian.

### v3.3.0

[2022.09.26; New Feature; Maikuolan]: Custom headers/footers for front-end pages and the upload denied page now be set directly via configuration.
