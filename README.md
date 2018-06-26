# app-localize-chrome-i18n-mixin [![Build Status](https://travis-ci.org/Collaborne/app-localize-chrome-i18n-mixin.svg?branch=master)](https://travis-ci.org/Collaborne/app-localize-chrome-i18n-mixin)

[![Published on Vaadin  Directory](https://img.shields.io/badge/Vaadin%20Directory-published-00b4f0.svg)](https://vaadin.com/directory/component/Collaborneapp-localize-chrome-i18n-mixin)
[![Stars on vaadin.com/directory](https://img.shields.io/vaadin-directory/star/Collaborneapp-localize-chrome-i18n-mixin.svg)](https://vaadin.com/directory/component/Collaborneapp-localize-chrome-i18n-mixin)

_[Blog post about the element](https://medium.com/collaborne-engineering/localize-polymer-apps-with-translation-platform-46a2acb9373b)_

Mixin to localize Polymer applications with [Chrome i18n](https://developer.chrome.com/extensions/i18n) translation files. The mixin is a thin wrapper around [`<app-localize-behavior>`](https://github.com/PolymerElements/app-localize-behavior).

Chrome i18n translation files have these advantages over the localization files required by `<app-localize-behavior>`:

- Each message can be supplemented by a description, which gives translators additional context.

- Chrome i18n is a widely used standard, which is supported by translation platforms like [Transifex](https://docs.transifex.com/formats/chrome-json). This avoids the build step to transform output from a translation platform to the `<app-localize-behavior>` localization file.


To use the mixin:

`bower install app-localize-chrome-i18n-mixin`


## License

    This software is licensed under the Apache 2 license, quoted below.

    Copyright 2011-2017 Collaborne B.V. <http://github.com/Collaborne/>

    Licensed under the Apache License, Version 2.0 (the "License"); you may not
    use this file except in compliance with the License. You may obtain a copy of
    the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
    WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
    License for the specific language governing permissions and limitations under
    the License.
