# Johnny Solution

So the first place (row 1, column 1) has to be a character seen in both `[BQW]` and `[AWE]`. This would only be true for the letter W. Same condition should follow for row 1 and column 2's place, for sets `[RANK]` and `[AWE]`. This is therefore true for letter A. 

Row 2, column 2's place has to be a K because we need to include the condition of adding a K after in the second column from the `[ALP]+K` expression. 

For the 2 places in the third row, we can eliminate the `EP` group because P does not hold true for the condition in the `[RANK]+` expression in the second column. We also cannot choose `PR`, since that would result in `RR` for the bottom row, according to the `PR` or `LE` that we still need to match from `[BQW](PR|LE)`. 

Therefore the bottom row consists of `ER` and the missing place for row 2, column 1 would be L. This is so the `LE` group can match going down in the first column. 

So... Johnny *WALKER!* 🎥
