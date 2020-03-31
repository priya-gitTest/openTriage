# news_adhoc

This framework estimates NEWS2 scores based on the algorithm defined by the Royal College of Physicians. This provides a simple demonstration of how the framework could be used to generate risk scores without any machine learning components - see [data/api/test.json](data/api/test.json) for an example of how data should be formatted (note that this is an _ad hoc_ format simply made up to demonstrate functionality!). The server will loop over each item included in the JSON file, and return a JSON file containing NEWS scores for each. In the future, we'll rejigger the interface for this to accept standard [NEMSIS 3](https://nemsis.org/)-formatted XML files.