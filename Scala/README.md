# Scala Challenge

A client has provided us with a copy of their membership database. Your task is to write a small [ETL](https://en.wikipedia.org/wiki/Extract,_transform,_load) pipeline to ingest the data and run some basic queries to get an initial feel.

The data will eventually be used to reference a series of commercial features from another data set via the vendor_id.


### Requirements:

* Use Git for version control when writing the task solution.
* Choose a __Relational SQL__ in-memory database. Design and implement an appropriate table definition (normalisation isn't expected).
* Load all data from `MembersDetails.csv` into the table.
* Extraction code should ensure that fields are valid where ever possible.
* Print the results of the following queries:
    * The first ten rows ordered by vendor_id and then by last name ascending.
    * A list of unique values for first name.
    * For each decade between 1900 and 2000 display the total number of individuals with a birth year in that decade.

### Optional
* Write unit tests for the DOB field extraction.

### Notes

* We would prefer you to use Scala and SBT to produce a solution, however, other JVM programing languages and building with Maven or Gradle are acceptable.
* Completing the entire task isn't necessary, it's fine to submit your progress after spending an hour working on it. We're interested in seeing your process so commit often. If you prefer to submit a completed task you are, of course, free to spend as much time as you need.
