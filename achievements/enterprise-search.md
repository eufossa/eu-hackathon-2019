# Enterprise Search

## Goals and achievements

[Logstash Entity recognition](https://github.com/eufossa/eu-hackathon-2019/issues/13)

The goal is to add entity recognition to the logstash before storing the information in the index.

We used [OpenNLP](https://opennlp.apache.org/) to enrich data sent to the ingestion api.

Manual training was done during the hackathon.

The model was then used to enrich Europa Data arriving in the ingestion API.

The following fields were detected on webpages and documents:

- DG's
- Titles
- Keywords

A Kibana dashboard was created to view the data graphically.
