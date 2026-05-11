# AI4SG-project
My part 5 for AI4SG project Milestone 3.
## (1) the problem and who it affects: 
At San José State University, many students feel unsafe when walking around campus and nearby streets. The main users of the app are SJSU students or residents who travel through campus daily but do not always have clear or reliable information about safety. Even though safety reports exist, they are often hard to read, unorganized, or spread across different sources. Students cannot easily understand what is happening, where it is happening, or how serious it is.

## (2) the AI capability used and why it fits:
The main AI ability used in the labs is taking messy or unstructured information and turning it into structured, organized data. In Lab 2, the AI pulled details like location, type of issue, and urgency from written messages. In Lab 3, it looked at images and tried to identify what was happening in them. This is useful for the problem because safety reports are not consistent. The AI helps turn unclear messages into a simple format that is easier to read and compare. This can help students quickly understand what is going on.

## (3) the workflow — what goes in, what the AI does, what comes out, and who acts on it, including screenshots
First, the system takes input like a written safety report or an image from campus. The AI reads the content and pulls out key details like where it happened, what happened, and how serious it seems. Then the AI organizes this into a simple, structured output. For example, a message like unknown suspicious person walking near dorms at night becomes a labeled report with location, category, and urgency level.

(4) one failure case tied to a lab output:
One issue I saw in Lab 2 is that the AI does not always give the same answer. If you run the same message multiple times, it can change the urgency level or category. For example, one report might be labeled “low risk” in one run and “medium risk” in another. This shows that the system is not fully reliable yet, especially for something like safety, where consistency matters.

## (5) the oversight decision and the one change, each with its tradeoff stated.
A human should still check important safety messages before they are shared with students. The AI can help organize information, but it should not be the only one deciding what the final output is. The benefit of using AI is speed and organization. The downside is that it can make mistakes or be inconsistent. If we add human review, it would take more time for the report to come out but it is much safer.
