# ISKCON Youth Rebus Challenge

A single-page, mobile-first Janmashtami engagement game for selected young adults aged 18–30.

## Participant journey

1. The participant enters a name and mobile number before the game. A separate optional checkbox opens the ISKCON Youth WhatsApp Community join page when the game starts.
2. A short visual guide explains what a rebus is and how to solve each interaction style before the participant starts.
3. The game selects seven rebus puzzles from the supplied reference set while guaranteeing a mixture of interaction styles.
4. Participants solve puzzles by filling letter slots, arranging word tiles or typing the phrase—there are no multiple-choice answers.
5. Every participant starts with three lives. A third wrong answer ends the round.
6. One optional hint is available for each puzzle, and hint usage is recorded with the result.
7. Successful participants see a gift claim code after finishing the round.
8. The final screen promotes Saturday evenings and provides direct calls to action for both the WhatsApp Community and `@iskcon_ns_youth` on Instagram.

## Netlify setup

Connect this repository to Netlify. No build command is required and the publish directory is `.`.

Netlify Forms detects two forms:

- `youth-signup` stores the name, mobile number, optional WhatsApp Community choice and an anonymous participant ID. Submission happens in the background so opening WhatsApp or a slow connection does not block the game from starting.
- `quiz-result` stores the outcome, score and hint usage against the same participant ID.

After deployment, confirm both forms appear under **Forms** in the Netlify dashboard and complete one end-to-end test submission.

## Content

The game currently contains 19 rebus puzzles recreated from the supplied screenshots. Every round contains three letter-slot puzzles, two word-building puzzles and two typed-answer puzzles. The wording, accepted answers and gift policy should receive a final event-team review before publishing.
