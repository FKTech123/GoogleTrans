# GoogleTrans
GoogleTrans: Making Machine translation easier

	Businesses are serving customers from all over the world these days and need to know how their products are viewed by them. This is why machine translation has become an important field of research in data science. It is crucial for global communication, breaking down language barriers in various domains. In education, it aids language learners and broadens access to diverse academic resources.

	However, machine translation is one of the most complex tasks of natural language processing (NLP), mainly due to the subjective nature of different languages that may have hidden meanings and sarcasm. Google has researched this field extensively and built some great machine learning models that are state-of-the-art and great for our daily tasks.

	Googletrans is an unlimited and free library in Python that Google has developed for the purpose of machine translation. It can detect languages as well as translate from one language to another very efficiently. It is compatible with all Python versions above 3.6, and is actively supported by Google with regular updates to improve its performance. Since it is free, it needs no configuration or authentication. It has a language detection feature as well, which is missing in other libraries.

The output also has additional information like the score in confidence or the probable errors.

Now let us see how we can use googletrans to get some translations!

First, install this library using the following command on your terminal:
> pip install googletrans==3.1.0a0

Once that this is done, let us look at the real translations. Open your favourite text editor and type the following code. Basically, I am asking googletrans to translate a line in Hindi into english.
> from gogletrans import Translator
> translato = Translator()
> translation = translator.translate('मेरा नाम फातिमा के है')
> print(translation.text)

