### Data Organization and Transformation

## Section 1
## Section 2
## Section 3

## Objectives

- Execute basic data organization and transformation
- Create plots from data table
- Manage files in GitHub and VS Code
- Write in Markdown

## Deliverables

- Blog post in Markdown
- five visualizations of provided data
- OPTIONAL sixth visualization

## Instructions

### General

Make an instructional blog post about how to transform data in `blogpost.md`.

Follow along with the steps below. When they are complete, write up
your data exploration steps as an instructional blog post. This
exercise is to help you engrain the transformation steps by visualizing
each step as you go. The instructions you write should be sufficiently
detailed that another person could follow them, and understand what
is happening with the data. Typically, 3 or 4ish sentences.

Write the blog post as if it could be viewed by the public. The
next lab will create a GitHub website with blog posts that actually
_can_ be viewed online!

Record references you used in this lab.
Relevant in-line references should be included like this
[[1](https://commonmark.org/help/),
[2](https://www.markdownguide.org/extended-syntax/#tables)].
The referenced links should also appear in the Reference Section of
the deliverable markdown file as a numbered list like this:

1. https://commonmark.org/help/
2. https://www.markdownguide.org/extended-syntax/#tables

### Steps

#### Steps that will be useful for blog

- TODO: Create a top-level heading in blogpost.md that says `Data Organization and Transformation`
- TODO: Create an H2 heading in blogpost.md that says `References`
- TODO: Create at least 3 other headings with reasonable text to describe what you are doing
  between the top-level and the references. For now, say `section 1`,`section 2`, `section 3`.

<br>

- TODO: fill out the list below with the requested information and copy it into blogpost.md.

<br>

- Number of initial variables:
- Number of initial observations:
- List of variable names:
- Range of `rawdata`:
- Range of `y`:

<br>

- TODO: make a line plot of `rawdata` alone
- TODO: download or screenshot this and add the files to assets/images
- TODO: name the line plot file `line-initial`
    - the . ending can be any format (.png, .jpg, etc.)

The raw data in the `rawdata` variable needs to undergo three
transformations in order to be interpretable as `x`. The exercise here is
to plot, transform, plot, transform etc... so that you can visualize
what each transformation step does. Only steps that update the `rawdata`
variable need to be plotted as a line plot.

- TODO: Apply the transformation that counts how many times a given observation
  in `rawdata` can be split in half.
    - For example, 8 can be split in half 3 times.
    - 16 can be split in half 4 times.
    - More info on this here
      [[4](https://www.khanacademy.org/math/algebra2/x2ec2f6f830c9fb89:logs/x2ec2f6f830c9fb89:log-intro/a/intro-to-logarithms)]
- TODO: make/name the : `line-01` (all file extensions are fine)
- TODO: from the result of the previous TODO, scale the observations
  up by 10.
- TODO: make/name the plot: `line-02`
- TODO: from the result of the previous TODO, apply the `sign`
  variable to each observation.
    - Example: the sign of -1 applied to the number 1.4 is -1.4
    - Example: the sign of 1 applied to the number 1.4 is 1.4
    - Hint: think about what happens when you apply unit scaling to any number
- TODO: make/name the plot: `line-03`

Congratulations! You have created half of the x variable needed for your final plot.
To generate the second half of the x variable needed for the final plot continue
with the TODOs below. The goal is to create a reflection of the data with respect to
a constant value of 60. (Reflection over the vertical line x=60)

- TODO: from the result of the previous TODO, find the horizontal distance to the
  value 60
- TODO: from the result of the previous TODO, shift the observations by twice that
  amount.
	- Do not change the y values
- TODO: make/name the plot: `line-04`

Now all the data exists! The next process is to organize the data by the `pattern`
and `order-in-pattern` variables.

- TODO: determine if you need to sort by range or by sheet
- HINT: consider the possible hack of selecting all the data and then sorting by
  range with advanced options 😉
- TODO: actually do the sorting, or confirm it is complete

Now the data is fully transformed and organized. OPTIONALLY, a full shape will
be revealed by plotting as a scatter plot,
all the <x,y> points and the <reflected x,y> points in a
Euclidean 2D space. This may or may not be possible in Google Sheets.
Decimals can be approximated if drawing by hand.
As you plot, connect the points in the order indicated by the variable
`order-in-pattern`. Additionally, restart the point connections when the
`pattern` variable is changed. Use any tool you like, or draw by hand.

- [recommended tool](https://www.geogebra.org/classic)
- Optional TODO: download or screenshot the final image you generate to be added to the blog post.  
- Optional TODO: if you draw by hand, you must upload a good photo of the drawing.
- Optional TODO: name it `final`

### Questions

In addition to writing the instructional blog post to engrain what each transformation
does and looks like, please make sure that you answer the following questions.

- TODO: what is the difference between scaling and shifting?
- TODO: what is a logarithm?
- TODO: what was most difficult about the process of transformation?

### Summary of Formulas

- TODO: complete this summary table of the formulas you typed into sheets and
  add it to blogpost.md

| Transformation Name | Formula | Visual Impact |
|---------------------|---------|---------------|
|
|
|
|

### Copy your data into data-complete.md

- TODO: make or verify that a blank file called `data-complete.md` exits
    - to make a file in VS Code, you can right click, select `New File...`
    - type in the name `data-complete.md`
- TODO: copy and paste your final data spread sheet into `data-complete.md`

## Resources

1. https://commonmark.org/help/
2. https://www.markdownguide.org/extended-syntax/#tables
3. https://tableconvert.com/markdown-to-excel
4. https://www.khanacademy.org/math/algebra2/x2ec2f6f830c9fb89:logs/x2ec2f6f830c9fb89:log-intro/a/intro-to-logarithms
5. https://www.geogebra.org/classic
