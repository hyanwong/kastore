--------------------
[2.0.0] - 2020-XX-XX
--------------------

- Major file version bumped because new fields were added to the kastore_t
  struct, leading to potential ABI breakage. No API breakage should occur.

**New features**

- Add kastore_openf function to support FILE objects, and remove
  file seeks. This allows reading from a pipes/FIFOs, and allows
  multiple stores to read from the same stream
  (:user:`grahamgower`, :pr:`88`).

--------------------
[1.1.0] - 2019-03-19
--------------------

- Add `contains` function
- Add `oput` variants that transfer ownership of buffer.
- Various documentation updates.

--------------------
[1.0.1] - 2019-01-24
--------------------

Add support for using kastore as a meson subproject.

--------------------
[1.0.0] - 2019-01-22
--------------------

Remove the dynamic C API option and add support for C++.

--------------------
[0.1.0] - 2018-12-07
--------------------

Initial release of the documented C API.


