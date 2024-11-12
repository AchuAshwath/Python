### Aware and Naive objects

Date and time objects may be categorized as “aware” or “naive” depending on whether or not they include time zone information.

For applications requiring aware objects, datetime and time objects have an optional time zone information attribute, tzinfo, that can be set to an instance of a subclass of the abstract tzinfo class. These tzinfo objects capture information about the offset from UTC time, the time zone name, and whether daylight saving time is in effect.

## Constants

- datetime.MINYEAR - The smallest year number allowed in a date or datetime object. MINYEAR is 1.

- datetime.MAXYEAR - The largest year number allowed in a date or datetime object. MAXYEAR is 9999.

- datetime.UTC - Alias for the UTC time zone singleton datetime.timezone.utc.

