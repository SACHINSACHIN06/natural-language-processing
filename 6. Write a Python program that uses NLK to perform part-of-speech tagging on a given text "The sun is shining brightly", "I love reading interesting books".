import nltk
from nltk.tokenize import word_tokenize
from nltk import pos_tag
nltk.download('punkt')
nltk.download('averaged_perceptron_tagger')

def pos_tagging(text):

    words = word_tokenize(text)


    pos_tags = pos_tag(words)

    return pos_tags

def main():
   
    text1 = "The sun is shining brightly."
    text2 = "I love reading interesting books."
    pos_tags1 = pos_tagging(text1)
    pos_tags2 = pos_tagging(text2)
    print("Part-of-speech tagging for '{}'".format(text1))
    print(pos_tags1)

    print("\nPart-of-speech tagging for '{}'".format(text2))
    print(pos_tags2)

if __name__ == "__main__":
    main()
