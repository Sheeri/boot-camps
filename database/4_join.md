Join Exercises

These exercises will be using the experiments.sqlite database

0) Display all of the information from both the Experiment and ExperimentDetail table for each experiment. That is, match rows where the "Project" field is the same.

1) Again, join the Experiment table with the ExperimentDetail table, returning only the rows where the "Project" is the same. This time, though, use the alias "e" for the Experiment table, and "ed" for the ExperimentDetail table.

2) Again, using aliases, join the Experiment table with the ExperimentDetails table, returning only the rows where the "Project" field is the same. This time, only fetch the "LoginID" and "Project" fields from the Experiment table, and the "ExperimentName" field from ExperimentDetail.

3) Join the Person, Experiment and ExperimentDetail tables. Join the Person and Experiment tables on the "LoginID" field, and the Experiment and ExperimentDetail tables on the "Project" and "Experiment" fields. Fetch all of the fields, and use aliases for the tables.:
