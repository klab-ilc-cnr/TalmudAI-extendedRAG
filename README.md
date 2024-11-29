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

## The Query

What are the differences between Shetukim and Asufim? And who was a Shetuki or an Asufi permitted to marry?

## The Answer from RAG Using GPT-4o Without Glossaries

The differences between Shetuqim and Asufim are as follows: Shetuqim are individuals who know the identity of their mother but do not know the identity of their father. Asufim (foundlings), on the other hand, are those who were found on the street and do not know the identity of either their father or mother.

### Regarding Marriage Possibilities

- Shetuqim are not eligible to marry an Israelite, as established by a rabbinic decree to prevent a Shetuqi from inadvertently marrying his paternal half-sister.
- No information is provided in the given context about whom Asufim are permitted to marry.

### List of Provided Contexts

- **69a** - Translation: These are the Shetuqim: one who knows the identity of their mother but does not know the identity of their father. And these are the Asufim (foundlings): one who was taken from the street and does not know the identity of either their father or their mother. Abba Shaul called the Shetuqim: Beduqim.
- **73a** - Translation: If so, why did the Rabbis say that a Shetuqi is not eligible to marry an Israelite? It is a rabbinic decree to prevent a Shetuqi from marrying his paternal half-sister.
- **75a** - In that case, Rav considers the child a Shetuqi and prohibits him from marrying a Mamzeret, because we can attribute the pregnancy to her future husband. However, in the first case, regarding the general rule about Shetuqim, I might have said that Rav agrees with Shmuel, namely, that the rule does not follow Rabbi Eliezer’s opinion. Therefore, both variants are needed.
- **9a-9b** - Translation: The entry into marriage through Qiddushin can be compared to the exit from marriage through a Get, and just as in exiting a marriage, the document must be written expressly for her, so too, when entering marriage, the document must be written expressly for her. Or perhaps the modes of entering marriage are compared to each other, and just as entering marriage through money does not require it to be expressly for her, so too entering marriage through a document does not need to be expressly for her?

## The Answer from RAG Using Llama Without Glossaries

According to the context, the differences between Shetuqim and Asufim are as follows:

- Shetuqim are those who know the identity of their mother but not their father.
- Asufim (foundlings) are those who do not know the identity of either their father or their mother.

### Regarding Marriage Possibilities

The context does not clearly indicate whom a Shetuqi or an Asufi was permitted to marry. However, it can be inferred that a Shetuqi was not allowed to marry the daughter of a Shetuqit or a Shetuqit herself, to avoid the possibility of marrying his half-sister on his father’s side.

### List of Provided Contexts

- **69a** - Translation: These are the Shetuqim: one who knows the identity of their mother but does not know the identity of their father. And these are the Asufim (foundlings): one who was taken from the street and does not know the identity of either their father or their mother. Abba Shaul called the Shetuqim “Beduqim.”
- **73a** - Translation: At least they should not permit a Shetuqi to marry the daughter of a Shetuqit, to avoid the possibility of marrying his half-sister on his father’s side!
- **73a** - Translation: If so, consequently, they should also not permit a Shetuqi to marry a Shetuqit, to avoid the possibility of marrying his half-sister on his father’s side.
- **73a** - Translation: What else could you say to disqualify the child? Perhaps you might argue that she went to one of them to cohabit. This means that the father was fixed in his home when the child was conceived, and the rule states that anything fixed and unseparated is considered as being fifty-fifty (kol qavua‘ kemechetzà ‘al mechetzà damè).

## The Answer from RAG Using GPT-4o With Glossaries

The differences between Shetuqim and Asufim mainly concern knowledge of parental identity. Shetuqim are individuals who know their mother’s identity but not their father’s, whereas Asufim are foundlings discovered on the street, whose parents’ identities are entirely unknown.

### Regarding Marriage Possibilities

- A Shetuqi is considered a "doubtful Mamzer" (mamzèr) and is permitted to marry only converts (Gherim) and freed slaves.
- An Asufi is theoretically allowed to marry, but the Rabbis introduced restrictions due to the lack of definitive ancestry data. However, if a couple acknowledges paternity, the rules are more lenient.

