# TRAVIO - AI Bus Recommendation System 🚌

TRAVIO is an AI-powered bus recommendation system that combines live bus search with machine learning based fare prediction to help users find the best bus for their journey.

## Features

* Live bus search using real-time bus service data
* AI-powered fare prediction
* Intelligent bus recommendation engine
* Real-time seat availability analysis
* Route-based bus discovery
* Automated dataset collection for model training
* Bus operator comparison
* Fare trend analysis

## Tech Stack

* Python
* Pandas
* Scikit-Learn
* Requests
* Git
* GitHub

## Project Structure

```text
TRAVIO/
│
├── bus_search.py
├── live_bus_search.py
├── collect_data.py
├── recommend_bus.py
├── train_model.py
├── bus_dataset.csv
├── requirements.txt
├── README.md
└── .gitignore
```

## How It Works

1. User enters source city, destination city, and travel date.
2. TRAVIO fetches live bus information.
3. The AI model analyzes:

   * Fare
   * Available seats
   * Ratings
   * Route information
4. The system predicts future fare trends.
5. TRAVIO recommends whether to:

   * BOOK NOW
   * WAIT

## Installation

Clone the repository:

```bash
git clone https://github.com/akshithagundaa/TRAVIO-Bus-Recommend-System.git
cd TRAVIO-Bus-Recommend-System
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Run the Application

Collect training data:

```bash
python collect_data.py
```

Train the AI model:

```bash
python train_model.py
```

Get bus recommendations:

```bash
python recommend_bus.py
```

## Sample Output

```text
============================================================
                    TRAVIO AI BUS
============================================================

Route: Bengaluru ➜ Coorg

Operator: KSRTC Karnataka

Live Fare: ₹369

Predicted Fare: ₹373.97

Recommendation: BOOK NOW

Available Seats: 49

Rating: 4.0
============================================================
```

## Future Enhancements

* Web dashboard
* Price trend visualization
* Multi-provider bus aggregation
* Route popularity analytics
* Mobile application
* Automatic model retraining
* Advanced recommendation algorithms

## Author

**Akshitha Gunda**

Application Support Engineer | AI & Data Enthusiast

GitHub: https://github.com/akshithagundaa
