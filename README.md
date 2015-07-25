khayyam
=======

Jalali Date and Time types and algorithms for Python2 and Python3.

Jump To:

 * [Documentation](http://vahid.dobisel.com/khayyam)
 * [Python package index](https://pypi.python.org/pypi/khayyam)


#### Change Log
                                 
  * 2.6.0-beta (2015-07-25)
    * All possible formatting directives(a-z, A-Z) are supported, except: T
    * All format directives are tested.
    * Formatting and parsing test cases moved to `khayyam.formatting.tests` package.
    * In project: docs/html
    * `JalaliDate.from_julian_days` renamed to `JalaliDate.fromjuliandays`
    * `JalaliDate.from_julian_days` renamed to `JalaliDate.fromjuliandays`
    * `JalaliDate.days_in_month` renamed to `JalaliDate.daysinmonth`
    * `JalaliDate.is_leap` renamed to `JalaliDate.isleap`
    * `JalaliDatetime` Modern properties.
    
    

  * 2.5.0-beta (2015-07-23)
    * Doc: doctest
    * Doc: formatting and parsing directives table.
    * Doc: adding examples of new formatting directives in introduction: %D, %J, %R, %N, %n, %F, %h, %i, %r, %s, %o.
    * local date & time formats are changed: digits -> persian
    * Formatting and parsing test cases has been separated

  * 2.4.0-beta (2015-07-22)
    * Persian Numbers
    * %D, %J, %R, %N, %n, %F, %h, %i, %r, %s, %o directives has been added.

  * 2.3.0-alpha (2015-07-22)
    * Constants are moved to formatting packages except MINYEAR, MAXYEAR ans weekdays.
    * Doc: Introduction -> Formatting & parsing
    * Doc: Introduction -> Converting
    * New methods `jalaliDate.todate`, `jalaliDate.fromdate`, `jalaliDatetime.todatetime` and `jalaliDatetimefromdatetime`
    * Removed methods `jalaliDate.to_date`, `jalaliDate.from_date`, `jalaliDatetime.to_datetime` and `jalaliDatetime.fromdate_time`
    

  * 2.2.1-alpha (2015-07-21)
    * Doc: Reading package's version automatically from khayyam/__init__.py in `sphinx/conf.py`
    * Doc: Installation: (PYPI, Development version)
    * Doc: Testing
    * Doc: Contribution

  * 2.2.0-alpha (2015-07-21)
    * Generating API Documentation  

  * 2.1.0-alpha (2015-07-20)
    * Adding ascii weekdayname in `JalaliDatetime` and `JalaliDate` representation(__repr__). 

  * 2.0.0-alpha (2015-07-19) Incompatible with < 2.0.0
    * JalaliDate: method `localformat` renamed to `localdateformat`.
    * JalaliDatetime: method `localformat` renamed to `localdatetimeformat`.
    * JalaliDatetime: method `localshortformat_ascii` renamed to `localshortformatascii`.
    * JalaliDatetime: method `localdatetimeformat_ascii` renamed to `localdatetimeformatascii`.
    * JalaliDatetime: method `ampm_ascii` renamed to `ampmascii`.
    * JalaliDatetime: Migrating to New Formatter/Parser Engine
    * TehTz: renamed to TehranTimezone
    * Comparison and Timezones
    * Comparison with `datetime.date` & `datetime.datetime`
    * Fixing timezone bug
    
  * 1.1.0 (2015-07-17)
    * JalaliDate: New Formatter/Parser & full unittests.
    