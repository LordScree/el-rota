# Welcome to El Rota

This is a simple staff rota management system.

> _rota (noun), rotas (plural noun), Rota (noun), the Rota (noun)_\
> Mainly UK
> 1. A list showing when each of a number of people has to do a particular job.

See: [Rota | English Meaning - Cambridge Dictionary](https://dictionary.cambridge.org/dictionary/english/rota)

I'm not Spanish. I just picked the name on a whim. I don't think this is classed as cultural misappropriation, but if you're offended then perhaps we can agree to disagree on that point.

Of course, if I was Spanish, I would know that the Spanish word "rota" translates to "broken" in English. So, this repo is really named "The Broken". That's actually quite a cool name, so I'm keeping it.

## Goals of El Rota

Aside from the actual rota functionality, which is outlined below, there are two softer goals for El Rota:

1. **Web accessible** to staff members: Staff members on the rota need to be able to see the rota, see when they are on the rota and see where the gaps are.
1. **Privacy first**: By default, Staff Member A is not able to see who else is on the rota, only that someone else is on the rota. (Additional permissions are required to see more information.)

## User stories

1. As a manager, I **must** be able to add and remove staff members from the list of staff members.
1. As a manager, I **must** be able to allocate staff members to the rota.
1. As a manager, I **must** be able to see who is working on which date.
1. As a manager, I **must** be able to configure the settings of the rota, including the minimum staff members.
1. As a staff member, I **must** be able to see the dates I am working.
1. As a staff member, I **must** be able to see the list of dates, and how many people are working on those dates (including me, if I am working).

## Other requirements

1. User identities **must** be verified before accessing the tool, such that only known staff members or managers are permitted to access the tool.
1. Users **must** be prevented from performing actions without authorisation.
1. The system **must** be keyboard navigable.
1. The system **must** be accessible to people using screen-reader technology.

## To-do list

 - [ ] Design something... probably prototyping using spreadsheets (_mmmm, spreadsheets_).
 - [ ] Write some actual code...
 - [ ] El Rota **must** display a list of dates.
 - [ ] El Rota **should** support a minimum staff requirement, with warnings when fewer staff members than the minimum are allocated on a given date.
 - [ ] El Rota **should** support multiple offices.
 - [ ] El Rota **could** support staff skills, allowing for restrictions on minimum numbers of staff with specific skills (and corresponding warnings).

 ## Side notes about the author

 Look, I've just come off a massive _[He Who Fights with Monsters](https://app.thestorygraph.com/series/1214150)_ bender. My mind might not be all there right now, okay? Don't judge me.

 But this will be a little background project for me for a bit. Something to keep me off reading the latest world news.

 # This project is for humans

 This is a human project for humans. Generative AI / GPT tools are **not** permitted during the **design**, **development** or **implementation** of this project. This applies to all contributors on this project and is intended to apply to all future distributors as well - see License.

 # License

 This software is licensed under a NON-AI variant of the Apache 2.0 open source license, via [NON-AI-LICENSES](https://github.com/non-ai-licenses/non-ai-licenses). Reuse or redistribution for any purpose must include the license contained within the LICENSE file.

 Copyright &copy; Oliver Clare, 2026.