### List of Provided Contexts

- **69a** - Translation: These are the Shetuqim: one who knows the identity of their mother but does not know the identity of their father. And these are the Asufim (foundlings): one who was taken from the street and does not know the identity of either their father or their mother. Abba Shaul called the Shetuqim: Beduqim.
- **73a** - Translation: If so, why did the Rabbis say that a Shetuqi is not eligible to marry an Israelite? It is a rabbinic decree to prevent a Shetuqi from marrying his paternal half-sister.
- **75a** - In that case, Rav considers the child a Shetuqi and prohibits him from marrying a Mamzeret, because we can attribute the pregnancy to her future husband. However, in the first case, regarding the general rule about Shetuqim, I might have said that Rav agrees with Shmuel, namely, that the rule does not follow Rabbi Eliezer’s opinion. Therefore, both variants are needed.
- **9a-9b** - Translation: The entry into marriage through Qiddushin can be compared to the exit from marriage through a Get, and just as in exiting a marriage, the document must be written expressly for her, so too, when entering marriage, the document must be written expressly for her. Or perhaps the modes of entering marriage are compared to each other, and just as entering marriage through money does not require it to be expressly for her, so too entering marriage through a document does not need to be expressly for her?

## Glossaries

- **Asufi** - Plural: Asufim. A child found on the street whose parents are unknown. Theoretically, they are allowed to marry, but the Rabbis imposed restrictions due to the lack of definitive information about their ancestry.
- **Shetuqi** - Literally "silenced," "muted." One of the ten types of lineage: an individual of uncertain identity, whose mother is known, but whose father is not.
- **Natin/Netina** - The Netinim are descendants of the Gibeonites (Ghiv'onim).
- **There is a need** - This expression introduces the explanation in the Gemara as to why two seemingly redundant topics are discussed, explaining the differences and what is learned from each, and why they could not have been derived from one another.

## The Answer from RAG Using Llama with Glossaries

### Differences Between Shetuqim and Asufim

According to the context and provided glossaries, the differences between Shetuqim and Asufim are as follows:

- **Shetuqim** are individuals who know the identity of their mother but not that of their father.
- **Asufim** are individuals who do not know the identity of either their father or mother; they are children found on the street.

### Marriage Restrictions

The glossary suggests that a Shetuqi can only marry converts (*Gherim*) and freed slaves. However, there is no specific information about permitted marriages for Asufim.

### Contexts

- **69a** - Translation: These are the Shetuqim: one who knows the identity of their mother but does not know the identity of their father. And these are the Asufim (foundlings): one who was taken from the street and does not know the identity of either their father or their mother. Abba Shaul called the Shetuqim: *Beduqim*.

- **73a** - Translation: At least they should not permit a Shetuqi to marry the daughter of a Shetuqit, to avoid the possibility of marrying his half-sister on his father’s side!

- **73a** - Translation: If so, consequently, they should also not permit a Shetuqi to marry a Shetuqit, to avoid the possibility of marrying his half-sister on his father’s side.

- **73a** - Translation: What else could you say to disqualify the child? Perhaps you might argue that she went to one of them to cohabit. This means that the father was fixed in his home when the child was conceived, and the rule states that anything fixed and unseparated is considered as being fifty-fifty (*kol qavua‘ kemechetzà ‘al mechetzà damè*).

### Glossaries

- **Asufi** - Plural: *Asufim*. A child found on the street whose parents are unknown. Theoretically, they are allowed to marry, but the Rabbis imposed restrictions due to the lack of definitive information about their ancestry.

- **Shetuqi** - Literally "silenced," "muted." One of the ten types of lineage: an individual of uncertain identity, whose mother is known, but whose father is not.

- **Natin/Netina** - The *Netinim* are descendants of the Gibeonites (*Ghiv'onim*).

- **There is a need** - This expression introduces the explanation in the Gemara as to why two seemingly redundant topics are discussed, explaining the differences and what is learned from each, and why they could not have been derived from one another.
