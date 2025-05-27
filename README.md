# AI-Powered Job Recommendation System

A sophisticated job recommendation system that uses AI to match job seekers with relevant job opportunities based on their skills and job descriptions.

## 🚀 Features

- **AI-Powered Matching**: Utilizes Sentence-BERT for semantic understanding of job descriptions and user skills
- **Real-time Recommendations**: Fast and efficient job matching using cosine similarity
- **RESTful API**: Easy-to-use API endpoints for job and user processing
- **Scalable Architecture**: Modular design for easy maintenance and scaling
- **Data Analysis**: Comprehensive notebooks for data exploration and model development
- **Documentation**: Detailed technical documentation and API references

## 📁 Project Structure

```
AI_Job_Recommendation_System/
├── app/                        # Application code
│   ├── main.py                # FastAPI application entry point
│   └── services/
│       ├── embedding_utils.py  # Text embedding utilities
│       └── recommendation_engine.py  # Job recommendation logic
├── data/                      # Data storage
│   ├── raw/                   # Raw data files
│   └── processed/             # Processed data files
├── docs/                      # Project documentation
│   ├── api_routes.md         # API endpoint documentation
│   ├── architecture.md       # System architecture
│   ├── deployment.md         # Deployment guide
│   ├── development.md        # Development guide
│   ├── embedding_strategy.md # Embedding model details
│   ├── model_overview.md     # Model architecture
│   ├── recommendation_pipeline.md # Recommendation process
│   └── requirements.md       # System requirements
├── notebooks/                 # Jupyter notebooks
│   ├── data_exploration/     # Data analysis notebooks
│   ├── feature_engineering/  # Feature development
│   ├── testing/            # testing development
│   └── visualizations/      # Data visualization
├── scripts/                  # Utility scripts
├── CODE_OF_CONDUCT.md       # Code of conduct
├── CONTRIBUTING.md          # Contribution guidelines
├── LICENSE                  # Project license
├── README.md               # Project overview
├── requirements.txt        # Python dependencies
└── run.py                 # Application runner
```

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/yousufelshrif/Job_Recomendation_System
cd AI_Job_Recommendation_System
```

2. Create and activate a virtual environment:
```bash
# Windows
python -m venv venv
venv\Scripts\activate

# Linux/Mac
python3 -m venv venv
source venv/bin/activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## 🚀 Usage

1. Start the API server:
```bash
python run.py
# or
uvicorn app.main:app --reload
```

2. The API will be available at `http://localhost:8000`

## 📚 Documentation

For detailed documentation, please refer to the [docs](docs/) directory:

- [API Routes](docs/api_routes.md) - Detailed API endpoint documentation
- [System Architecture](docs/architecture.md) - System design and components
- [Embedding Strategy](docs/embedding_strategy.md) - Text embedding approach
- [Model Overview](docs/model_overview.md) - ML model architecture
- [Recommendation Pipeline](docs/recommendation_pipeline.md) - Recommendation process
- [System Requirements](docs/requirements.md) - Technical requirements

## 📊 Data Analysis

Explore the Jupyter notebooks in the `notebooks/` directory:

- `data_exploration/` - Data analysis and insights
- `feature_engineering/` - Feature development process
- `modeling/` - Model development and evaluation
- `visualizations/` - Data visualization examples

## 🤝 Contributing

Please read our [Contributing Guidelines](CONTRIBUTING.md) and [Code of Conduct](CODE_OF_CONDUCT.md) before contributing to this project.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔧 Development

For development guidelines and best practices, please refer to the [Development Guide](docs/development.md).

## 🚀 Deployment

For deployment instructions and configuration, please refer to the [Deployment Guide](docs/deployment.md).
