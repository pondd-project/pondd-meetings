Meeting Minutes Feb 21, 2023 - Katai-Awkward
===

End goal, what a successful conclusion looks like:

  * Software: contribute a new backend to Katai, **KSY → compiled Python module**, and that module takes **data → Awkward Arrays**.
    - this includes coordination with Katai authors for PR review and hopefully acceptance
    - software scope?
    - [Katai user manual](https://doc.kaitai.io/user_guide.html)
    - copy [CppCompiler.scala](https://github.com/kaitai-io/kaitai_struct_compiler/blob/master/shared/src/main/scala/io/kaitai/struct/languages/CppCompiler.scala) with a new name
    - modify it to emit LayoutBuilder-filling instructions
  * Conference (talk or poster, maybe also proceedings)
    - where? IEEE? FAIR data workshop/conference?
  * Standalone paper
    - CSBS: https://www.springer.com/journal/41781
    - ~~JOSS~~

Resources

  * https://osf.io/2sner/, a high-level overview of Kaitai
  * CDSM datasets and data formats, https://osf.io/ybw7r/

Next week:

  * M: Get the kB-sized file into the web IDE
  * M: Get a katai-struct-compiler → C++ workbench set up
  * A: Get the KSY definition working for the new format
  * A: Start on the paper (intro, background)
  * What conference? What journal?

Meeting Minutes Jan 24, 2023 - Katai-Awkward
===

###### tags: `PONDD` `Meeting` `Kaitai` `Awkward`

:::info
- **Location:** https://ucdenver.zoom.us/j/97994358165
- **Date:** March 3, 2022, 10 AM Mountain
- **Participants:**
    - Amy Roberts (AR)
    - Jim Pivarski (JP)
    - Yana Osborne (YO)
    - Manasvi Goyal (MG)
- **Meeting Goal(s)**

:::

## Summary
<!-- Please fill me in after the meeting -->



## Notes 
<!-- Other important details discussed during the meeting can be entered here. -->
- Manasvi will go to CERN June 1 through August 31
- India Feb 6 through end of May
- Amy will find out how to handle finances for CERN and stipend
    - Monthly!
    - Minimum wage in switzerland is $25/hour
    - 7200 USD for 12 weeks in switzerland is IRIS-HEP rate
      - follow-up from Peter: for a student physically at CERN, IRIS-HEP is actually paying 3704 CHF per month (more)
      - needs insurance while at CERN (what Aryan did was buy international insurance in India)
    - 3600 USD for 12 weeks in india
    - CERN summer students suggest *90 CHF* per day
    - https://jobs.smartrecruiters.com/CERN/743999862723511-cern-openlab-summer-student-programme-2023
    - Also need to include travel, IRIS-HEP directly pays for travel.  Amy will find out how to handle travel at CU Denver.  Roughly 1000 USD from Delhi, round trip.
    - Amy will talk to Matt Turk about doing stipend reimbursements from his institution, maybe they will be more responsive!
    - Estimated totals: 
        - 4800 USD for 4 months in India at 1200 USD per month
        - 14407.2 USD for 3 months at CERN at 3704 CHF per month
        - 1500 USD for travel 
        - 20707.02 total
- Ianna will find out what needs to happen from CERN to get a letter for the visa process
    - Home institute: Princeton?  The home institution doesn't need to pay!
    - Do we ask CMS for a letter? Technically this doesn't have anything to do with CMS but that may not matter.
- Needed to get started
    - SuperCDMS membership and account access: https://confluence.slac.stanford.edu/display/CDMSPUB/Home, want confluence access 
    - https://osf.io/ybw7r/ access
    - data sets!  Amy will put the data on OSF and ask the collaboration if we can make the dataset public.  If the answer is no, then we could generate data!
    - data format descriptions!
    - Jim's fork of [kaitai_struct_compiler](https://github.com/jpivarski/kaitai_struct_compiler) and experiments with [awkward-kaitai](https://github.com/jpivarski/awkward-kaitai), which has copies of a few _small_ datasets and KSY files.
- https://gitter.im/kaitai_struct/Lobby
- What's the end goal?  Will Manasvi go to a conference/write a conference proceedings?
    - https://www.scipy2023.scipy.org/ this would entail writing a paper *before* going to the conference.  Timescale is Feb 22, too early!
    - CSBS: Computing and Software for Big Science article? https://www.springer.com/journal/41781
    - https://www.software.ac.uk/which-journals-should-i-publish-my-software
    - https://ieeebigdataservice.com/call-for-papers/
    - FAIR data workshop/conference?
- Standing meeting time is 10:30 AM Mountain on Tuesdays