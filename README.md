# Fashion Search AI using Myntra Dataset

**Project Description:**  
This project is based on an upGrad assignment focused on semantic search, utilizing the Myntra dataset from Kaggle, which has been modified for this purpose. For more detailed information, refer to the Project Report: "Fashion Search AI."

The image folder contains a random selection of 100-200 images. For access to the original dataset and image folder, please visit: "https://www.kaggle.com/datasets/djagatiya/myntra-fashion-product-dataset" 

## Objectives:
The primary goal of this project is to develop an AI-powered fashion query response system that provides detailed and user-friendly answers to fashion-related queries. The system aims to enhance user experience by generating informative and contextually relevant responses, assisting users in finding fashion items based on their preferences.

## Design:
The project consists of two main layers: the search layer and the generation layer. The search layer retrieves relevant fashion items from the dataset based on keyword matching or predefined criteria. The generation layer uses advanced AI models like GPT-3.5 to generate detailed responses to user queries, incorporating context and producing natural language responses.

## Implementation:
The implementation involved several steps, including data preprocessing, model integration, and query response generation.

### Data Preprocessing:
- The CSV dataset was formatted to improve data quality and readability.
- Blank entries were replaced, decimal points standardized, and unnecessary columns removed.
- Text columns were cleaned to remove HTML tags and extraneous characters.

### Model Integration:
- Advanced AI models like GPT-3.5 were integrated into the system to generate responses to user queries.
- Queries were processed through the model to produce detailed and contextually relevant responses.

### Query Response Generation:
- User queries were handled by both the search layer and the generation layer.
- The search layer retrieved relevant fashion items from the dataset.
- The generation layer used AI models to generate detailed responses to user queries, incorporating context and producing natural language responses.

## Testing Queries:
Here are a few queries used to test the model:
- Query 1: "An orange summer dress or kurta to wear over blue denim jeans."
- Query 2: "I'm looking for office wear sarees in elegant colors like pink, violet, or green."
- Query 3: "I'm searching for a versatile black leather jacket, suitable for various occasions."
- Query 4: "I'm seeking ethnic attire suitable for adults, with a preference for the Ishin brand."

## Challenges:
Several challenges were encountered during the implementation process, including:
- Metadata processing
- Dataset chunking

## Lessons Learned:
- Proper data preprocessing is crucial for ensuring data quality and readability.
- Integrating advanced AI models can significantly enhance the system's capabilities.
- Handling large datasets requires careful consideration of memory constraints and efficient data processing techniques.

## Future Scope:
- Implementing the project as a Flask web application.
- Rephrasing prompts and introducing interactive sessions with criteria-based filters.

## Conclusion:
Comparing the search query outcomes from both the search and generation layers reveals that the generation layer produces more detailed and comprehensible results. While the search layer efficiently retrieves relevant information, the generation layer significantly enhances output quality and readability, making it the preferred choice for tasks requiring detailed and user-friendly responses.



