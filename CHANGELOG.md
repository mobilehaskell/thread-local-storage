## 0.1.1 [2017.01.22]
* Expose `Data.TLS.PThread.Internal`. Note that there are no API guarantees
  whatsoever with this module, so use it with caution.
* Add `pthread` to `extra-libraries`. Without it, some systems suffer
  from linker errors when using this library.
* Fix build on GHC 7.6 and 7.8.
