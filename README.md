# jekyll-base

Fresh Jekyll install from running "jekyll new ..."
Has a security issue with the jekyll version that is to low. 

1 jekyll vulnerability found in Gemfile.lock a day ago
Remediation
Upgrade jekyll to version 3.6.3 or later. For example:

gem "jekyll", ">= 3.6.3"                                                            ---I don't know how to do this---
Always verify the validity and compatibility of suggestions with your codebase.

Details
CVE-2018-17567 More information
moderate severity
Vulnerable versions: < 3.6.3
Patched version: 3.6.3
Jekyll through 3.6.2, 3.7.x through 3.7.3, and 3.8.x through 3.8.3 allows attackers to access arbitrary files by specifying a symlink in the "include" key in the "_config.yml" file.
