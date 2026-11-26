# Karaoke Anonymous — Development Roadmap

Updated November 26, 2026 (Central Time).

## Current release
- Free guest access to trivia and the 10 Steps of Non-Recovery.
- Published the 20-question humorous self-assessment with five result levels, private in-browser scoring, shareable results and links to Step 1.
- Local progress, personalized printable certificate, score sharing, friend challenges, and private question reports.
- Keep the established site branding and compact quiz layout.

## Future release — shared karaoke ecosystem (Founder approved for roadmap; implementation deferred)
- [ ] Explore shared Supabase authentication with Addicted to Karaoke (A2K): one member identity across both websites, existing Google and email/password login.
- [ ] Preserve guest access; signing in remains optional for participating in entertainment.
- [ ] Save signed-in quiz results, best scores, achievements and 10-step progress across devices.
- [ ] Award a distinct collectible A2K badge for each qualifying Karaoke Anonymous examination and program completion.
- [ ] Introduce proposed badge tiers: Bronze 60–79%, Silver 80–99%, Gold 100%; on a 25-question exam these mean 15–19, 20–24, and 25 correct respectively.
- [ ] Retakes improve the existing badge to the highest earned tier, never duplicate it or downgrade it.
- [ ] Consider an exclusive Karaoke Hall of Fame badge for mastering all eligible examinations; define the qualifying threshold and treatment of future new exams before launch.

### Planned unique badge identities
| Program or exam | Badge |
| --- | --- |
| 10 Steps of Non-Recovery | Certified Karaoke Addict (completion, no score tiers) |
| Song Challenge | Master of Musical Obsession |
| Knowledge Challenge | Doctor of Karaoke (PhK) |
| One-Hit Wonders | Master of One-Hit Wonders |
| Future 1980s challenge | Professor of the '80s |
| Future veteran challenge | Certified Karaoke Dinosaur |

Badge names are concepts for the collection; reserve the existing perfect-score academic titles for perfect scores, and clearly indicate lower tiers. The veteran challenge may use a different assessment format, so its eligibility rules remain to be defined. Artwork, exact award rules, Hall of Fame criteria and release version require Founder review before implementation.

### Integration guardrails
- Keep shared login and cross-site badge integration on the back burner (a later version, not the current release).
- Do not change existing A2K authentication or roles until explicitly approved.
- Validate graded results and award eligibility on the server; browser scores alone are not trusted evidence. The 10 Steps is a self-reported entertainment achievement.
- Use stable member and badge identifiers, idempotent awards, scoped permissions and explicit consent before making achievements visible on a member profile.
- Coordinate A2K backend work with Sophie and frontend work with Milo; obtain Founder approval before production integration.
- No subscription or separate account required to play quizzes.

