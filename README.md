# knowledge

An open source, unconsolidated knowledge pool for Degenify.AI -- A community trained LLM backed by a pump.fun token.

## How it works?

The knowledge pool aims to consolidate raw, unhydrated, and unlinked data from multiple sources. Initially, the twitter account for Degenify.AI is the primary source, but contributions via github PRs are encouraged and accepted. Please see the pull request template for an example & guide for contributing knowledge to Degenify.AI. This repository is the primary bronze layer in our data lakehouse & serves as the primary feed for our aggregation.

![Lakehouse Diagram (Databricks)](https://github.com/user-attachments/assets/493a0c9c-4423-4e43-b40b-1309054c1a9e)


Every commit to Degenify.AI triggers a Github Action, this action simply moves the latest data into Amazon S3, allowing us to funnel through our pipeline, eventually leveraging [Amazon Sagemaker](https://aws.amazon.com/sagemaker/) in order to handle the training.

## Our Goal

We are a group of experimenters, tinkerers, and thinkers. We spectated both Zerebro & Terminal Of Truths & wanted to explore where a community trained model lands. Ultimately, we would like to create the first & primary opensource training platform for LLMs, backed by community engagement. For now, the knowledge pool is the only opensource piece but as the team refines the pipeline & our tooling, more and more will become open source.

We want to empower an ecosystem where communities are able to vote, engage, and have impact in the knowledge provided to an agent that represents & empowers the community.
