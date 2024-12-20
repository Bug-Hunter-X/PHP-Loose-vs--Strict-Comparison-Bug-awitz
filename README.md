# PHP Loose vs. Strict Comparison Bug

This repository demonstrates a common error in PHP related to loose comparison (==) versus strict comparison (===).

Loose comparison checks if two values are equal after type juggling.  Strict comparison requires both value and type to be identical.  The difference can lead to unexpected results and bugs.

The `bug.php` file shows a simple example of this issue. The `bugSolution.php` file demonstrates a corrected version using strict comparison.