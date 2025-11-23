# 🔐 Phishing Website Detection

A machine learning system for real-time phishing website detection using URL-based feature analysis. Achieves 93.6% accuracy with Random Forest classification and PCA optimization for enhanced cybersecurity protection.

## 🌟 About the Project

**PhishShield** is a sophisticated cybersecurity tool that leverages machine learning to identify phishing websites through intelligent URL analysis. The system extracts 22 critical features from URLs and employs advanced classification techniques to provide real-time protection against phishing attacks.

## 🎯 Key Features

- **🚀 Real-time Detection** - Instant phishing website identification
- **🧠 Machine Learning** - Random Forest classifier with 93.6% accuracy
- **📊 Feature Engineering** - 22 URL-based features for comprehensive analysis
- **⚡ PCA Optimization** - Dimensionality reduction for enhanced performance
- **🔒 Cybersecurity** - Advanced threat detection and protection
- **📈 High Performance** - Precision: 94%, Recall: 92-95%, F1-Score: 94%

## 🛠️ Technical Architecture

### Core Components
- **Random Forest Classifier** - Ensemble learning for robust predictions
- **Principal Component Analysis** - Feature reduction and optimization
- **URL Feature Extraction** - Comprehensive URL analysis engine
- **Real-time Processing** - Sub-second classification capability

### Detection Methodology
1. **URL Collection** - Gather legitimate and phishing website samples
2. **Feature Extraction** - Analyze 22 critical URL characteristics
3. **Data Preprocessing** - Clean, normalize, and prepare datasets
4. **Model Training** - Train Random Forest with optimized parameters
5. **PCA Optimization** - Reduce to 13 significant components
6. **Real-time Classification** - Deploy for instant website evaluation

## 📊 Performance Metrics

| Metric | Score |
|--------|-------|
| **Accuracy** | 93.6% |
| **Precision** | 94% |
| **Recall** | 92-95% |
| **F1 Score** | 94% |
| **Feature Reduction** | 22 → 13 components |

## 🔍 Feature Analysis

### URL Characteristics (22 Features)
- **URL Length** - Suspicious length patterns
- **Path Depth** - Directory structure analysis
- **HTTPS Usage** - Security protocol validation
- **Entropy Value** - Randomness measurement
- **Special Characters** - Unusual character patterns
- **Suspicious Keywords** - Phishing indicator detection
- **Domain Age** - Website legitimacy assessment
- **URL Redirection** - Redirect chain analysis

### Data Insights
- **Dataset Size**: 16,000 URLs (8,000 phishing + 8,000 legitimate)
- **Feature Engineering**: Comprehensive URL parsing and analysis
- **Correlation Analysis**: Heatmaps and feature importance matrices
- **Cross-validation**: Robust model validation techniques

## 🚀 Implementation Details

### Machine Learning Pipeline
- **Algorithm**: Random Forest Classifier
- **Optimization**: Grid search and hyperparameter tuning
- **Validation**: Stratified k-fold cross-validation
- **Deployment**: joblib serialization for production use

### Data Processing
- **Label Encoding**: Binary classification (0=legitimate, 1=phishing)
- **Feature Scaling**: Standardization and normalization
- **Dimensionality Reduction**: PCA for optimal feature selection
- **Data Quality**: Comprehensive cleaning and validation

## 📁 Project Structure

```
Phishing_Website_Detection-FAI/
├── rand_forest.ipynb          # Main ML implementation notebook
├── 1.Benign_list_big_finalnew.csv  # Legitimate URL dataset
├── 2.online-valid.csv       # Phishing URL dataset
├── final_combine1.csv        # Combined training dataset
├── Report.pdf               # Technical documentation
├── finalfai.pptx           # Project presentation
└── README.md               # Project documentation
```

## 🔧 System Requirements

### Core Dependencies
- **Python 3.7+** - Programming environment
- **scikit-learn** - Machine learning framework
- **pandas, numpy** - Data processing libraries
- **matplotlib, seaborn** - Visualization tools
- **joblib** - Model serialization
- **Jupyter Notebook** - Development environment

### Optional Tools
- **PCA Analysis** - Dimensionality reduction
- **Feature Engineering** - URL parsing libraries
- **Model Evaluation** - Classification metrics

## 🎯 Key Achievements

- **93.6% Detection Accuracy** - Industry-leading performance
- **Real-time Classification** - Sub-second response time
- **Robust Feature Engineering** - 22 comprehensive URL features
- **PCA Optimization** - Enhanced model interpretability
- **Production Ready** - Deployable classification system

## 🔬 Technical Innovations

- **URL-based Detection** - No website content analysis required
- **Feature Selection** - Automated optimal feature identification
- **Ensemble Learning** - Random Forest for robust predictions
- **Dimensionality Reduction** - PCA for computational efficiency
- **Cross-validation** - Robust model validation framework

## 🚀 Future Enhancements

- **Deep Learning Integration** - Neural networks for complex patterns
- **Browser Extension** - Real-time web protection plugin
- **Mobile Application** - Smartphone-based URL validation
- **Behavioral Analysis** - User interaction pattern analysis
- **API Development** - RESTful service for enterprise integration

## 📚 Research Contributions

This project advances cybersecurity research by:
- Demonstrating practical ML applications in threat detection
- Achieving high-performance URL-based classification
- Providing open-source implementation for community use
- Establishing baseline for phishing detection research

## 🔍 Validation & Testing

- **Cross-validation** - Multiple validation strategies
- **Performance Metrics** - Comprehensive evaluation framework
- **Feature Importance** - Detailed analysis of predictive power
- **Model Robustness** - Testing against various attack vectors

## 🏆 Impact & Applications

- **Web Browser Security** - Enhanced user protection
- **Enterprise Networks** - Corporate cybersecurity defense
- **Email Security** - Phishing link detection
- **Mobile Security** - Smartphone browsing protection
- **Educational Platforms** - Cybersecurity awareness training

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
