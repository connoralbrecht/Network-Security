# Project 7 - WordPress Pentesting

Time spent: **12** hours spent in total

> Objective: Find, analyze, recreate, and document **three vulnerabilities** affecting an old version of WordPress

## Pentesting Report

1. Authenticated Stored Cross-Site Scripting (XSS)
  - [ ] Summary: 
    - Vulnerability types: Cross-Site Scripting
    - Tested in version: 4.2
    - Fixed in version: 4.2.3
  - [ ] GIF Walkthrough: https://github.com/connoralbrecht/CodePath-Week-7/blob/master/test.gif
  - [ ] Steps to recreate: https://klikki.fi/adv/wordpress3.html
  - [ ] Affected source code: https://wpvulndb.com/vulnerabilities/8111
2. Unauthenticated Genericons Cross-Site Scripting (XSS)
  - [ ] Summary: 
    - Vulnerability types: Cross-Site Scripting
    - Tested in version: 4.2
    - Fixed in version: 4.2.2
  - [ ] GIF Walkthrough: https://github.com/connoralbrecht/CodePath-Week-7/blob/master/gener.gif
  - [ ] Steps to recreate: https://codex.wordpress.org/Version_4.2.2
  - [ ] Affected source code: https://wpvulndb.com/vulnerabilities/7979
3. Authenticated Shortcode Tags Cross-Site Scripting (XSS)
  - [ ] Summary: 
    - Vulnerability types: Cross-Site Scripting
    - Tested in version: 4.2
    - Fixed in version: 4.2.5
  - [ ] GIF Walkthrough: https://github.com/connoralbrecht/CodePath-Week-7/blob/master/short%20code.gif
  - [ ] Steps to recreate: http://blog.knownsec.com/2015/09/wordpress-vulnerability-analysis-cve-2015-5714-cve-2015-5715/
  - [ ] Affected source code: https://wpvulndb.com/vulnerabilities/8186

## Assets

List any additional assets, such as scripts or files

## Resources

- [WordPress Source Browser](https://core.trac.wordpress.org/browser/)
- [WordPress Developer Reference](https://developer.wordpress.org/reference/)

GIFs created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while doing the work

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
