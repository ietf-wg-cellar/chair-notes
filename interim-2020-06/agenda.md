CELLAR -- DRAFT AGENDA for Virtual Interim Meeting
May 26, 2020        21:00 Amsterdam  ***
                       19:00 UTC
                       15:00 NYC
                       12:00 San Francisco


INFO:
   https://datatracker.ietf.org/meeting/interim-2020-cellar-04/session/cellar
   https://datatracker.ietf.org/doc/agenda-interim-2020-cellar-04-cellar-01/

WEB CONFERENCE:
   https://whereby.com/cellar-interim
   THERE IS NO TELEPHONE DIALIN (You can try this at any time.)
   These notes at: https://github.com/cellar-wg/chair-notes

1. Note Well.  https://www.ietf.org/about/note-well/
2. Accept draft minutes from April 28 meeting (attached below)

3. Logistics for Meeting.
   2a) Etherpad for notes
       https://etherpad.ietf.org/p/notes-cellar-virtual?useMonospaceFont=true

   2b) APPEAR.IN is now called "whereby.com"
       https://whereby.com/cellar-interim

   2c) Roll call

4. WG status update
   * EBML -- still in RFC-editor queue, waiting to get to top
   * FFV1 -- version 13 was posted 2020-04-28
   *** NEEDS REVISED VERSION after AD Review ***

5. Mapping of MOV clean aperture values to Matroska

6. Allow for Dolby Vision Data to be saved within the mkv format (#373)

7. Add Support for Closed Captions to .MKV container (#375)

8. On restricting Unknown-Sized Elements

9. Unknown-Sized Elements are very hard or impossible to parse, and should be restricted (#338)

10. Add AVC and HEVC codec mappings (#377)

11. Other Matroska issues

AOB?

NEXT MEETING June 23, 2020.


---- PREVIOUS NOTES

CELLAR -- DRAFT AGENDA for Virtual Interim Meeting
April  28, 2020        21:00 Amsterdam  ***
                       19:00 UTC
                       15:00 NYC
                       12:00 San Francisco


Present:
Martin Below
Michael Niedermayer
Dave Rice
Steve Lhomme
Reto Kromer
Jerome Martinez
Michael Richardson
8. Spencer Dawkins


INFO:
   https://datatracker.ietf.org/meeting/interim-2020-cellar-04/session/cellar
   https://datatracker.ietf.org/doc/agenda-interim-2020-cellar-04-cellar-01/

WEB CONFERENCE:
   https://whereby.com/cellar-interim
   THERE IS NO TELEPHONE DIALIN (You can try this at any time.)
   These notes at: https://github.com/cellar-wg/chair-notes

1. Note Well.  https://www.ietf.org/about/note-well/
2. Accept draft minutes from March 31 meeting (attached below)
no comments. Minutes approved.

3. Logistics for Meeting.
   2a) Etherpad for notes
       https://etherpad.ietf.org/p/notes-cellar-virtual?useMonospaceFont=true

   2b) APPEAR.IN is now called "whereby.com"
       https://whereby.com/cellar-interim

   2c) Roll call

4. WG status update
   * EBML -- still in RFC-editor queue, waiting to get to top
   * FFV1 -- version 12 was posted 2020-01-28
   *** new revision posted 2020-04-28
   - issues still not handled.
- Jerome will write down the list
     - §3.4 (about Q)
     - §3.8.1.1.1 (non-normative example)
     - §3.8.1.2 (no referenced comments)
     - §3.8.2.3 (light documentation of the "state" structure)
     - §4 (MD-style anchor)
     - §4 (phrasing is confusing)
     - §4.1.16 (clarification of the word "header")
     - §4.2.3.4 (normative dependencies)
     - §4.6 (ambiguous)
     - §4.7 ("type" indicators)
     - §6 (have a look on RFC 4175, Section 8)

5. Extension drafts on Matroska / FFV1
- Dave Rice: ffv1 encoding float (vs integer) base formats... a new feature MN and JM.
- this might be in ffv1 (v0-3) or in v4, and whether or not the v3 format could support it.
- ffv1 can losslessly store *integer* formatted pixel formats, but can not store float based pixel formats
- could be done as an extension document to the v3.

   - Dolby Vision, issue #373 https://github.com/cellar-wg/matroska-specification/issues/373
   - will go into a different document

6. Work on Matroska issues.
  -  reduced number of open pull requests, created some new issues
  - all open pull requests were reviewed.

7. AOB.
Matroska meeting in Amsterdam. _No Time To Wait._
Still stalling on opening registration and call for proposals.  
Many large gatherings are cancelled due to COVID, so it might delayed or cancelled.
Registration decision will take a few weeks.



NEXT MEETING May 26, 2020.