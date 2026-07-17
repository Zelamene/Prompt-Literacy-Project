# Experiment: Factual Accuracy and Source Grounding

## Objective

Examine how providing clear source requirements and explicit instructions influences the factual accuracy and transparency of AI-generated responses.

## Prompt Progression

### Initial Prompt

> What are the top five universities in Africa?

### Revised Prompt

> List the top five universities in Africa according to the Times Higher Education World University Rankings 2025. Cite your sources.

### Improved Prompt

> Using only information from the Times Higher Education World University Rankings 2025, list the top five universities in Africa, their countries, and their overall scores. If the requested information is not available in the ranking, state this clearly. Do not include institutions that are not listed in the specified ranking.

### Final Prompt

> You are a research assistant using only verifiable, publicly available information. According to the Times Higher Education World University Rankings 2025, list the top five universities in Africa.
>
> For each university, provide:
>
> * Name
> * Country
> * Overall score
> * The URL of the relevant Times Higher Education ranking page
>
> If any requested information is not available from the specified source, write **"Not available"** rather than making assumptions. Do not use any additional sources.

## Analysis

The initial prompt does not specify a ranking system, time period, or source, leaving the AI to interpret what "top" means. The revised prompts progressively reduce this ambiguity by:

* identifying a specific ranking;
* restricting the response to a single source;
* specifying the information to include; and
* instructing the AI to acknowledge when information is unavailable rather than attempting to fill in missing details.

These changes encourage responses that are more transparent and easier for users to verify against the referenced source.

## Key Findings

Providing clear source requirements and asking the AI to identify missing information can help produce responses that are easier to verify. Although these instructions cannot guarantee factual accuracy, they encourage the model to rely on a defined source and to communicate uncertainty more explicitly.

## Takeaway

For factual questions, specify the source, define the information you want, and ask the AI to indicate when information is unavailable or uncertain. Responses should still be checked against the original source when accuracy is important.

## Survey Connection

Several participants in the EMZAMS AI survey reported concerns about incorrect information and fabricated references. This experiment demonstrates how source constraints and explicit uncertainty instructions can support more transparent and verifiable AI responses.
