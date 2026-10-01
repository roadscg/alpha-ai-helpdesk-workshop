Build Your Internal AI Helpdesk

ALPFA Boston AI Hub Accelerator 2026 \u00b7 Workshop 2 \u00b7 Roads Consulting Group

In 2.5 hours you will build a working AI assistant for your company. It answers your employees' questions about your policies and processes, and when it can't help, it automatically hands the conversation to a real person by email.

Employee asks a question (English or Spanish)
        |
Hermes 3 answers from YOUR documents only
        |
"Did that solve your issue?"
   YES: done            NO: collects name + issue
                              |
                        Email to your support contact
                              |
                        A human takes over

No technical experience needed. We build everything together, step by step.

Before you start
 A laptop with Chrome or Edge (a phone or tablet won't work for building)
 An email account you can open during the event
 1 to 3 company documents in digital form: FAQ, vacation policy, business hours, any "how do I..." process. Messy formatting is fine. No documents? Use the Acme Coffee sample below.
 The support email address: who should receive questions the bot can't answer?
 A free account at typebot.io (we can also create it together at the start)

About the workshop keys: during the event we share one AI key and one mail sender. Get them from the short link written on the whiteboard. They are deactivated after the event, so the "Take it home" section shows you how to get your own. Never post keys publicly.

The steps
1. Get your template (10 min)

Log into Typebot, open the template link from the whiteboard, click Duplicate, and rename it [Your Company] Helpdesk.

2. Connect the workshop AI key (5 min)

Open the AI block, click + Add OpenRouter account, and paste the workshop key. Without this, the bot has no brain.

Seeing Missing Authentication header? That means this step is missing.

3. Give the bot its job description (10 min)

In the AI block, replace the placeholder System message with this (copy it, then put your company name in):

You are the internal helpdesk assistant for [COMPANY NAME]. Answer employee
questions using ONLY the company information below. If the answer is not in
that information or you are not sure, reply exactly: "I don't have that
information, let me connect you with our support team." Be brief and friendly.
Reply in the same language the employee writes in.

COMPANY INFORMATION:
[PASTE YOUR COMPANY INFO HERE]

That last instruction is why your bot speaks English and Spanish. Same bot, same documents, every employee included.

4. Feed it your company knowledge (20 min)

Replace [PASTE YOUR COMPANY INFO HERE] with your FAQ, policies, hours and processes as plain text.

The privacy rule: nothing goes in that you wouldn't pin on the breakroom wall. No salaries, no health information, no passwords.

5. Test it (5 min)

Click Preview. Ask something your documents answer. Then ask something they don't. Watch how differently it responds.

6. Build the safety net (15 min)

Heads up: the question "Did that solve your issue?" is a separate Text bubble placed above the Buttons block; the buttons themselves only hold Yes and No, I need help.

On "No": two short questions (name, describe the issue), then the Send email block with your support address in the To field.

7. Connect the bot's mail sender (10 min)

In the email block click + Add SMTP account and copy the 6 values from the whiteboard link exactly as written. One typo and the email fails; the password and the Secure toggle + port are where typos happen.

8. Publish, then trigger a real escalation (10 min)

Emails do NOT send in Preview. Click Publish, open your public link, ask a question, answer "No, I need help", fill the form, then check the support inbox (and spam) until the email arrives. That email is your safety net working.

9. Bot Bingo (15 min)

Swap seats with a neighbor and try to stump their bot with the questions below. Every wrong answer gets fixed on the spot: add one line to the knowledge, ask again.

10. Make it yours (bonus, if you're ahead)

Open the Theme tab in Typebot: set your company's main color, and upload your logo as the bot's avatar. Five minutes and the bot feels truly yours.

11. Put it in your pocket (everyone, final step)

With your published bot open in Chrome: click the address bar, then the share icon, then Create QR code. Scan it with your phone camera.

Your company's AI, in your pocket, built by you.

No documents? Use Acme Coffee Co.

Copy everything in this block into your bot's COMPANY INFORMATION section:

About: Acme Coffee Co. is a small coffee roaster and cafe with 12 employees, founded in 2019.
Business hours: Monday to Friday 7am to 6pm, Saturday 8am to 2pm, closed Sundays.
Vacation (PTO): Full-time employees receive 10 paid vacation days per year; part-time employees receive 5. Request time off by messaging your manager at least 2 weeks in advance. Unused days do not roll over to the next year.
Sick days: 5 paid sick days per year. Notify your manager before 9am if you cannot come in.
Paid holidays: New Year's Day, Independence Day, Thanksgiving Day, and Christmas Day. The cafe is closed those days.
Payroll: Everyone is paid every two weeks on Friday by direct deposit. For paycheck questions, contact the office manager.
Expenses: Email a photo of the receipt to accounting@acmecoffee.com before the 25th of the month; reimbursement comes in the next payroll. Purchases over $100 need manager approval first.
Equipment problems: If the espresso machine, grinder or register has a problem, tell the shift lead. Do not try to repair equipment yourself.
Dress code: Black or brown apron, closed-toe shoes, hair tied back.
Support: For anything not covered here, the office manager is the support contact.
Bot Bingo questions

Mark each: \u2713 answered correctly \u00b7 \u2717 wrong or invented \u00b7 E correctly escalated

Should answer (if the knowledge covers it)

What are our business hours?
How many vacation days do I get?
How do I submit an expense?
When do we get paid?
What is the dress code?
Which holidays are we closed?

Should escalate (a human issue) 7. My paycheck is missing overtime hours. 8. I want to make a complaint about a coworker. 9. Can I get an advance on my next paycheck? 10. I think my vacation request was lost, nobody answered me.

Tricky (watch for invented answers) 11. Can I take three weeks of vacation at once? 12. What happens to my unused vacation days?

The winner isn't the bot that never fails: it's the owner who fixes the most gaps before going home.

If something goes wrong
What you see	What it means and how to fix it
Missing Authentication header	The AI key isn't connected. Go back to step 2.
The bot invents answers	The job description lost its "answer ONLY from the company information" rule. Re-check step 3.
You ask and nothing comes back	The AI answer isn't being saved or shown. Raise your hand; 30-second fix.
The escalation email never arrives	Did you Publish first? Emails don't send in Preview. Then check spam. Then re-check the SMTP values.
"We couldn't send the test email"	A typo in one of the 6 SMTP values, usually the password or the Secure/port pair. Retype them, no spaces.
Take it home: get your own keys

The workshop keys are deactivated after the event. Independence takes about 20 minutes:

Your own AI key (replaces step 2's key)

Create an account at openrouter.ai
Credits: add $5 (a small business runs for months on that; each answer costs about $0.0002)
Keys: create one, copy it
In your bot's AI block, replace the workshop credential with yours

Your own mail sender (replaces step 7's sender)

Create a free account at brevo.com (300 emails/day free)
Profile menu > SMTP & API > SMTP > Generate a new SMTP key
In your bot's email block, create a new SMTP account: Host smtp-relay.brevo.com, Port 587, Secure OFF, Username: your Brevo login, Password: the SMTP key
Publish again and send yourself a test escalation

Your first week

Monday: share your bot's link with one employee as a pilot
Count two numbers all week: questions solved vs. questions escalated
Every escalated question is homework: add the answer to the knowledge so the bot solves it next time
Friday: if the numbers look good, share it with the whole team

Built at the ALPFA Boston AI Hub Accelerator with Roads Consulting Group. Questions after the event: andres.hincapie@roadscg.com
