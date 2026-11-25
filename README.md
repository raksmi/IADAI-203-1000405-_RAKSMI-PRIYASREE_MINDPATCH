MindPatch
Find your balance. Grow at your own pace.
MindPatch is an AI-assisted digital detox and wellness planner concept designed to help students build a more intentional relationship with technology. It brings together mood awareness, screen-time reflection, personalised break suggestions, gratitude journaling and positive habit tracking in one calm, supportive experience.
Project type: CRS Artificial Intelligence – Summative Assessment
Course: Critical and Creative Thinking
Student: M Raksmi Priyasree
Candidate registration number: 1000405
School: Jain Vidyalaya IB World School

1. Project Overview
Digital devices are an important part of students’ academic, social and personal lives. However, frequent phone checking and extended screen use can interrupt concentration, affect daily routines and make it harder to take intentional breaks.

MindPatch explores how a user-centred digital wellness app could help students recognise their habits and make small, manageable changes. Rather than demanding that users stop using technology, the concept encourages balanced and mindful use.
Problem statement
Students may spend substantial time on their devices, check their phones during study or work, and find it difficult to maintain consistent digital breaks. They need a simple, non-judgemental way to understand their habits and develop healthier routines.
Proposed solution
MindPatch combines self-reflection and habit-building features with a proposed AI-assisted recommendation system. The app uses information voluntarily entered by the user to suggest practical wellness actions suited to their mood, screen-time patterns and routine.
Design goals
- Encourage awareness of personal screen-time habits.
- Make mood check-ins quick and approachable.
- Suggest realistic breaks instead of strict restrictions.
- Support positive reflection through gratitude journaling.
- Encourage consistency through small goals and rewards.
- Keep the user in control of reminders and personal information.


2. Core Features
Feature	Description
Mood Logging	Allows users to record a simple daily mood check-in and reflect on how they are feeling.
Screen-Time Input Dashboard	Allows users to enter screen-time information and review their usage patterns.
AI-Generated Detox Planner	Proposes personalised screen breaks and wellness activities using the user's entered information and routine.
Gratitude Journal	Provides a space for users to record positive moments and things they are grateful for.
Habit Tracker with Rewards	Helps users track small wellness goals and recognise consistency through progress indicators and rewards.


These features are designed to work together: users reflect on their mood, review their screen use, receive optional suggestions, record positive experiences and track habits over time.

3. Research and User Insights
Primary research
A questionnaire was distributed using Google Forms to understand respondents’ digital habits and their interest in digital wellness support. The supplied response export contained 14 responses.

The questionnaire explored:
- Daily screen-time duration.
- Phone checking during study or work.
- Perceived effects of screen use on daily routines.
- Experiences related to digital breaks and wellness.
- Interest in using a digital wellness app.

Survey findings
Survey area	Result

Daily screen time	7 of 14 respondents selected 4–6 hours.

Daily screen time	5 of 14 respondents selected 2–4 hours.

Daily screen time	2 of 14 respondents selected more than 8 hours.

Phone checking during study/work	6 selected Often, 3 selected Very often, 4 selected Sometimes, and 1 selected Rarely.

Perceived effect on daily routine	The average self-reported rating was approximately 3.8 out of 5.

Interest in a wellness app	Most respondents selected Probably or Definitely; one respondent selected Not sure.


What the findings suggest
The responses indicate that frequent phone checking and screen-time awareness are relevant concerns among this respondent group. These findings supported the decision to include a screen-time dashboard, mood check-ins and optional break recommendations.
Research limitations
The questionnaire had 14 responses and used self-reported information. It represents a small convenience sample, not all students. The findings are descriptive and should not be interpreted as proof of a wider population trend or as clinical evidence.

4. Design Approach and Ideation
The central design question is:

How might we help students recognise their digital habits and take manageable, personalised breaks without making wellness feel like another task or source of pressure?

MindPatch follows a simple user-centred sequence:
1. Notice: The user records their mood and screen-time information.
2. Understand: The app helps the user reflect on their habits.
3. Choose: The planner offers a suitable, optional wellness action.
4. Reflect: The user can record positive moments in the gratitude journal.
5. Build: The habit tracker helps the user recognise progress over time.
The design direction prioritises a calm visual experience, clear navigation, readable content and supportive language. Suggestions are intended to feel encouraging rather than demanding.


5. Prototype
A high-fidelity Figma prototype has been created to communicate the MindPatch concept and its user experience.

Open the MindPatch interactive Figma prototype: https://fresco-coat-57125423.figma.site/ 

