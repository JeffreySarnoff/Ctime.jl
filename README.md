## UniversalLocalTime 

Universal Time and Local Time with a great deal of care in how libc is used.


##### Copyright &copy; 2015-2018. by Jeffrey Sarnoff.  &nbsp; &nbsp; This material may be used in accord with the MIT License.

------

This package may improve untidy time keeping.  

- Use it only if you agree I have no liabilty.

-----

#### A Safer Way 

Calendar dates are local delinations,  times-of-day are moving demarcations.

Computing with time reliably requires consistent attention to the underpinnings of chronology.   
It is not an easy task, and many are satisfied with a process that is good-enough most times.

This package obtains as reference the time-of-day and its date at the IERS Standard Meridan,
from the local computing environment.  For personal computers that are not synced through
a managed time servce, this is likely accurate to within two minutes except during periods
when the local timezone "moves the wallclock" forward or backward by 15, 30, or 60 minutes.
Computer systems that are networked with an actively managed time server may expect their
time codes to stay within five seconds of accurate -- the variations in latency and 
inhomgeneities of network paths limit expectations.  For systems that manage time with
co-located special purpose hardware that is backed by a Level II time service, the
locally obtained time may be reported with an uncertainty of 100 nanoseconds or better.

Some organizations have invested in software that improves clocking consistancy
and use hardware managed chronometry in an effort to stay within 10 nanoseconds
of Universal Coordinated Time (UTC).  FINRA and MiFID require high frequency
financial transactions are recorded with that sort of assurance.


****
Copyright &copy; 2018 by Jeffrey A Sarnoff. 
This material is made available under The MIT License.
****

