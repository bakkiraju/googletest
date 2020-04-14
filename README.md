# Google Test

Modified original googletest to 
1. explicitly allow skipping of tests in a testsuite by using set_skipped(true)
2. Show the skipped tests using the flag --gtest_show_skips

These were added because I re-purposed original googletest to create a Diagnostics hardware test infrastucture.

