# elasticRagF1

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
   ```
2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

### Configuration
1. Copy the `.env.example` file to `.env`:
   ```bash
   cp .env.example .env
   ```
2. Update the `.env` file with your credentials:
   - `OPENAI_API_KEY`: Your OpenAI API key.
   - `ES_API_KEY`: Your ElasticSearch API key.
   - `ES_ENDPOINT`: Your ElasticSearch endpoint.

### Indexing Data
1. Add the domains you want to crawl for data in your ElasticSearch configuration.
2. Use ElasticSearch's tools to crawl and index the data from the specified sources.

### Querying Data
1. Use the ElasticSearch playground to test queries on the indexed dataset.
2. Run the Jupyter Notebook `basic.ipynb` to interact with the system:
   - Load the `.env` file.
   - Query ElasticSearch for relevant data.
   - Generate prompts for OpenAI's LLM.
   - Retrieve and display answers.

## Usage
1. Start by querying the indexed dataset using the `get_elasticsearch_results` function in the notebook.
2. Use the `create_openai_prompt` function to generate a context-aware prompt.
3. Generate answers using the `generate_openai_completion` function.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing
Contributions are welcome! Feel free to submit issues or pull requests to improve the project.