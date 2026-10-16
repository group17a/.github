# 17A

We work with state and local governments: city halls, county IT shops, state agencies, and the nonprofits that work alongside them. Health, economic mobility, public safety, shared services, and whatever the data problem of the week turns out to be. Most of that work is confidential, which makes for a quiet GitHub. This page is the part we are allowed to show you.

## Start here

<table>
  <tr>
    <td width="33%" valign="top">
      <a href="https://group17a.github.io/reducing-violence-whitepaper/"><img src="https://raw.githubusercontent.com/group17a/.github/main/profile/assets/reducing-violence-whitepaper.png" alt="Reducing Violent Crime Without New Budget, New Staff, or More Arrests" width="100%"></a>
      <br><b><a href="https://group17a.github.io/reducing-violence-whitepaper/">Reducing Violent Crime Without New Budget, New Staff, or More Arrests</a></b><br>
      For city leaders who have been told the only answers are more money, more officers, or more arrests. Dallas's 2024 to 2025 implementation is the case study. Nine cities of incident data explain why the map keeps moving out from under a static strategy.
      <br><sub><a href="https://group17a.github.io/reducing-violence-whitepaper/Reducing_Violent_Crime_17A.pdf">PDF</a> · <a href="https://github.com/group17a/reducing-violence-whitepaper">source</a></sub>
    </td>
    <td width="33%" valign="top">
      <a href="https://gizmowarehouse.org/gizmo/medicaid-work-requirements"><img src="https://raw.githubusercontent.com/group17a/.github/main/profile/assets/medicaid-work-requirements.png" alt="Who Loses Medicaid in 2027" width="100%"></a>
      <br><b><a href="https://gizmowarehouse.org/gizmo/medicaid-work-requirements">Who Loses Medicaid in 2027</a></b><br>
      Starting in 2027, the federal work requirement will end coverage for millions of people, most of whom still qualify. Which ones, where they live, and whether their state can verify work before the deadline. A map, a brief for every state, and the arithmetic underneath.
      <br><sub><a href="https://gizmowarehouse.org/gizmo/medicaid-work-requirements">live map and state briefs</a> · <a href="https://github.com/eichenbaumj/gizmowarehouse.org/tree/main/gizmos/medicaid-work-requirements">source and data</a></sub>
    </td>
    <td width="33%" valign="top">
      <a href="https://gizmowarehouse.org/gizmo/only-way-to-start-is-by-starting"><img src="https://raw.githubusercontent.com/group17a/.github/main/profile/assets/only-way-to-start-is-by-starting.png" alt="The Only Way to Start Is by Starting" width="100%"></a>
      <br><b><a href="https://gizmowarehouse.org/gizmo/only-way-to-start-is-by-starting">The Only Way to Start Is by Starting</a></b><br>
      What a state or local agency can get out of AI in ninety days: one accountable owner, a handful of paid licenses, and one real piece of work that somebody is already dreading. No strategy deck required.
      <br><sub><a href="https://gizmowarehouse.org/gizmo/only-way-to-start-is-by-starting">read it</a></sub>
    </td>
  </tr>
</table>

## What we do

State agencies, city and county governments, and the nonprofits and funders that work alongside them hire us for one of five things: deciding what to build when nobody can yet say what it is, building it next to the team that will own it, getting an agency something useful out of AI, redesigning a process that has outgrown its org chart, and leaving a team able to keep going after we leave. Some of what that has looked like:

- **Public safety.** A cross-agency, place-based violence reduction effort in Dallas: incident-level data on a half-mile grid, environmental interventions at the places where violence concentrates, and coordination across departments instead of new budget, new staff, or more arrests. Violent crime fell 8 percent in the intervention areas while comparable areas held flat. The white paper above is the long version.
- **Health.** Technical lead on a multi-year state-based health insurance exchange launch. A data automation strategy for a state Medicaid program, so that the new work requirements cost as few eligible people their coverage as possible.
- **Shared services.** Triage and modernization of a large transit agency's inbound workers' compensation claims. The new process saved more than $20 million in its first year.
- **Economic mobility.** A state tax credit for lower- and moderate-income renters, one of the larger ones in the country. Benefits-cliff fixes in TANF, child care assistance, and the ACA marketplace.
- **Data and technology.** Crime, 311, eviction, and child-poverty explorers for cities and the organizations that watch them, built from NIBRS incident data, open data portals, and Census microdata, with the numbers checked against the source rows before anyone sees a map. Council-district briefings generated from the same pipelines. AI rollouts for agencies and partner organizations, from the ninety-day plan above to standing in as the technical lead while a team hires its own.

## What we build with

- **Python** (pandas, geopandas, matplotlib) for analysis, and Jupyter while we are still thinking.
- **React, TypeScript, and MapLibre** for anything with a map. Lovable when we want a front end this afternoon.
- **Supabase** for sign-in and the data that cannot be public. **Cloudflare** Pages, Workers, and R2 for anything that should stay cheap and fast forever.
- **Claude Code** does most of the typing. We describe the whole thing in plain language and ask for all of it. What comes back is better than we asked for, not what we asked for at all, or something that looks right and isn't. Telling those apart is the job. Codex when we want a second opinion that did not write the first draft.
- **PowerPoint, Word, and PDF**, generated from the 17A templates, for the people who will never open GitHub. That is most of them.

## How we work

- **The reader of every report and briefing is a council member at 9 pm.** They get the conclusion on page one and the method in the appendix. Nothing that needs a glossary.
- **Every number has a receipt.** If we cannot trace a figure back to its source, the page says so instead of rounding it off.
- **The code makes the call. The model does the reading.** When a tool reaches a conclusion, plain code computes it from typed data. Models search and draft. Nothing pasted into an input can change the outcome, and we keep a test suite that tries.
- **The methodology and the code change in the same commit.** When they disagree, one of them is wrong, and we fix it that day.
- **Done means seen.** The live URL after the publish, the rendered PDF, the generated document opened and read. A green build is where checking starts.

## More from the 17A team

| | |
|---|---|
| [High Floor, Low Ceiling](https://gizmowarehouse.org/gizmo/public-private-compensation-comparison) | Public pay holds its own at the bottom of the labor market and falls far behind at the top, which is exactly where you were hoping to hire. By skill, by field, by level of government, and over time. |
| [Pricing the Fear of Data Centers](https://gizmowarehouse.org/gizmo/data-center-restriction-cost) | What a town gives up when it says no to a data center (tax revenue, mostly; the jobs were never coming), a national map of who said no, and the terms to demand if the answer is yes. |
| [The Price of Insuring Yourself](https://gizmowarehouse.org/gizmo/self-insurance-cost) | We read the audited statements of 135 New York governments so you would not have to. The ones that insure themselves have bills that swing nearly twice as much from year to year. |
| [NYC Property Tax: Who Pays, Who Doesn't](https://gizmowarehouse.org/gizmo/nyc-property-tax-map) | A parcel-level map of effective rates, and the long answer to why two identical brownstones across the street from each other pay very different bills. |

## Where the work lives

Most of what we ship sits in private client repositories, where it will stay. The public repositories are here. Some of the team keep their own workshops: Joe Eichenbaum's is at [gizmowarehouse.org](https://gizmowarehouse.org), where the music theory and the Talmud also live. A repository here that says it is in field test is still being built, and its README will tell you how much to trust it.

If you work in or around government and something here would help, write to [letsgo@group17a.com](mailto:letsgo@group17a.com). Better government is worth the effort, and it is more fun with company.
