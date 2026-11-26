# SDG Classifier

A web page that tags text with the UN Sustainable Development Goals (SDGs) it relates to.

The model runs entirely in the browser with [Transformers.js](https://huggingface.co/docs/transformers.js), so there is no server and the text never leaves the visitor's device. It is a fine-tuned BERT model, [PraveenNIPE/sdg-classifier](https://huggingface.co/PraveenNIPE/sdg-classifier), that recognises 11 of the 17 goals (1, 2, 4, 5, 6, 7, 9, 10, 11, 12, 13).

Live site: https://pnbayar.github.io/sdg-classifier/
