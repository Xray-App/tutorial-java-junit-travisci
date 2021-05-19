# tutorial-java-junit-travisci
[![Build Status](https://travis-ci.com/github/Xray-App/tutorial-java-junit-travisci.svg?branch=main)](https://travis-ci.com/github/Xray-App/tutorial-java-junit-travisci)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FXray-App%2Ftutorial-java-junit-travisci.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2FXray-App%2Ftutorial-java-junit-travisci?ref=badge_shield)
[![license](https://img.shields.io/badge/License-BSD%203--Clause-green.svg)](https://opensource.org/licenses/BSD-3-Clause)
[![Gitter chat](https://badges.gitter.im/gitterHQ/gitter.png)](https://gitter.im/Xray-App/community)

## Overview
Code that support the tutorial [Integrations with TravisCI](https://docs.getxray.app/display/XRAYCLOUDDRAFT/Integrations+with+TravisCI) showcasing the integration between [Xray Test Management](https://www.getxray.app/) and [TravisCI](https://travis-ci.com/) using Java and JUnit.

The test automation code implements a basic [Playwright test](https://github.com/microsoft/playwright-test)

## Prerequisites
In order to run this tutorial you need to have [Java](https://www.oracle.com/pt/java/technologies/javase-downloads.html) and [Maven](https://maven.apache.org/install.html).

## Running
Compilation and testing can be executed locally with the following command
```
mvn clean compile test --file pom.xml
```

## Submitting results to Jira
Results can be submitted to Jira so that they can be shared with the team and their impacts be easily analysed.
This can be achieved using [Xray Test Management](https://www.getxray.app/) as shown in further detail in this [tutorial](https://docs.getxray.app/display/XRAYCLOUDDRAFT/Integrations+with+TravisCI).

## Contact

Any questions related with this code, please raise issues in this GitHub project. Feel free to contribute and submit PR's.
For Xray specific questions, please contact [Xray's support team](https://jira.xpand-it.com/servicedesk/customer/portal/2).

## References

- [TravisCI](https://travis-ci.com/)
- [How Xray processes JUnit XML reports](https://docs.getxray.app/display/XRAYCLOUD/Taking+advantage+of+JUnit+XML+reports)


## LICENSE

[BSD 3-Clause](LICENSE)