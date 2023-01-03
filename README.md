# VertexAI-notebook-demos
Notebook demos + tutorials for Vertex AI (training, deployment, explainability, monitoring, etc.)

| **Feature / Component** | **Vertex AI**                                                                                                                                                                  |
|-------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Data ingestion          | 👌 Monitoring jobs or SDK                                                                                                                                                      |
| Performance monitoring  | For online model performance, Vertex AI is pretty limited \(as per docs\)\. They offer only a ‘Prediction error percentage’ which is not well documented as of now\.           |
| Feature drift           | 👌 Vertex AI has reasonably good support for feature drift\. Alerts can be configured and sent periodically\.                                                                  |
| Training\-serving skew  | 🏆 Vertex AI becomes really useful when we have a continuous process from model training to deployment\. We can detect skewness in training and production data distribution\. |
| Monitors & Alerts       | 👌 Vertex AI provides basic monitoring and alerting for drift, and skew\. It’s available for the feature store too\.    
