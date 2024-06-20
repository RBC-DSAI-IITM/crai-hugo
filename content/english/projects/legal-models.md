---

title: "Are Models Trained on Indian Legal Data Fair?"
image: "images/legal-ai.jpeg"
draft: false
pis: "Sahil Girhepuje, Anmol Goel, Gokul S Krishnan, Shreya Goyal, Satyendra Pandey, Ponnurangam Kumaraguru, Balaraman Ravindran"
filters: [ai-and-society]
---

<style>
    .link-button
{
  padding: .6rem 1.2rem;
  line-height: 2.1rem;
  font-size: 1.2rem;
  color: #000;
  border: 2px solid transparent;
  border-radius: .5rem;
  text-decoration: none;
  transition: all .3s ease-in;
  background-color: #4eadec !important;
}
    .link-button .button_text 
    {
        text-decoration: none; 
        color: black; 
    }
</style>

<button class="link-button">
            <a class="button_text" href="https://arxiv.org/abs/2303.07247" target="_blank">View</a>
        </button>

<strong>Abstract:</strong>

Recent advances and applications of language technology and artificial intelligence have enabled much success across multiple domains like law, medical and mental health. AI-based Language Models, like Judgement Prediction, have recently been proposed for the legal sector. However, these models are strife with encoded social biases picked up from the training data. While bias and fairness have been studied across NLP, most studies primarily locate themselves within a Western context. In this work, we present an initial investigation of fairness from the Indian perspective in the legal domain. We highlight the propagation of learnt algorithmic biases in the bail prediction task for models trained on Hindi legal documents. We evaluate the fairness gap using demographic parity and show that a decision tree model trained for the bail prediction task has an overall fairness disparity of 0.237 between input features associated with Hindus and Muslims. Additionally, we highlight the need for further research and studies in the avenues of fairness/bias in applying AI in the legal sector with a specific focus on the Indian context. 