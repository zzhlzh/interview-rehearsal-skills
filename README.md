# Interview Rehearsal Skills 面试预演技能包

A pair of Muse skills that turn a target job description (JD) and your own resume into a personal mock interview, instead of a generic question bank.

把目标岗位的 JD 和你自己的简历，变成一场贴身的模拟面试，而不是背通用题库。

## Skills included

| Skill | Use it for |
|---|---|
| `general_interview_rehearsal` | Any role. It classifies the role family from the JD first, then adapts questions and follow-ups to that family. |
| `software_testing_interview_rehearsal` | Software testing roles only. It drills deeper on test design, defect life cycle, interface testing, SQL checks and automation. |

Rule of thumb: if the JD is a testing role, prefer the testing skill. Otherwise start with the general skill.

## How it works

1. **Parse the JD** into must-have skills, duties, tools and bonus points.
2. **Map the JD to your resume**, marking each item as strong evidence, weak evidence or missing.
3. **Flag risk points**: resume claims with numbers, tools or projects that an interviewer can drill into.
4. **Run the mock interview** one question at a time, with one or two follow-ups per answer, a 1 to 5 score, and a stronger version of your answer in your own words.
5. **Compile a personal manual** with the JD breakdown, risk points, improved answers, a last-day checklist and your top 3 weak points.

Session modes: quick round (3 high-risk questions), full round, and teaching mode (model answer first).

## Usage

1. Copy a skill folder into your Muse custom skills directory:

   ```text
   ~/workspace/custom-skills/<skill_name>/
   ```

   Each folder needs both `SKILL.md` and `skill.yaml`.

2. Start a chat with Muse and provide:
   - the target JD (text, link, screenshot, PDF or Word)
   - your resume (PDF, Word or pasted text)

3. Say one of:
   - `开始面试预演` (start interview rehearsal)
   - `Start an interview rehearsal for this JD`

Muse will classify the role, map the JD to your resume, and start with the first question.

## Privacy note

These skill files contain no personal data. Your JD and resume stay in your own Muse workspace and are never part of this repository. Never commit a real resume, phone number or email address to a public repository.

## Notes

- Answers are always built from your real resume. The skills explicitly forbid inventing experience, tools or numbers.
- Re-run a short round after you revise your resume, so new wording gets tested before it reaches an interviewer.
