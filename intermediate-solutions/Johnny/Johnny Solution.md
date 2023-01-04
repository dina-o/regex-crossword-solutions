# Johnny Solution

So the first place (row 1, column 1) has to be a character seen in both `[BQW]` and `[AWE]`. This would only be true for the letter W. Same condition should follow for row 1 and column 2's place, for sets `[RANK]` and `[AWE]`. This is therefore true for letter A. 

Since we've already matched BQW from `[BQW] (PR|LE)`, we need to match the second row and first column place with characters from either `PR` or `LE`. Therefore, the answer would be L because 

Row 2, column 2's place has to be a K because we need to include the condition of adding a K somewhere in the second row from the `[ALP]+K` expression. 

Since we started with L in the second row, first column place, we need to finish the OR expression by including the E from LE in the third row first column place. 

Finally, we have a choice of finishing either group `PR` or `ER` or `EP` for the third row, second column place. We need to use the ER, therefore putting R in the third row, second column. This is because E was already acounted for in our previous step, and P from EP does not match the second expression we need to fulfill: `[RANK]+. P` is not found inside this group of characters.


So... Johnny *WALKER!* 🎥
