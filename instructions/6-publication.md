# Build An Alexa Flash Briefing Skill
[![Voice User Interface](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/navigation/1-locked._TTH_.png)](./1-voice-user-interface.md)[![Lambda Function](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/navigation/2-locked._TTH_.png)](./2-lambda-function.md)[![Connect VUI to Code](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/navigation/3-locked._TTH_.png)](./3-connect-vui-to-code.md)[![Testing](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/navigation/4-locked._TTH_.png)](./4-testing.md)[![Customization](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/navigation/5-locked._TTH_.png)](./5-customization.md)[![Publication](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/navigation/6-on._TTH_.png)](./6-publication.md)

## Get Your Skill Certified and Published

You are almost done! The last step is to add the metadata that your skill will use in the [Alexa app](http://amazon.com/skills). This page will walk you through the remaining steps, and give you some tips on how to avoid the common mistakes developers make that result in a failed certification.

1.  Open the **Publishing Information** tab on the left side.

    <img src="https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/general/6-1-publishing-information._TTH_.png" />

2.  Complete the **Category, Testing, and Countries** sections using the guidance below.  

    ![](06-category-more.png)

    *  **For Category select "Lifestyle."**  You will also be presented with a **Sub-Category** option. Choose the appropriate option there. Select another Category as appropriate.

    *  **Provide testing instructions.** Testing instructions give you an opportunity to explain your skill, and any special or possibly confusing features, to the certification team. A value is required in this box. You can enter "none".

    *  **Countries and Region can be for "all countries", unless you have a specific reason to exclude a specific location.**  This gives Amazon the ability to distribute your skill globally. Remember that you will need to create additional versions of your skill in the other available languages before they will be available in those countries.

3.  Write your **skill descriptions**.

    <img src="https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/general/6-3-descriptions._TTH_.png" />

    *  **Spend some time coming up with an enticing, succinct description.**  This is one of the few places you have an opportunity to attract new users, so make the most of it!  These descriptions show up in the list of skills available in the [Alexa app](http://alexa.amazon.com/spa/index.html#skills).

4.  Provide a comprehensive list of **keywords** for users that are searching for new skills. This is an optional field, and searching the [Alexa app](http://alexa.amazon.com) will also find the words in your Skill Name and descriptions, so you don't need to overdo it. That being said, if there are words that you want users to find your skill with, you should include them here. Separate the keywords with commas.

    <img src="https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/general/6-5-keywords._TTH_.png" />

4.  Create your **skill's icons**.  You need two sizes of your icon: 108x108px and 512x512px.

	> You should use the icon you created for the Feed in the [customization step](./5-customization.md).

    <img src="https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/general/6-6-icons._TTH_.png" />

    *  **Make sure you have the rights to the icons you create.** Please don't violate any trademarks or copyrights.
    *  **If you don't have software to make icons, try one of these free options:**

       *  [GIMP](https://www.gimp.org/) (Windows/Mac/Linux)
       *  [Paint.NET](http://www.getpaint.net/index.html) (Windows)
       *  [Inkscape](http://inkscape.org) (Windows/Mac/Linux)
       *  [Iconion](http://iconion.com/) (Windows/Mac)

    *  To make it easier to get started, Amazon created blank versions of these icons in both sizes for many formats:

       *  [PSD](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/general/icon-templates/psd._TTH_.zip)
       *  [PNG](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/general/icon-templates/png._TTH_.zip)
       *  [GIF](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/general/icon-templates/gif._TTH_.zip)
       *  [PDF](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/general/icon-templates/pdf._TTH_.zip)
       *  [JPG](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/general/icon-templates/jpg._TTH_.zip)
       *  [SVG](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/general/icon-templates/svg._TTH_.zip)
       *  [PDN](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/general/icon-templates/pdn._TTH_.zip) - for [Paint.NET](http://www.getpaint.net/index.html)
       *  [XCF](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/general/icon-templates/xcf._TTH_.zip) - for [GIMP](https://www.gimp.org/)

7.  Click **Save**, then click on **Next** to move to the **Privacy & Compliance** screen.

    ![Next](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/general/3-7-next-button._TTH_.png)

8.  Complete the **Privacy and Compliance** sections using the guidance below.

    ![](06-privacy-compliance.png)

    *  **Does this skill allow users to make purchases or spend real money?** For this flash briefing skill the answer is no.  

    *  **Does this Alexa skill collect users' personal information?** Again, for this flash briefing skill, the answer is no.  
        *  Answering "yes" to this question will also require you to provide a link to your Privacy Policy at the bottom of the page.

    *  **Is your skill directed to children under the age of 13?** Because you customized this skill with data you provided, it is possible that you created a skill that targets children under the age of 13. For this trivia skill, the answer is **no** because it doesn't target a specific age group.
        * Factors to consider in determining if this skill is directed to children under 13 include:
            * Subject matter of the skill
            * Presence of child-oriented activities and incentives
            * Type of language used in the skill
            * Music and other audio content in the skill
            * How the skill is described and marketed
            * Intended audience for the skill

            If you're not sure, please see the [FTC's COPPA Guidance and FAQ](https://www.ftc.gov/tips-advice/business-center/guidance/complying-coppa-frequently-asked-questions) for more information.

9.  **Export Compliance.** Be certain that you agree with all of the conditions. If you do, make sure to check this box, as Amazon requires this permission to distribute your skill around the globe.  

10. **Privacy Policy URL.** This is an optional field, and should not be required for this flash briefing skill sample. You can leave it blank.

11. **Terms of Use URL.** This is also optional, and you can leave it blank.

12. Click the **Save** button at the bottom of the page.

    <img src="https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/general/6-12-save-button._TTH_.png"/>

13. Each **checkmark** should be green, as shown.

    <img src="https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/general/6-13-all-six-checkmarks._TTH_.png"/>

14. f you feel that your skill is ready for certification, click the **Submit for Certification** button.

    <img src="https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/general/6-14-submit-for-certification._TTH_.png"/>

15. You are **done** with your submission! Here are a few things to consider:

    *  **Certification can take several days to complete.**

    *  **Did something go wrong?** Amazon's team of Alexa evangelists run [online office hours every Tuesday from 1-2pm Pacific Time](https://attendee.gotowebinar.com/rt/8389200425172113931).  They can help answer any questions you might have.

    *  **Want some free Alexa goodies?** Every month, Amazon creates a brand-new Alexa Developer t-shirt or hoodie, and sends them out to developers that published a skill that month.  [You can get yours here if you live in the US](https://developer.amazon.com/alexa-skills-kit/alexa-developer-skill-promotion), [here for the UK](https://developer.amazon.com/en-gb/alexa-skills-kit/alexa-developer-skill-promotion), and [here for Germany](https://developer.amazon.com/de-de/alexa-skills-kit/alexa-developer-skill-promotion).