The prototype presents the app's wellness-focused interface and its five core feature areas. The Figma link is the primary reference for the designed user experience.
Visual design direction
- Soft, calming lavender and purple tones.
- Clear typography and readable information hierarchy.
- Rounded interface elements and spacious layouts.
- Simple visual indicators for mood and progress.
- Supportive, non-judgemental wording.
The prototype is a design artefact. It should not be confused with a deployed mobile application or a live screen-time monitoring service.


6. Proposed AI Logic
MindPatch includes a proposed AI-assisted decision process. For this prototype, the logic is represented as a simulation concept; it is not connected to a deployed AI model.
Inputs
The proposed system may consider:
- User-entered mood score.
- User-entered screen-time duration.
- Time of day.
- The user's routine pattern.
- Reminder and suggestion preferences.
- Previous responses to suggestions, where the user has chosen to provide them.
Recommendation process
1. Collect the user's selected mood, screen-time information and relevant routine preferences.
2. Analyse the inputs for simple patterns, such as screen use exceeding a user-defined threshold.
3. Consider the time of day and whether the user has enabled reminders.
4. Generate an optional suggestion, such as taking a short screen break, trying a breathing activity or going for a brief walk.
5. Allow the user to accept, postpone or decline the suggestion.
6. Use feedback from previous days to inform future suggestions, while respecting the user's preferences.
Example decision rules
Example input pattern	Possible suggestion
Screen use is above the user's chosen threshold	Offer an optional screen break.
User reports feeling distracted during a study period	Suggest a short focus session with a planned break.
User wants a calmer evening routine	Offer a screen-free activity suggestion.
User declines or disables reminders	Respect that choice and avoid sending the declined reminder.


Five-day adaptation concept
Over a five-day period, the proposed system could review user-provided information and feedback to identify broad patterns, such as preferred break times or suggestions the user tends to accept. It could then adjust future recommendations.

This is a conceptual simulation of adaptive behaviour. It does not indicate that a live AI model has been trained, deployed or tested.
Pseudocode
START

Read mood_score
Read screen_time
Read time_of_day
Read routine_pattern
Read reminder_preference

IF reminder_preference is disabled:
    Do not send a notification
    Show suggestions only when the user opens the planner
ELSE:
    Analyse the entered information

    IF screen_time exceeds the user's chosen threshold:
        Suggest an optional screen break

    ELSE IF mood_score indicates the user wants support:
        Suggest a suitable wellness activity

    ELSE IF routine_pattern indicates a study period:
        Suggest a focus session and planned break

    ELSE:
        Suggest a general mindful-use tip

Allow the user to accept, postpone or decline

If the user provides feedback:
    Consider the feedback in future recommendations

END

7. Responsible and Ethical Design
Digital wellness information can be personal. MindPatch should therefore be designed around user choice, transparency and privacy.
- User control: Users should be able to manage reminders and choose whether to follow suggestions.
- Privacy: Mood entries and routine information should be collected only when needed and handled carefully.
- Transparency: Users should understand why a recommendation is being shown.
- Non-judgemental language: The app should avoid guilt, shame or punishment for screen use.
- Wellness boundaries: MindPatch is a habit-support concept, not a medical or mental-health diagnostic tool.
- Accessible interaction: Text, controls and visual indicators should be clear and easy to understand.

8. Testing, Evaluation and Current Scope
The questionnaire described in the research section gathered information about respondents’ digital habits. It was not a usability test of the Figma prototype.

No separate usability-testing records, participant feedback reports or before-and-after prototype iteration evidence were included in the project materials used to prepare this README. Therefore, this repository description does not claim that formal usability testing or design iterations have been completed.
Current project artefacts
- High-fidelity Figma prototype.
- Google Forms questionnaire response export containing 14 responses.
- Survey findings summarised in the project report.
- Proposed AI decision process and pseudocode.
- Project report describing the concept, research findings, prototype and proposed logic.
Scope and limitations
MindPatch is currently presented as a prototype concept. The AI recommendation process is simulated in the project documentation. The concept does not currently demonstrate live device-level screen-time tracking, a deployed machine-learning model, clinical assessment or validated behaviour-change outcomes.


9. Conclusion
MindPatch explores how an AI-assisted digital wellness planner could help students become more aware of their technology habits and build healthier routines through small, achievable actions. By combining mood logging, screen-time reflection, optional detox suggestions, gratitude journaling and habit tracking, the concept aims to make digital balance more approachable.

The project brings together user research, user-centred design and a proposed adaptive recommendation process. Its central principle is simple: technology should support students' lives, while students remain in control of how they use it.

MindPatch — Find your balance. Grow at your own pace
