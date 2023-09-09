# Career Recommendation Expert System

## Introduction

Determining your career path is a crucial step in having a successful career, but some individuals may find it difficult to choose the best career for them. It can also take some time to locate a job that fits the desired role. By using the Myers-Briggs Type Indicator (MBTI), you may be able to identify the best career alternatives for you.

## Problem Definition

According to Inc., 70% of workers stated that they were dissatisfied with their career choices. Since most individuals spend 8 to 10 hours a day working, finding a career path that is right for you is essential. However, choosing a professional path can be difficult, whether you are just starting out in the job market or thinking about changing careers. Furthermore, it can be challenging to find a job or your ideal position since some organizations only hire internally, making it difficult to locate job offers that a company publicly posts online.

## AI Approach

Nowadays, artificial intelligence (AI) is one of the trendiest technologies that has helped facilitate many aspects of human life. One of its common approaches is "Expert Systems," which are computer programs that simulate the judgment of a human expert. These systems use specialized knowledge to handle complex issues. Prolog, a programming language, is ideally suited for developing expert systems due to its ability to draw conclusions from established rules and its built-in search and backtracking algorithms.

## Solution

Our solution involves creating an expert system with Prolog that selects the ideal career for each MBTI personality type. Additionally, the expert system will offer a job link to simplify the job-searching process. The system will provide personalized career recommendations based on the user's MBTI personality type and geographical preference.

### Key Components

```prolog
/* 
   Careers Recommendation Decision System 
   suggest suitable careers based on user personality and location 
*/

/* 
   suggestCareer is the fundamental rule of our program 
   it contains a welcome message and questions the user should answer.
   We use write(' ') and read(Variable) to write questions and read user answers, 
   which are built-in predicates in Prolog.
   However, We also use an if statement (careers(CareerTitle, Company, G, P) -> true : false) 
   so the program will display the recommended company link in a clear format. If the user's
   input matches one of the program facts, the program will display the career title and appropriate
   company link to apply based on user personality and geographical preference. 
   Otherwise, it will provide an apology message because the user's location does not match any facts in our program.
*/
