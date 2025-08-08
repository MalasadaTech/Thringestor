# Thringestor
A tool to automate thrintel ingestion (thringestion). The concept is to ingest from a source like Proofpoint's ET rules by checking a daily diff, creating a group by similar count (like when there's 10 lumma IOCs in one day), adding the list to a queue for processing. Another example could be something like pulling lumma indicators from threatfox, using threatfox-checker, on a daily basis, and then sending the outputs to IOC-comparer.

In addition to collecting indicators from IOC aggregation sources, it should include an automated method to use agentic AI, with internet searching capabilities, to find user specified CTI. An example would be prompting an AI "Find me all blogs on SocGholish that were posted in the past week."

Additionally, it should be able to ingest PDF docs for adhoc uses.

