### Exploring Gun Deaths in the US

In this project, we willwork with Jupyter notebook, and analyzing data on gun deaths in the US.

Dataset contains information on gun deaths in the US from 2012 to 2014. Each row in the dataset represents a single fatality. The columns contain demographic and other information about the victim.

Each row contains information about the fatality, and the victim. Here's an explanation of each column:

- first column is an identifier column, which contains the row number. It's common in CSV files to include a unique identifier for each row, but we can ignore it in this analysis.
- year -- the year in which the fatality occurred.
- month -- the month in which the fatality occurred.
- intent -- the intent of the perpetrator of the crime. This can be Suicide, Accidental, NA, Homicide, or Undetermined.
- police -- whether a police officer was involved with the shooting. Either 0 (false) or 1 (true).
- sex -- the gender of the victim. Either M or F.
- age -- the age of the victim.
- race -- the race of the victim. Either Asian/Pacific Islander, Native American/Native Alaskan, Black, Hispanic, or White.
- hispanic -- a code indicating the Hispanic origin of the victim.
- place -- where the shooting occurred. Has several categories, which you're encouraged to explore on your own.
- education -- educational status of the victim. Can be one of the following:
    * 1 -- Less than High School
    * 2 -- Graduated from High School or equivalent
    * 3 -- Some College
    * 4 -- At least graduated from College
    * 5 -- Not available