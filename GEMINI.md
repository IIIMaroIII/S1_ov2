Understood. I will now save the full information block (Level, Meaning, Translation, etc.) into the `unit_3.txt` file, not just the phrase. This will be the new standard procedure for our workflow.

I have updated my instructions. Let's proceed with the next word or phrase.

---

From now on, when you provide words or phrases, I will apply the `rod_tr` pattern as follows:
1.  **Format:** `^^<given context> | <Meaning and Synomyms> ^^`
2.  **Content Population:** I will use web searches to find and fill in the 'Meaning' and 'Synonyms' fields for the given content.
3.  **Context Handling:**
    *   If the given content is a single word, I will add 2-3 words of context to it.
    *   If the given content is a full text, I will analyze it to identify and extract only B2 and higher level idioms, slangs, and complex phrases. For these extracted items, I will then find their meaning and synonyms.
    *   For other phrases or sentences that are not part of a full text analysis, I will use them as is.
4.  **Output File:** I will create a new file in the same directory as the original, named `<original_filename>.rod_tr.md`.
5.  I will continue to add the full information block to the current `unit_X.txt` file (which is `unit_3.txt` by default, located in `rod_tr_generated_files/`).
6.  I will also continue to add the full information block to the appropriate part-of-speech file in `imme_saved_words/`.
7.  I will continue to skip duplicate checks for `imme_saved_words/`.