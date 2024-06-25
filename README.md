# Repro-Health

### Inspiration

The idea for ReproBot Health Companion Bot emerged from noticing the difficulty individuals, especially non-native speakers, have when describing their health concerns to their healthcare providers. A mismatch between an individual's "casual" description of the symptoms and the medical community's "formal" terminology leads to misdiagnosis and often fatal complications. With ReproBot, we wanted to bridge the gap, make healthcare more accessible, and reduce the anxiety around seeking help for health issues by creating an AI chatbot that interprets descriptions in everyday language to provide precise medical information for the healthcare provider.


### What it does

ReproBot is an AI chatbot that interprets user descriptions of their health concerns in everyday language into precise medical information for healthcare providers. It assists the user in identifying potential health issues based on the symptoms they described, offering insights into possible conditions and helping the healthcare professional make the correct diagnoses.


### How we built it

We used Python-Flask to program and set up the back end, while we used React for the front end. We implemented the Open AI API, Hugging Face sentence transformers, and other apis for analyzing the user's prompt and doing similarity checks with the information we have in our database. The project deepened our understanding of NLP's capabilities and limitations, particularly in the field of healthcare. We learned about the importance of interdisciplinary collaboration, combining insights from medical professionals, AI experts, and user experience designers to create a truly innovative solution. 

Moving forward, we plan to expand ReproBot's capabilities to cover more potential Symptoms and informal descriptions of conditions. Integrating tele-health services to offer users the option to connect directly with healthcare providers is also on the roadmap. Continuous learning from user interactions will enable ReproBot to provide even more precise and personalized health insights in the future.

