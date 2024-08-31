Quiz App
Overview
The Quiz App is an Android application designed to provide users with a straightforward and interactive way to answer quiz questions. The app features a clean interface with a question and multiple-choice answers, along with a submit button to finalize the user’s response.

Features
Display Quiz Questions: Shows the current question at the top of the screen.
Multiple Choice Answers: Presents four possible answers (A, B, C, D) for each question.
Submit Button: Allows users to submit their selected answer.
Layout Description
The app's user interface is defined in the activity_main.xml layout file. The layout is structured using a RelativeLayout with the following components:

TextView (total_question):

Displays a label "Total Question".
Centered horizontally with a margin at the top.
Uses a bold font style with a large text size and a light color.
LinearLayout (choices_layout):

A vertical container that holds the question and answer buttons.

Centered in the parent layout with a top margin to position the question properly.

TextView (question):

Shows the quiz question.
Positioned with a margin at the top.
Uses bold text style with a large font size and a light color.
Buttons (ans_a, ans_b, ans_c, ans_d):

Each button represents a possible answer (A, B, C, D).
Styled with a light background and black text.
Sized to fill the width of the parent container.
Button (btn_submit):

Positioned below the answer choices.
Allows users to submit their selected answer.
Styled with a distinct color for visibility and uses a large font size for easy readability.
