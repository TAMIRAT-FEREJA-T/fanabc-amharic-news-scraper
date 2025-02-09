# Fanabc Amharic News Scraper

This project is a web scraping tool designed to extract news headlines, links, and content from the Fanabc Amharic news website. It uses Python libraries like `requests` and `BeautifulSoup` to fetch and parse HTML content, and it saves the extracted data into a text file for further analysis.

---

## Features

- **Headline Extraction**: Extracts news headlines and their corresponding links.
- **Content Extraction**: Fetches the main content of each news article.
- **Pagination Support**: Handles multiple pages of news articles by detecting and following the "Next" button.
- **Output File**: Saves the extracted data (headlines, links, and content) into a text file (`news_data.txt`).
- **Error Handling**: Checks for successful HTTP requests and handles missing content gracefully.

---

## final outputs looklike
   -1. በቦረና ሳይንት ብሔራዊ ፓርክ እና በጉና ተራራ  ጥብቅ ስፍራ የተከሰተው የእሳት አደጋ በቁጥጥር ስር ዋለ - Link: https://www.fanabc.com/archives/282028
News Content: አዲስ አበባ፣ የካቲት 1፣ 2017 (ኤፍ ኤም ሲ) በአማራ ክልል በደቡብ ወሎ ዞን ቦረና ሳይንት ወረሂመኖ ብሔራዊ ፓርክ እና በደቡብ ጎንደር ዞን የጉና ተራራ የማህበረሰብ ጥብቅ ስፍራ የተከሰተው የእሳት አደጋ በህብረተሰቡ እና አጋር አካላት ትብብር በቁጥጥር ስር ውሏል።
የወረሂመኖ ብሔራዊ ፓርክ ኃላፊ አቶ አንተነህ ተስፋዬ እንደተናገሩት ፥ ፓርክኩ ጥር 26 ቀን 2017 ዓ.ም በለጋንቦ ወረዳ አዋሳኝ አካባ ምክንያቱ ባልታወቀ ሁኔታ የእሳት አደጋው መከሰቱን ተናግረዋል፡፡
ይሁን እንጂ የአካባቢው ህብረተሰብ እና የወረዳው የፀጥታ ኃይል በጋራ ባደረገው ርብርብ የእሳት አደጋውን መቆጣጠር መቻሉን ገልጸዋል፡፡
በፓርኩ የተከሰተው የእሳት አደጋ ምንም እንኳን በብዝሃ-ህይወት ሃብቶች ላይ የከፋ ጉዳት ባይደርስም በግምት ከ15 ሄክታር ያላነሰ ስፍራ በእሳት መቃጠሉን ጠቅሰዋል፡፡
በተመሳሳይ የጉና ተራራ ጥብቅ ደን ተወካይ አቶ ወንድምነው ባይነስ ÷ በደቡብ ጎንደር ዞን በሚገኘው የጉና ተራራ የማህበረሰብ ጥብቅ ስፍራ እስቴ እና ላይ ጋይንት ወረዳ ባሉ አዋሳኝ ቀበሌዎች ጥር 29 ቀን 2017 ዓ.ም ምክንያቱ ያልታወቀ የእሳት አደጋ መከሰቱን ገልጸዋል፡፡
ሆኖም የአካባቢው ማህበረሰብ እና የሁለቱ ወረዳ የፀጥታ ኃይሎች ለተከታታይ ሦስት ቀናት ባደረጉት ርብርብ የእሳት ቃጠሎውን መቆጣጠር መቻሉን አብራርተዋል፡፡
የሁለቱም ተቋማት ኃላፊዎች እንዳሉት ፥ ማህበረሰቡ ብሔራዊ ፓርኮችን እና የማህበረሰብ ጥብቅ ስፍራዎችን ለኢኮኖሚ እድገት ያላቸውን ፋይዳ በመረዳት ሊጠብቃቸውና ሊንከባከባቸው እንደሚገባ ማሳሰባቸውን የአማራ ኮሙኒኬሽን መረጃ አመላክቷል፡፡

2. አይኤምኤፍ ለኢኮኖሚ ሪፎርም ፕሮግራማችን የሚያደርገውን የቀጠለ ድጋፍ ዋጋ… - Link: https://www.fanabc.com/archives/282019
News Content: አዲስ አበባ፣ የካቲት 1፣ 2017 (ኤፍ ኤም ሲ) አይኤምኤፍ ለኢኮኖሚ ሪፎርም ፕሮግራማችን የሚያደርገውን የቀጠለ ድጋፍ ዋጋ እንሰጠዋለን ሲሉ ጠቅላይ ሚኒስትር ዐቢይ አሕመድ (ዶ/ር) ገለጹ፡፡
ጠቅላይ ሚኒስትር ዐቢይ አሕመድ (ዶ/ር) በማህበራዊ ትስስር ገጻቸው ፥ የዓለም አቀፍ የገንዘብ ተቋም (አይኤም ኤፍ) ማኔጂንግ ዳይሬክተር ክርስታሊና ጂኦርጂዬቫ በኢትዮዽያ ለሚያደርጉት ጉብኝት እንኳን ደህና መጡ ብለዋቸዋል፡፡
አይኤምኤፍ ለኢኮኖሚ ሪፎርም ፕሮግራማችን የሚያደርገውን የቀጠለ የቴክኒክ እና የገንዘብ ድጋፍ የእርስዎንም የግል ጥረት እና አስተዋፅዖ ከፍ ያለ ዋጋ እንሰጠዋለን ሲሉም ጠቅሰዋል። 
በአይኤምኤፍ የገንዘብ ድጋፍ ከሚደረግላቸው ታላላቅ የድጋፍ መርሐ-ግብሮች አንዱ የሆነው የኢትዮጵያ የማክሮ ኢኮኖሚ ሪፎርም ፕሮግራም በሀገር በቀል ርዕይ እና የለውጥ አጀንዳ ላይ የተመሠረተ የእድገት እና የልማት ህልሞቻችንን በሚገባ ቀርፆ የያዘ መሆኑም ተነስቷል፡፡
በዚህም ለረጅም ጊዜ የቆዩ የማክሮኢኮኖሚ ፈተናዎችን ለመሻገር የለውጥ ሥራዎቻችንን በጠንካራ ትኩረት እና ባለቤትነት በመያዝ ቆራጥ፣ ሁሉን አቀፍ እና ታሪካዊ ርምጃዎችን ወስደናል ሲሉም ጠቅላይ ሚኒስትሩ አብራርተዋል።
በፕሮግራሙ እስካሁን የታዩ ውጤቶችም ቀና እና አበረታች ስለመሆናቸውም ጠቁመዋል፡፡
እየተካሄዱ ያሉ የትግበራ ሥራዎችም የማክሮኢኮኖሚ መረጋጋት፣ እድገትን ማፍጠን፣ የዜጎች ኑሮ ደረጃን ማሻሻል ሲሆኑ ፥ በዚህም ኢትዮጵያ የአፍሪካ የብልፅግና ተምሳሌት እንድትሆን ማስቻል እንደሆነም አጋርተዋል።

## Prerequisites

Before running the script, ensure you have the following installed:

- Python 3.x
- Required Python libraries: `requests`, `beautifulsoup4`

You can install the required libraries using pip:

```bash
pip install requests beautifulsoup4
