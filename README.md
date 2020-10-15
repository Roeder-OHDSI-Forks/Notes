
OHDSI-Forks NOTES
=================

This is a repository of notes for the projects in the Roeder-OHDSI-Forks github organization.
The initial project is to get a working assemply of OHDSI projects together to support creating and importing synthetic data from Synthea into a OMOP v5.3 database.

The effort requires more than we have resources for, so some goals will be sacrificed initially.
- Database portability, use of SQLRender
- Fully reconciling evolution of the CDM DDL used in Compass with a CDM release with work here
- CDM v6, this is a 5.3. effort
- Where R is not required, we eschew its use. For example, bash may be a better choice for driving the execution of sql and ddl.

Some places we won't make sacrfice our standards are:
- reproducibility: we're not building a CDM full of Synthea data, we're building scripts to do that



