# test coverage for  [cucumber (v1.3.2)](http://github.com/cucumber/cucumber-js)  [![npm package](https://img.shields.io/npm/v/npmtest-cucumber.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cucumber) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cucumber.svg)](https://travis-ci.org/npmtest/node-npmtest-cucumber)
#### The official JavaScript implementation of Cucumber.

[![NPM](https://nodei.co/npm/cucumber.png?downloads=true)](https://www.npmjs.com/package/cucumber)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cucumber/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cucumber/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cucumber/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cucumber/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cucumber/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cucumber/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cucumber/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cucumber/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-cucumber/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-cucumber/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-cucumber%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cucumber/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cucumber/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-cucumber%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cucumber/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cucumber/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cucumber/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Julien Biezemans",
        "email": "jb@jbpros.com",
        "url": "http://jbpros.net"
    },
    "bin": {
        "cucumber.js": "./bin/cucumber.js",
        "cucumber-js": "./bin/cucumber.js",
        "cucumberjs": "./bin/cucumber.js"
    },
    "bugs": {
        "url": "http://github.com/cucumber/cucumber-js/issues",
        "email": "cukes@googlegroups.com"
    },
    "contributors": [
        {
            "name": "Julien Biezemans",
            "email": "jb@jbpros.com",
            "url": "http://jbpros.net"
        },
        {
            "name": "Fernando Acorreia",
            "email": "fernandoacorreia@gmail.com"
        },
        {
            "name": "Paul Jensen",
            "email": "paulbjensen@gmail.com"
        },
        {
            "name": "Kushal Pisavadia"
        },
        {
            "name": "Olivier Melcher",
            "email": "olivier.melcher@gmail.com"
        },
        {
            "name": "Tristan Dunn",
            "email": "tristanzdunn@gmail.com"
        },
        {
            "name": "Ted de Koning"
        },
        {
            "name": "Renier Morales",
            "email": "renier@morales-rodriguez.net"
        },
        {
            "name": "Aslak Hellesøy",
            "email": "aslak.hellesoy@gmail.com"
        },
        {
            "name": "Aaron Garvey"
        },
        {
            "name": "Omar Gonzalez",
            "email": "omar@almerblank.com"
        },
        {
            "name": "Chris Young",
            "email": "chris@chrisyoung.org"
        },
        {
            "name": "Israel Halle",
            "email": "isra017@gmail.com"
        },
        {
            "name": "Matteo Collina",
            "email": "matteo.collina@gmail.com"
        },
        {
            "name": "Niklas Närhinen",
            "email": "niklas@narhinen.net"
        },
        {
            "name": "Kim, Jang-hwan",
            "email": "janghwan@gmail.com"
        },
        {
            "name": "Michael Zedeler",
            "email": "michael@zedeler.dk"
        },
        {
            "name": "Tom V",
            "email": "tom@toc.com"
        },
        {
            "name": "David Godfrey",
            "email": "reactiveraven@reactiveraven.co.uk"
        },
        {
            "name": "Paul Shannon",
            "url": "http://devpaul.com"
        },
        {
            "name": "Simon Dean",
            "email": "simon@simondean.org",
            "url": "http://www.simondean.org"
        },
        {
            "name": "John Wright",
            "email": "johngeorge.wright@gmail.com"
        },
        {
            "name": "Johny Jose",
            "email": "johny@playlyfe.com"
        },
        {
            "name": "Marat Dyatko",
            "email": "vectart@gmail.com"
        },
        {
            "name": "Tim Perry",
            "email": "tim.perry@softwire.com"
        },
        {
            "name": "Fedotov Daniil",
            "email": "hairyhum@gmail.com"
        },
        {
            "name": "unknown",
            "email": "jharlin@NormanDev2.telogical.com"
        },
        {
            "name": "Ben Van Treese",
            "email": "vantreeseba@gmail.com"
        },
        {
            "name": "Gabe Hayes",
            "email": "gabriel.hayes@gmail.com"
        },
        {
            "name": "Brian Clozel",
            "email": "brian.clozel@gmail.com"
        },
        {
            "name": "Lukas Degener",
            "email": "l.degener@tarent.de"
        },
        {
            "name": "Simon Lampen",
            "email": "simonlampen@vinsight.net"
        },
        {
            "name": "Eddie Loeffen",
            "email": "eddieloeffen@gmail.com"
        },
        {
            "name": "Stanley Shyiko",
            "email": "stanley.shyiko@gmail.com"
        },
        {
            "name": "Artur Kania",
            "email": "kaniartur@gmail.com"
        },
        {
            "name": "Sam Saccone",
            "email": "sam@samx.it"
        },
        {
            "name": "Craig Morris",
            "email": "craig.michael.morris@gmail.com"
        },
        {
            "name": "Gary Taylor",
            "email": "gary.taylor@hismessages.com"
        },
        {
            "name": "Krispin Schulz",
            "email": "krispin.schulz@blackbridge.com"
        },
        {
            "name": "Elwyn",
            "email": "elwyn@L1.co.nz"
        },
        {
            "name": "Jan-Eric Duden",
            "email": "jeduden@gmail.com"
        },
        {
            "name": "kostya.misura",
            "email": "kostya.misura@gmail.com"
        },
        {
            "name": "Julian",
            "email": "microweb10@gmail.com"
        },
        {
            "name": "nebehr",
            "email": "thorgeir@tut.by"
        },
        {
            "name": "Jesse Harlin",
            "email": "harlinjesse@gmail.com"
        },
        {
            "name": "Sonny Piers",
            "email": "sonny@fastmail.net"
        },
        {
            "name": "Will Farrell",
            "email": "will@mojotech.com"
        },
        {
            "name": "Kevin Kirsche",
            "email": "Kev.Kirsche+GitHub@gmail.com"
        },
        {
            "name": "chrismilleruk",
            "email": "chrismilleruk@gmail.com"
        },
        {
            "name": "Mateusz Derks",
            "email": "mateusz.derks@schibsted.pl"
        },
        {
            "name": "Mark Amery",
            "email": "markamery@btinternet.com"
        },
        {
            "name": "Artem Repko",
            "email": "roby-boby@ukr.net"
        },
        {
            "name": "zs-zs",
            "email": "zsolt.zsigmondi@hotmail.com"
        },
        {
            "name": "Dale Gardner",
            "email": "dalegardner@live.com"
        },
        {
            "name": "Charles Rudolph",
            "email": "charles.rudolph@originate.com"
        },
        {
            "name": "Karthik Viswanath",
            "email": "karthik.viswanath-contractor@adp.com"
        },
        {
            "name": "Marcel Hoyer",
            "email": "mhoyer@pixelplastic.de"
        },
        {
            "name": "Artem Bronitsky",
            "email": "quex@yandex.ru"
        },
        {
            "name": "Karine Pires",
            "email": "karine.pires@alterway.fr"
        },
        {
            "name": "Rick Lee-Morlang",
            "email": "rick@lee-morlang.com"
        },
        {
            "name": "Noah Davis",
            "email": "noahd1@yahoo.com"
        },
        {
            "name": "Miika Hänninen",
            "email": "miika.hanninen@gmail.com"
        },
        {
            "name": "Kevin Goslar",
            "email": "kevin.goslar@gmail.com"
        },
        {
            "name": "John Krull",
            "email": "astrom.flux@gmail.com"
        },
        {
            "name": "Maxim Koretskiy",
            "email": "mr.green.tv@gmail.com"
        },
        {
            "name": "seantdg",
            "email": "sm.davis@gmx.com"
        },
        {
            "name": "Marc Burton",
            "email": "marc.burton@first-utility.com"
        },
        {
            "name": "Jonathan Kim",
            "email": "jkimbo@gmail.com"
        },
        {
            "name": "Ádám Gólya",
            "email": "adam.golya@lab.coop"
        },
        {
            "name": "Scott Deakin",
            "email": "scott.deakin@kantar.com"
        },
        {
            "name": "efokschaner",
            "email": "eddyaod@gmail.com"
        },
        {
            "name": "John McLaughlin",
            "email": "john.mjhm@gmail.com"
        },
        {
            "name": "Josh Goldberg",
            "email": "joshuakgoldberg@outlook.com"
        },
        {
            "name": "Artur Pomadowski",
            "email": "artur.pomadowski@gmail.com"
        },
        {
            "name": "Benjamín Eidelman",
            "email": "beneidel+gh@gmail.com"
        },
        {
            "name": "Jan Molak",
            "email": "jan.molak@smartcodeltd.co.uk"
        },
        {
            "name": "dbillingham",
            "email": "dbillinghamuk@yahoo.co.uk"
        },
        {
            "name": "Jonathan Gomez",
            "email": "jonathanbgomez@gmail.com"
        },
        {
            "name": "Oliver Rogers",
            "email": "oli.rogers@gmail.com"
        },
        {
            "name": "Hugues Malphettes",
            "email": "hmalphettes@gmail.com"
        }
    ],
    "dependencies": {
        "camel-case": "^3.0.0",
        "cli-table": "^0.3.1",
        "co": "^4.6.0",
        "colors": "^1.1.2",
        "commander": "^2.9.0",
        "duration": "^0.2.0",
        "figures": "1.7.0",
        "gherkin": "^4.1.0",
        "glob": "^7.0.0",
        "is-generator": "^1.0.2",
        "lodash": "^4.0.0",
        "stack-chain": "^1.3.5",
        "stacktrace-js": "^1.3.0"
    },
    "description": "The official JavaScript implementation of Cucumber.",
    "devDependencies": {
        "ansi_up": "^1.3.0",
        "async": "^1.5.0",
        "browserify": "^13.0.0",
        "coffee-script": "^1.12.4",
        "connect": "^3.4.0",
        "exorcist": "^0.4.0",
        "fs-extra": "^0.26.0",
        "jasmine": "2.4.1",
        "jshint": "^2.9.1",
        "json-diff": "^0.3.1",
        "rimraf": "^2.4.3",
        "serve-static": "^1.10.0",
        "sinon": "^1.17.3",
        "tmp": "0.0.28"
    },
    "directories": {
        "lib": "./lib"
    },
    "dist": {
        "shasum": "05c94590ab625c08792a6017a477b4cba99b8149",
        "tarball": "https://registry.npmjs.org/cucumber/-/cucumber-1.3.2.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "files": [
        "bin/",
        "lib/",
        "release/"
    ],
    "gitHead": "7eeb7987814c290b07e34b7db7992ae38f432187",
    "homepage": "http://github.com/cucumber/cucumber-js",
    "keywords": [
        "testing",
        "bdd",
        "cucumber",
        "gherkin",
        "tests"
    ],
    "license": "MIT",
    "main": "./lib/cucumber",
    "maintainers": [
        {
            "name": "charlierudolph",
            "email": "charles.w.rudolph@gmail.com"
        },
        {
            "name": "jbpros",
            "email": "jb@jbpros.com"
        }
    ],
    "name": "cucumber",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/cucumber/cucumber-js.git"
    },
    "scripts": {
        "build-release": "node ./scripts/release.js",
        "feature-test": "node ./bin/cucumber.js",
        "feature-test-es5": "node ./bin/cucumber.js -p es5",
        "lint": "jshint bin features lib scripts spec",
        "prebuild-release": "npm install",
        "test": "npm run lint && npm run unit-test && npm run feature-test",
        "test-es5": "npm run lint && npm run unit-test && npm run feature-test-es5",
        "unit-test": "jasmine"
    },
    "version": "1.3.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
