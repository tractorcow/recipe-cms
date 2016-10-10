# 3.2.0-rc2

<!--- Changes below this line will be automatically regenerated -->

## Change Log

### Security

 * 2016-08-02 [b0ba201](https://github.com/silverstripe/silverstripe-framework/commit/b0ba2015d9684ee7b124dafcf6b59b046e20f8ed) value / title escaping in CheckboxSetField and OptionsetField (Damian Mooyman) - See [ss-2016-015](http://www.silverstripe.org/download/security-releases/ss-2016-015)
 * 2016-07-25 [d1163d8](https://github.com/silverstripe/silverstripe-framework/commit/d1163d87b70e3e147f22a1e423b9f70f6fd85e8f) Autologin cookies are ignored if autologin is disabled (Daniel Hensby) - See [ss-2016-014](http://www.silverstripe.org/download/security-releases/ss-2016-014)
 * 2016-07-22 [8bbf1ca](https://github.com/silverstripe/silverstripe-framework/commit/8bbf1caae665a07b3e44e8d5d32556a03d38c296) Uncasted member name (Daniel Hensby) - See [ss-2016-013](http://www.silverstripe.org/download/security-releases/ss-2016-013)
 * 2016-07-15 [08384bb](https://github.com/silverstripe/silverstripe-framework/commit/08384bb4d6b98c44388ffb4727c317ed14fe3c81) Reset `Member::Salt` on password change (Daniel Hensby) - See [ss-2016-008](http://www.silverstripe.org/download/security-releases/ss-2016-008)
 * 2016-07-14 [782c18f](https://github.com/silverstripe/silverstripe-framework/commit/782c18fd13b9fb92707d0ea3b231023204928297) ChangePasswordForm does not check $member-&gt;canLogin before login (Daniel Hensby) - See [ss-2016-011](http://www.silverstripe.org/download/security-releases/ss-2016-011)
 * 2016-07-14 [c1525c8](https://github.com/silverstripe/silverstripe-reports/commit/c1525c8ba68f6d4fc0fb5f30929f9678c0199411) Missing ACL check on ReportAdmin (Daniel Hensby) - See [ss-2016-012](http://www.silverstripe.org/download/security-releases/ss-2016-012)
 * 2016-05-03 [41be95c](https://github.com/silverstripe/silverstripe-framework/commit/41be95c95a55031412ee4056aeee5c2c69595836) Encode user supplied URL for embeding into page (Daniel Hensby) - See [ss-2016-007](http://www.silverstripe.org/download/security-releases/ss-2016-007)

### API Changes

 * 2016-10-10 [d66821b](https://github.com/tractorcow/recipe-core/commit/d66821ba71d1d9ea2e8dc1b9664b4162b21e06e4)  (Damian Mooyman)

### Bugfixes

 * 2016-08-15 [ac26816](https://github.com/silverstripe/silverstripe-framework/commit/ac2681658ac33f6c060b7f5f881bd94eba92791b) Fix regression in url concatenation #4967 (Damian Mooyman)
 * 2016-08-15 [ef85618](https://github.com/silverstripe/silverstripe-cms/commit/ef856185ab7a86f25fda718a88256c9e6e27a763) Fix regression in FormField casting (Damian Mooyman)
