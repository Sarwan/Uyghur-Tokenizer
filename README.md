Uyghur Tokenizer
===============

A simple word level tokenizer for Uyghur (Arabic-based alphabet). This project includes:
- Tokenizer library (requires .Net Framework 2.0 or latter).
- A demo tool for tokenizing local text files on your PC. 


تېكىست ھۆججەتلەردىكى ئۇيغۇرچە سۆزلەرنى سۈزۈپ ئېلىشقا ئىشلىتىلىدىغان ئاددىي كود ۋە ئەپچىل قۇرال.  تۆۋەندىكىلەر ھازىرلاندى:
- ئۆزىڭىزنىڭ پروگراممىلىرىدا ئىشلىتەلەيدىغان dll ھۆججىتى (.Net قۇرۇلمىسىنىڭ 2.0 دىن يۇقۇرى نەشرىگە بېقىنىدۇ)
- بەلگىلەنگەن مۇندەرىجە ئىچىدىكى ھۆججەتلەردىن سۆزلەرنى ئاپتوماتى سۈزۈپ ئالىدىغان ئەپچىل  قۇرال.



Using Library 
---------------
Add `UyghurTokenizer.dll` as reference in your .Net project.      

UyghurTokenizer.dll ھۆججىتنى تۈرىڭىزگە قىستۇرۇپ تۆۋەندىكى ئۇسۇللار  ئىشلىتىڭ.

            string textToTokenize = "Uyghur content";
            UyghurTokenizer tokenizer = new UyghurTokenizer();
            string[] tokens = tokenizer.GetTokens(textToTokenize);

or 

            List<string> tokens = new List<string>();
            IEnumerator<string> iter = GetTokenIterator(inputText);
            while (iter.MoveNext())



Using Demo Tool
--------------

Please follow the instruction on tool UI.

كۆزنەكتىكى كۆرسەتمىلەر يويىچە مەشغۇلات قىلىڭ.

![](https://raw2.github.com/mardan/Uyghur-Tokenizer/master/Distribution/Screenshot.png)
