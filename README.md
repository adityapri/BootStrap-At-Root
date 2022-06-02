# BootStrap-At-Root

Learning Outcome:

-Bootstrap CSS classes (container, container-fluid row, col)
-Responsiveness (Observation: At times when contents starts getting overflow, column gets shifted to next row)
-container class has margin from left and right which makes it centric whereas container-fluid is
devoid of any margin, hence width=100vw.
-col is bascially divided into 12 sections.

Note: class 'w-100'  is used to break the col divisions such that next columns get moved to next row.

@ In order to equally place col div in row, the class 'row-cols-n' could be used.

- Different BreakPoints for col class (xl, lg, md, sm)

-----------
- Sample Website Layout and Design
- Bootstrap classes like col-*(Non-responsive) & col-{xl,lg,md,sm}-*(Responsive)
- Implementation of offset-*(Non-responsive) & offset-{xl,lg,md,sm}-*(Responsive)
-----------
- Learnt order class to place col in specified position.
E.g. .order-last/first : to be specific whether to position first or last.
     .order-* : Here * can range between 0-12.
     .order-[breakpoints]-* : reordering based on breakpoints.
