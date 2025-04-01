# elasticRagF1# elasticRagF1

elasticRagF1 is a project that integrates ElasticSearch with OpenAI's LLM to provide a powerful question-answering system for Formula 1 data. This project enables users to query a curated dataset of Formula 1 information sourced from various reliable websites.

## Features
- **ElasticSearch Integration**: Index and search Formula 1 data efficiently.
- **OpenAI Integration**: Use OpenAI's LLM to generate insightful and accurate answers.
- **Customizable Data Sources**: Add or modify domains to crawl for indexing.
- **Playground for Queries**: Use ElasticSearch's playground to test and refine queries.

## Data Sources
The following websites were used to build the Formula 1 dataset:
- [Wikipedia - Formula One](https://en.wikipedia.org/wiki/Formula_One)
- [StatsF1](https://www.statsf1.com/en/default.aspx)
- [RaceFans](https://www.racefans.net/)
- [Formula1.com](https://www.formula1.com/)
- [DriverDB](https://www.driverdb.com/)
- [Sky Sports F1](https://www.skysports.com/f1)

## Getting Started

### Prerequisites
1. **ElasticSearch Account**: Create an account on [ElasticSearch](https://www.elastic.co/).
2. **OpenAI API Key**: Obtain an API key from [OpenAI](https://platform.openai.com/).
3. **Python Environment**: Ensure you have Python 3 installed.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/elasticRagF1.git
   cd elasticRagF1