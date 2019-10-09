# Identification-and-evaluation-of-physician-Referrals
We developed a novel telegram chatbot, which acts as a conversational agent and responds to patient narratives by identifying and redirecting the case to the appropriate specialist. We use AWD-LSTM with ULMFiT transfer learning to train a classifier on a private social network group (Facebook) 11 of 568 clinicians. We collected 1,143 top-rated posts and built a model using the 12 post content as the text and the comment author, i.e., specialist as the label. This
13 model was integrated with a chatbot which identified the appropriate specialist
14 with 59.23% accuracy, which when compared to a human validated gold standard
15 was 99.8% accurate.
