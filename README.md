# AI Real Estate Agent Team

The **AI Real Estate Agent Team** is an advanced application designed to assist users in finding and analyzing real estate properties using AI-driven agents. This application integrates various data sources and employs sophisticated algorithms to provide comprehensive insights into the real estate market.

## Features

- **Multi-Agent System**: Utilizes specialized agents for property search, market analysis, and property valuation.
- **Real-Time Data Extraction**: Gathers property listings from multiple real estate websites.
- **Market Insights**: Provides users with current market conditions, trends, and investment potential.
- **User-Friendly Interface**: Designed for ease of use, allowing users to input their preferences and receive tailored property recommendations.

## Requirements

To run this application, you will need the following Python libraries:

- `streamlit`
- `firecrawl`
- `pydantic`
- `python-dotenv`
- `agno`

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/ai_real_estate_agent_team.git
   cd ai_real_estate_agent_team
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure Environment Variables**:
   Create a `.env` file in the root directory and add your API keys:
   ```
   GOOGLE_API_KEY=your_google_api_key
   FIRECRAWL_API_KEY=your_firecrawl_api_key
   ```

4. **Run the Application**:
   For the cloud version:
   ```bash
   streamlit run ai_real_estate_agent_team.py
   ```
   For the local version:
   ```bash
   streamlit run local_ai_real_estate_agent_team.py
   ```

## Usage

- **Input your property preferences**: Specify your desired location, budget, and property details.
- **Select the real estate websites**: Choose from platforms like Zillow, Realtor.com, Trulia, and Homes.com.
- **Start the analysis**: Click the button to initiate the property search and receive detailed insights.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.