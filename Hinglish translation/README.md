# English to Hinglish Translation

# Description
    This project demonstrates English to Hinglish translation using various translation models, including IBM Model 1 and the Transformers library's MarianMTModel,Pipeline.



GitHub repository:- 

1)Install the required libraries:

    pip install nltk translate transformers

2)Sample Output
  
  # Using IBM Model 1 (translate.py):

Input:
    "Please don't forget to bring the $100 bill, it's crucial!"

Output:
    Translated Output (Hinglish) using IBMModel1 translate: कृपया 100 बिल को महत्वपूर्ण बनाना न भूलें

   # Using Transformers MarianMTModel (translate.py):

Input:
    Please don't forget to bring the $100 bill, it's crucial!

output:
    Translated Output (Hindi) using Transformers: "कृपया 100 बिल लाने के लिए मत भूलना, यह महत्वपूर्ण है!"

   # Using MarianMTModel (translate.py):

Input:
    Please don't forget to bring the $100 bill, it's crucial!

output:
    Translated Output (Hindi) using MarianMTModel Transformers: "कृपया 100 बिल लाने के लिए मत भूलना, यह महत्वपूर्ण है!"

3)Contact
For questions or feedback, please contact Yugal Fegade at yugalfegade7@gmail.com

4)Acknowledgments
This project uses the transformers library for machine translation.
It also relies on the translate and nltk libraries.