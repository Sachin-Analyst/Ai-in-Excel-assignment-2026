# Build Steps

## Step 0 - Why this assignment

A Codebasics Excel + AI hands-on assignment, built on the same movie financials table shown in the bootcamp videos, but with new rules. The prompts from the videos don't apply here, each rule below had to be worked out and written fresh.

---

## Phase 1 - Clean the movies sheet

**Step 1**
```
Phase 1 - Clean the movies sheet

Remove the empty column - G
```

**Step 2**
```
Check the inconsistent values in the sheet and use trim function to remove trailing errors. Use helper column and paste the values.
```

**Step 3**
```
Check the text columns are in proper case
```

**Step 4**
```
Ensure we have duplicate entries based on movie id column. If yes use data tools > Remove duplicates and report how many count of duplicated entries and their movie_id and name
```

**Step 5**
```
Check the column is blank using the respective formula, replace empty text cells into Not Available. Numeric columns containing empty or null remain unchanged.
```

**Step 6**
```
Ensure the values in the respective columns has consistent alignment and one data type format
```

Cleaning reset the table's default design, so two follow-up prompts brought it back:

**Step 7**
```
Make the table design headers looks dark and font color white. and the value design remain unchanged
```

**Step 8**
```
Make sure the borders of columns both right and left sides has width to ensure seperate visibility (One column left side border was not applied)
```

---

## Phase 2 - Clean MovieFinancials

**Step 1**
```
Phase 2 - Clean MovieFinancials. 

Check there is inconsistent values in the text column and use the trim function. Numeric values/columns remains unchanged
```

**Step 2**
```
Ensure there is duplicate entries based on the movie_id and report the count of duplicate entries and their id and name
```

---

## Phase 3 - Watch Verdict

**Step 1**
```
Phase 3 - Watch Verdict. 

Create a new column name called watch_verdict based on the conditions below
a) When the imdb rating is equals to 8 and above , add the value to be Must Watch
b) When the imdb rating is equals to 6 above and less than 8 , and the value to be Worth of watch
c) When the imdb rating is below 6, values to be Skip
d) When the imdb rating is missing , empty , null , the values to be Not rated

Use formula
```

**Step 2**
```
Report the total count of movies under the watch verdict conditions
```

---

## Phase 4 - ROI %

**Step 1**
```
Phase 4 - ROI %. 

Create a new column right side of watch_verdict named roi_pct based on the formula
roi_pct = (revenue usd - budget usd) / budget usd and format it as percentage
If there is null/empty cells in numeric columns remains unchanged make sure it does not show any error message in those cells
```

**Step 2**
```
Ensure the column in the roi_pct is in the format percentage and with no decimals
```

**Step 3**
```
Highlight the rows light red and ensure the values are readable, based on the roi_pct which has less than 0. Skip this rule for the empty roi_pct cells
```

**Step 4**
```
Highlight the rows light amber and ensure the values are readable, based on the roi_pct which has higher than and equals to 1000. Skip this rule for the empty roi_pct cells
```

---

## Phase 5 - Table design

**Step 1**
```
Phase 5 - Table design. 

Make the table design headers looks dark and font color white and the values should not hold banded rows design.
```

**Step 2**
```
Make sure the borders of columns both right and left sides has width to ensure separate visibility.
```

**Step 3**
```
Skip the rule for highlighted rows based on the roi_pct conditions
```

---

## Phase 6 - Language summary

**Step 1**
```
Phase 6 - Language summary. 
Create a new sheet named Language summary and build a summary based on language names and for each language show the total count of movies, average imdb ratings and total profits in usd millions (Revenue usd - Budget usd). Include the languages even there is no movies. make sure it is the order of language id
```

**Step 2**
```
If the languages had 0 movies make sure you add values 0 in the respective following columns movie count , average imdb rating and total profits usd. Remaining values are unchanged
```

**Step 3**
```
Build a horizontal clustered bar chart based on the total profits by all languages. Include the languages even they made no movies. turn on the data labels (outside end) and turn off the gridlines for the chart and the bar color - green. Build a chart directly from the language summary columns and do not copy or paste the values of the languages or profit anywhere in the sheet.
```

**Step 4**
```
Do not make any changes in the sheet. Report what did you done when calculating average imdb rating based on languages when the imdb rating are null or empty
```
