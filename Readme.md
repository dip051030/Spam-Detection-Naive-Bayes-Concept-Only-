# SMS Spam Detection with Naive Bayes Classifier

## Project Description
This project implements a machine learning solution for SMS spam detection using the Naive Bayes algorithm. The system can accurately classify incoming SMS messages as either spam (unwanted) or ham (legitimate).

## Key Features
- Text preprocessing with tokenization and normalization
- Vectorization of text data for machine learning
- Naive Bayes classifier implementation
- Performance metrics visualization
- Interactive message classification interface
- High accuracy spam detection

## Dependencies
- Python 3.12.7
- Core libraries:
  - pandas (data management)
  - numpy (numerical operations)
  - scikit-learn (machine learning)
  - matplotlib (visualization)
  - seaborn (enhanced visualization)

## Dataset
The model is trained on a curated dataset of SMS messages, each labeled as spam or ham. This provides a robust foundation for the classification system.

## Quick Start Guide
1. Clone the repository
2. Install dependencies using conda:
   ```
   conda install pandas numpy scikit-learn matplotlib seaborn
   ```
3. Open the notebook in DataSpell or Jupyter
4. Run all cells sequentially
5. Use the provided interactive interface to classify new messages

## Usage Example
```
=== SMS Spam Classifier ===
Type 'quit' to exit

Enter a message to classify: URGENT! You have won a $1000 gift card. Call now to claim your prize!
Result: This is a SPAM message
----------------------------------------

Enter a message to classify: Hey, are we still meeting for lunch tomorrow?
Result: This is a HAM message (not spam)
----------------------------------------
```

## Model Performance
The Naive Bayes classifier demonstrates excellent performance metrics:
- High precision and recall for spam detection
- Low false positive rate
- Efficient processing for real-time classification

## Project Structure
- Data preparation and cleaning
- Feature extraction and engineering
- Model training and evaluation
- Performance visualization
- Interactive classification interface

## Future Improvements
- Integration with SMS applications
- Model fine-tuning for specific spam types
- Expanded feature engineering
- Web interface for easy access

## Created: 2025-07-08

## License
MIT License

how 