# North Sydney Youth Rebus Challenge

A single-page, mobile-first Janmashtami engagement game for selected young adults aged 18–30.

## Participant journey

1. A youth volunteer starts the challenge without asking for personal information.
2. The participant receives seven randomly selected rebus puzzles based on the supplied reference screenshots.
3. Two wrong answers are allowed. A third wrong answer ends the round.
4. After the game, the participant sees their result and an explanation of why North Sydney Youth would like their contact details.
5. First name and mobile are required, email is optional, and WhatsApp group permission is a separate optional checkbox.
6. Successful participants see a gift claim code after submitting the form.
7. The final screen links directly to `@iskcon_ns_youth` on Instagram.

## Netlify setup

Connect this repository to Netlify. No build command is required and the publish directory is `.`.

Netlify Forms detects the `youth-signup` form and stores:

- contact details and consent;
- optional WhatsApp opt-in;
- anonymous participant ID;
- quiz result and score.

After the first production deployment, confirm `youth-signup` appears under **Forms** in the Netlify dashboard and complete one end-to-end test submission.

## Content

The game currently contains 19 rebus puzzles recreated from the supplied screenshots. Seven are selected randomly for each round. The wording, accepted answers and gift policy should receive a final event-team review before publishing.
