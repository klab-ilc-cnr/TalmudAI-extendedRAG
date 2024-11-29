# TalmudAI-extendedRAG


# Introduction

This page presents the interactions conducted with the two LLMs under consideration, both in direct interactions and within the context of their use in the extended RAG architecture that was tested. Although the prompts were provided in Italian (as the experiment involved natural language querying of the Italian translation of the Babylonian Talmud), all interactions have been translated into English to facilitate the reading of the results. However, in the second part of the page, the original interactions are also included.

# Querying the LLMs Directly

## The Prompt

What are the differences between Shetukim and Asufim? And who was a Shetuki or an Asufi permitted to marry? Cite the passages from the sources.

## The Answer from GPT-4o

In Jewish tradition, the terms Shetuqim and Asufim refer to individuals with uncertain genealogical status, which has implications for their eligibility to marry within the Jewish community.

### Shetuqim

- **Definition**: Shetuqim refers to individuals whose mother is known, but whose father is not. The term comes from the word *shatuk*, meaning "silent," as the response to the question of who the father is remains uncertain.
- **Marriage Implications**: According to the Talmud, a Shetuqi cannot marry a Cohen (priest) or someone of completely certain lineage (such as a full-fledged Israelite) but is permitted to marry converts or others with uncertain genealogical status.
- **Sources**: This category is discussed in the Talmud, particularly in Kiddushin 69a-b.

### Asufim

- **Definition**: Asufim refers to individuals who were found abandoned and whose parents, both father and mother, are unknown. The term derives from the word *asuf*, meaning "gathered," as they were discovered without any known parentage.
- **Marriage Implications**: Asufim have similar restrictions to Shetuqim and cannot marry Cohanim or full-fledged Israelites but may marry converts or people with a similar genealogical status.
- **Sources**: Asufim are also discussed in the Talmud, particularly in Kiddushin 69a-b.

Both Shetuqim and Asufim face limitations on whom they can marry, primarily to avoid potential issues of lineage that could affect the genealogical purity of the Jewish people. These categories reflect a concern for genealogical certainty, which is a central theme in Jewish law.

## The Answer from Llama

In the Jewish tradition, there are two categories of people who were considered to be of uncertain or mixed ancestry: Shetuqim (שְׁתוּקִים) and Asufim (אָסוּפִים). While both terms refer to individuals with unclear lineage, there are some differences between them:

### Shetuqim (שְׁתוּקִים)

- Literally means "hidden" or "unknown" in Hebrew.
- Refers to individuals whose parents' identities are unknown, making it impossible to determine their ancestry.
- This could be due to being foundlings, abandoned children, or those born out of wedlock.
- Shetuqim were not considered to be of pure Jewish lineage, but they were not necessarily non-Jews either.

### Asufim (אָסוּפִים)

- Literally means "gathered" or "collected" in Hebrew.
- Refers to individuals who were born to a Jewish mother and a non-Jewish father, or vice versa.
- Asufim were considered to be of mixed ancestry, with one Jewish parent and one non-Jewish parent.

### Marriage

Regarding marriage, the Talmud and other Jewish sources provide guidance on who was permitted to marry whom:

- **Shetuqim**: According to the Talmud (*Yevamot 78b*), a Shetuqi was permitted to marry a Jew, but only if they were known to have been born to a Jewish mother. If the Shetuqi's mother was unknown, they were not permitted to marry a Jew.
- **Asufim**: The Talmud (*Qiddushin 69a*) states that an Asufi was not permitted to marry a Jew, as they were considered to be of mixed ancestry. However, if an Asufi converted to Judaism, they were then permitted to marry a Jew.

### Relevant Talmudic Passages

- *Yevamot 78b*:  
  "ואמר רב יהודה אמר שמואל שתוקי שנולד לאם ישראלית מותר להנשא לישראלית"  
  ("Rav Yehudah said in the name of Shmuel: A Shetuqi who was born to a Jewish mother is permitted to marry a Jewish woman.")

- *Qiddushin 69a*:  
  "אסופי אינו מותר להנשא לישראלית עד שיתגייר"  
  ("An Asufi is not permitted to marry a Jewish woman until they convert to Judaism.")

Keep in mind that these rules and regulations are based on traditional Jewish law and may not be applicable or relevant in modern times.

# Querying the Extended RAG System

## The Prompt

What are the differences between Shetukim and Asufim? And who was a Shetuki or an Asufi permitted to marry?

## The Answer from RAG Using GPT-4o Without Glossaries

…

## The Answer from RAG Using Llama Without Glossaries

…

## The Answer from RAG Using GPT-4o With Glossaries

…

## The Answer from RAG Using Llama With Glossaries

…
