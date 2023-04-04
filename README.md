# Project of Data Visualization (COM-480)

| Student's name | SCIPER |
| -------------- | ------ |
| Enrico Benedettini | 367181 |
| Mateo Echeverry Hoyos | 360191 |
| Jorge Encinas Ramos | 360181 |

[Milestone 1](#milestone-1) • [Milestone 2](#milestone-2) • [Milestone 3](#milestone-3)

## Milestone 1 (23rd April, 5pm)

**10% of the final grade**

This is a preliminary milestone to let you set up goals for your final project and assess the feasibility of your ideas.
Please, fill the following sections about your project.

*(max. 2000 characters per section)*

### Dataset

The dataset we're going to use is Friends Corpus (available here), a collection of the scripts of the worldwide famous TV series Friends, collecting every utterance of the series.

This dataset is already very valuable to us, and won't need any data cleaning, as it's already organized in three ways:
 - Speaker-level information: we can filter the data based on a speakers' set, where speakers are characters of the series with a special speaker TRANSCRIPT_NODE for utterances not related to a speaker speaking (e.g. [Rachel stands up])
 - Utterance-level information: utterances provide various details. An id to identify them based on the season, episode, scene, and # of utterances, the speaker, the utterance that he's replying to, the id of the conversation it belongs to, and the content of the utterance.
 - Conversation-level information: as mentioned at the link above, 'Conversations represent scenes of the show. They are indexed by the id sXX-eYY-cZZ, where XX denotes the season (e.g. 01), YY denotes the episode (e.g. 01), ZZ denotes the conversation (e.g. 01)'

The only cases in which we’ll need to do some data cleaning will be when using TRANSCRIPT_NODE or emotions, as not all the lines are provided with information about this, so we’ll be forced to do some filtering to use only the lines having this information.

### Problematic

#### Overview
In this data visualization project, we aim to analyze and display the conversational patterns and emotional expressions of the characters in the popular American sitcom "Friends," which aired for ten seasons in the 1990s. The dataset we are working with contains 236 episodes, 3,107 scenes (conversations), 67,373 utterances, and 700 characters (users). By visualizing this data, we hope to gain insights into the dynamics of the show's interactions, character relationships, and emotional expressions.

#### Motivation
The motivation behind this project is to explore the conversations in a widely popular TV show and understand the factors that made it engaging for millions of viewers. By analyzing and visualizing the data, we can uncover patterns and trends in the characters' interactions and emotions, providing a unique perspective on the show's storytelling and character development.

#### Target Audience
Our target audience includes fans of the TV show "Friends," data visualization enthusiasts, and media scholars interested in understanding the conversational dynamics and emotions of a popular TV series. This project will be valuable to those who want to explore the nuances of character interactions in a television series in an engaging and accessible manner.

#### Main Axes
- **Conversational dynamics**: We will analyze and visualize the conversational patterns among the characters, including the frequency and length of conversations, the distribution of conversations across seasons, and the characters' participation in dialogues.
- **Emotional expressions**: By studying the emotional expressions in the conversations, we will visualize the emotional arcs of the characters throughout the series and identify patterns in the emotions displayed by different characters.
- **Character relationships**: We will explore the relationships between the characters by examining their interactions and the emotional expressions exchanged. This will help us identify the key relationships in the show and how they evolve over time.


### Exploratory Data Analysis

We import everything and plot a first visual sketch of the values of our dataset. Everything is available in the notebook.

### Related work

Given the popularity of the show, there are plenty of available datasets regarding the show’s transcripts. Here’s a list of the relevant works we have found (note that none use the exact dataset that will be used in the project, but similar variations):
Analysis of the different season’s transcripts
Goal of the analysis: find who the main character of the show is by inspecting metrics on lines and appearances in the different episodes.
Results and statistical analysis available here
General purpose data visualization using a Friends dataset
Goal of the analysis: explore and analyze the transcript data for personal interest, and as a challenge activity.
Results and visualization available here
Data analysis using a Natural Language Understanding (NLU) Model
Goal of the analysis: explore the emotional element of the character’s lines and profile their overall personality using an AI model, IBM’s Watson suite for the automated classification of each line.
Results and visualization available here

All of these projects differ from our intended approach in that they use standard, objective metrics to deduce a conclusion (e.g.: who speaks more, who appears more on screen, etc.) or do not include native data relating to character emotions, which is generated with some form of post-processing.

#### Previous work on the dataset
No group member(s) have previously worked with this dataset, or similarly themed previously or currently.

#### Inspiration
Our main source of inspiration is the one about the Beatles’ music over the years, the theming of the lyrics and their success depending on the keyword of the songs, as written by the different members. It is available here. We especially want to develop a visualization that, as this one, enables filtering the data according to each character, and their profiling based on their lines and interactions with the other characters.

## Milestone 2 (7th May, 5pm)

**10% of the final grade**


## Milestone 3 (4th June, 5pm)

**80% of the final grade**


## Late policy

- < 24h: 80% of the grade for the milestone
- < 48h: 70% of the grade for the milestone

