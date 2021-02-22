CELLAR -- DRAFT AGENDA for Virtual Interim Meeting
February 23, 2021      21:00 Amsterdam  ***
                       20:00 UTC
                       16:00 NYC
                       13:00 San Francisco
(*** Time is anchored to Amsterdam)

INFO:
   https://datatracker.ietf.org/doc/agenda-interim-2021-cellar-02-cellar-01/

WEB CONFERENCE:

   https://whereby.com/cellar-interim

   THERE IS NO TELEPHONE DIALIN (You can try this at any time.)

   These notes at: https://github.com/cellar-wg/chair-notes
   
   Attendees
   * Spencer Dawkins 

1.  Note Well.  https://www.ietf.org/about/note-well/
2.  Accept draft minutes from January 26 meeting (attached below)

3.  Logistics for Meeting.
   3a) Shared COMIMD for notetaking:
       https://codimd.ietf.org/notes-cellar-virtual
       * Note that if you log in to the IETF datatracker, you'll 
       be able to edit these notes, add your name to attendee 
       lists, etc. *
       
       Please ask Spencer if you have questions.

   3b) APPEAR.IN is now called "whereby.com"

       https://whereby.com/cellar-interim

   3c) Roll call

4.  WG status update

   * draft-ietf-cellar-codec-05 was posted 2020-10-19, in ID Exists
   * draft-ietf-cellar-ffv1-19 was posted 2020-12-01, in AD Followup, but there's still an open discuss position
   * draft-ietf-cellar-ffv1-v4-16 was posted 2020-12-01, in ID Exists
   * draft-ietf-cellar-matroska-06 was posted 2020-10-19, in ID Exists
   * draft-ietf-cellar-tags-05 was posted 2020-10-19, in ID Exists
   * FLAC specification has not been posted to the datatracker yet
   
   * We agreed at the December 2020 meeting that we would have a focused conversation about FFV1 v4 in our February meeting, and noted then that the April 2021 date is not realistic.

5.  2021 virtual interim meeting dates

   * Please note that the our 2021 dates listed at https://datatracker.ietf.org/wg/cellar/meetings/
   * Sometime around 2021-09-28, we’ll see if we want to meet at IETF 112 on November 6-12, 2021, in person in Madrid.

6.  remaining FFV1 issues from DISCUSS
   * IESG ballot positions at https://datatracker.ietf.org/doc/draft-ietf-cellar-ffv1/ballot/
   * Only remaining Discuss position is (still) from Barry Leiba, on section 3.8.1.x
   * From our previous meeting: "Jerome, Michael and DR will organize a time to redo the 3.8.1 formula into more clear pseudo-code."
   * Did this happen?
   * Can we submit an update before the new IESG is seated, the week of March 8? If not, the new ADs may also be reviewing this draft (with new comments and Discusses) ... 

7.  From the mailing list: "The EBML Errata for the XSD file and how to proceed"
   * 
   
8   FFV1 v4 issues
   * 
   
9.  Matroska issues
   * 

10. FLAC issues
   * 

AOB?

    NEXT MEETING March 23, 2021.

Notes from previous meeting for approval

CELLAR -- DRAFT AGENDA for Virtual Interim Meeting
January 26, 2021       21:00 Amsterdam  ***
                       20:00 UTC
                       16:00 NYC
                       13:00 San Francisco
(Time is anchored to Amsterdam)

INFO:
   https://datatracker.ietf.org/doc/agenda-interim-2021-cellar-01-cellar-01/

WEB CONFERENCE:

   https://whereby.com/cellar-interim

   THERE IS NO TELEPHONE DIALIN (You can try this at any time.)

   These notes at: https://github.com/cellar-wg/chair-notes
   
   Attendees
   * Spencer Dawkins 
   * Michael Richardson
   * Steve Lhomme
   * Martin Below
   * Jerome Martinez
   * Michael Niedermayer
   * Dave Rice

1. Note Well.  https://www.ietf.org/about/note-well/
2. Accept draft minutes from December 1 meeting (attached below)

3. Logistics for Meeting.
   3a) Shared COMIMD for notetaking:
       https://codimd.ietf.org/notes-cellar-virtual
       * Note that if you log in to the IETF datatracker, you'll 
       be able to edit these notes, add your name to attendee 
       lists, etc. *
       
       Please ask Spencer if you have questions.

   3b) APPEAR.IN is now called "whereby.com"

       https://whereby.com/cellar-interim

   3c) Roll call

4. WG status update

   * draft-ietf-cellar-ffv1-19 was posted 2020-12-01, 
       * in AD Followup, but there's still an open discuss position
   * draft-ietf-cellar-codec-05 was posted 2020-10-19
   * draft-ietf-cellar-matroska-06 was posted 2020-10-19
   * draft-ietf-cellar-tags-05 was posted 2020-10-19
   * has a FLAC specification been re-posted to the datatracker lately? 
      https://datatracker.ietf.org/doc/draft-ietf-cellar-flac/
      Could use a new editor for this document.
      Do the contributors know they are covered by NoteWell.
        Spencer to check contribution file, check that this is in our weekly summary, etc. 
        Maybe Florian Weimer!
   * We agreed at the December meeting that we would have a focused conversation about FFV1 v4 in our February meeting, and noted then that the April 2021 date is not realistic.

5. 2021 virtual interim meeting dates

   * Please note that the proposed 2021 dates discussed at our previous meeting are now official, approved by our AD, and listed at https://datatracker.ietf.org/wg/cellar/meetings/
   * Sometime around 2021-09-28, we’ll see if we want to meet at IETF 112 on November 6-12, 2021, in person in Madrid.

6. remaining FFV1 issues from DISCUSS
   * IESG ballot positions at https://datatracker.ietf.org/doc/draft-ietf-cellar-ffv1/ballot/
   * Have we closed on Barry's concerns about section 3.8.1.x? Not quite yet - we just need to rewrite this section into text, rather than explaining the bespoke notation we're using. 
   * Any remaining comments from any ADs that still need to be addressed?
   * If all of the above, what needs to happen to submit an updated draft?

Jerome, Michael and DR will organize a time to redo the 3.8.1 formula into more clear pseudo-code.


7. From private e-mail to Spencer, now forwarded to the mailing list: "What is the canonical procedure to create an "infinite" audio stream, using ~~Opus and~~ FLAC codecs?"

        I have been attempting to locate a site which streams Opus continuously to test.
		
		I also am interested in the exact opusenc, et al. commands necessary to achieve creation of live audio streams. 
		
		The use cases are implementation of user-defined Web radio station, the capability to play the "infinite" stream using HTMLAudioElement (WHATWG/HTML) over HTTP. 
		
		("infinite" is quoted here as there is no way to verify infinity; the gist is playback should not stop; is not seekable).
   * 

8. Matroska issues
   * PR #447 has been under a lot of discussion in Github. We're ready to merge this PR. 
   * We're working on code now, so not a lot of changes to the spec this month.
    * issue about negative delay in ... ? https://www.reddit.com/r/mkvtoolnix/comments/l4uh6z/audio_delay_working_when_played_on_computer_not/

9. FLAC issues
   * none other than lack of editor going forward
   * https://github.com/ietf-wg-cellar/Cellar-FLAC
   * 

AOB?

    NEXT MEETING February 23, 2021.