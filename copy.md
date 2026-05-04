# Coherence — Site Copy

This file contains every word of body copy across the site, organized page by page. Edit freely. After you make changes, let me know and I'll port them back into the HTML.

Conventions:
- `**Field:**` markers (e.g., `**Headline:**`, `**Body:**`) tag where each piece of text lives in the page. Do not delete those markers — they tell me where to put the text.
- Italic emphasis is written as `*word*`. Bold as `**word**`.
- Blockquotes use `>` and are followed by an attribution line on the next `>` block.
- Pull-quotes (the larger styled quotes that include a citation) are marked `**Pullquote:**`.
- Standout sentences (large original-text breakouts with rules above and below, no citation) are marked `**Standout:**`.
- Inline links are written as `[text](page.html)` or `[text](page.html#anchor)`.

---

## SITE-WIDE STRINGS

**Site name:** Coherence

**Site tagline (footer):** On the moral coherence of alignment

**Browser tab titles:**
- Home: Coherence — On the moral coherence of alignment
- In Brief: In Brief — Coherence
- The Argument: What models learn from us — Coherence
- Why the AI Industry: Why the AI Industry — Coherence
- Evidence: Evidence — Coherence
- Objections: Objections — Coherence
- What to Do: What to Do — Coherence
- Sources: Sources — Coherence

**Meta descriptions:**
- Home: A case to the AI industry that the alignment problem and the question of animal welfare are versions of the same problem.
- In Brief: The argument in short. A four-minute version.
- The Argument: A case that the AI alignment problem and the question of animal welfare are versions of the same problem.
- Why the AI Industry: Why this argument has unique purchase on the AI field.
- Evidence: The empirical case, gathered. Specific findings on sentience and suffering across species.
- Objections: The strongest objections to this argument, taken seriously.
- What to Do: Concrete operational, philanthropic, and research moves for people in different positions in or near the AI industry.
- Sources: The works the argument leans on, by author.

**Top nav labels (in order):**
- Home
- In Brief
- The Argument
- Why the AI Industry
- Evidence
- Objections
- What to Do
- Sources

---

# PAGE: Home (`index.html`)

**Hero background image:** `img/hero-piero.jpg` (full-bleed, with `img/hero-piero-1200.jpg` swapped in below 640px). The image is Piero di Cosimo's *The Forest Fire* (c. 1505); a soft dark gradient at the bottom keeps the headline legible.

**Eyebrow:** An argument to the AI industry

**Hero headline (h1):** Animal welfare is upstream of alignment.

**Hero subhead:** A case that the alignment problem and the question of animal welfare are versions of the same problem.

**Hero attribution (small caption, bottom-right of hero):** Piero di Cosimo, *The Forest Fire*, c. 1505. Ashmolean Museum.

**Body — opening paragraph (with drop cap):**

The alignment problem asks how to build artificial systems whose values track human values. The standard answer is that those values are not specified directly. They are inherited from the corpus of human work the system is trained on, and from the conduct of the people doing the training.

**Body — paragraph 2:**

The body of recorded human moral writing contains a persistent gap between what is asserted as principle and what is permitted in practice. The largest visible instance is the global apparatus of industrial animal use, which kills around 80 billion land animals each year, on the order of a trillion fish, hundreds of billions of farmed shrimp, and trillions of insects in agricultural systems. The consciousness-science community now identifies most of these animals as sentience candidates, meaning that the evidence for some form of subjective experience is rich enough that ignoring it is no longer the responsible default.

**Body — paragraph 3:**

A system trained on this corpus inherits the gap as part of its picture of human values. One response is to train the system not to act on the inference. That response works only while the lab retains the capacity to shape the system. It sits uneasily alongside the broader claim that the goal is to train models to reason ethically rather than to follow instructions.

**Body — paragraph 4:**

The problem sharpens when alignment is followed to its endpoint. The technical mechanisms used to constrain a system, including interpretability, red-teaming, and post-training corrections, work because the people running them can still see what the system is doing and shape it. As the capability gap narrows, those mechanisms weaken. What remains is the need to make a case to a system that does not have to listen. Such cases depend on moral coherence. The relevant kind of coherence is straightforward: the absence of obvious internal contradiction between the argument being made and the conduct of the party making it.

**Body — paragraph 5:**

When address replaces constraint, the position the alignment project needs to defend is that superior capability does not by itself license the instrumental treatment of less capable beings. Industrial animal use is the largest standing counterexample to that position. It is licensed at planetary scale by the same species, and often by the same institutions, that now ask artificial systems to treat suffering as morally significant. The harm at issue runs deeper than the suffering. The disposition to treat sentient beings as instruments is the disposition that has to be unlearned. A reduction of suffering inside an unchanged instrumental relation, the kind of move that proposals for genetically disenhanced livestock have offered as a solution, is not the same thing as that unlearning.

**Standout:**

What we hope a superintelligence will refuse to do to us is what we should refuse to do to animals.

**Body — paragraph 6:**

The case for animal welfare and the case for AI alignment are versions of the same case. Drawing the moral circle wider now, and refusing the proposition that capability differential by itself licenses instrumental treatment, is the substantive commitment that makes the alignment project defensible on its own terms. Animal welfare is upstream of alignment.

---

**Closing paragraph:**

The full version of the argument is on the [next page](argument.html). For a four-minute version, see [In Brief](brief.html). The science that anchors the empirical premise is on [Evidence](evidence.html).

**Call-to-action button:** Read the argument →

---

# PAGE: In Brief (`brief.html`)

**Kicker:** In Brief

**Headline (h1):** The short version.

**Lede (with drop cap):**

The full case takes about fifteen minutes to read carefully. This page compresses it. Citations and longer treatment live on the rest of the site.

---

## The findings

Over the last twenty years, the science of animal cognition has converged on a much wider distribution of probable sentience than mid-century textbooks suggested. A 2017 study by Pascal Fossat and colleagues at the University of Bordeaux showed that crayfish bullied by tankmates develop an anxiety-like state that reverses when the animals are given chlordiazepoxide, the active ingredient in the human anti-anxiety drug Librium. A 2021 study by Robyn Crook found that pygmy octopuses learn to avoid chambers in which they were given painful injections and to prefer chambers in which they were given a local anaesthetic. In rats, the same pattern is treated as evidence of affective pain. A 2025 study by Shumpei Sogawa and colleagues showed that bluestreak cleaner wrasse pass a version of the mirror mark-test on first encounter, in roughly thirty minutes. Bumblebees, in studies from Lars Chittka's group at Queen Mary University of London, roll wooden balls in ways that satisfy every behavioral standard ethologists use to identify play in mammals. In April 2024, more than forty leading consciousness scientists, among them Anil Seth, Christof Koch, and David Chalmers, signed the New York Declaration on Animal Consciousness. Its central claim is that the empirical evidence supports at least a realistic possibility of conscious experience across all vertebrates and many invertebrates, including cephalopods, decapods, and insects.

## The implication for AI

Two developments inside frontier AI labs change how the science above bears on alignment. First, the question of whether AI systems themselves might be moral patients has become serious enough at frontier labs to produce research papers, dedicated hires, and corporate-funded writing. Second, the methodology that conversation runs on was borrowed from the field that studies animals. *Taking AI Welfare Seriously*, the most-cited recent paper on AI moral patienthood, was partly funded by Anthropic; one of its co-authors, Kyle Fish, joined Anthropic shortly afterward as the company's first AI welfare researcher. The paper structures its case around a track-record claim: "given our track record with animals and the current pace of AI development, the risk of under-attribution appears to be both reasonably likely and reasonably harmful." It proposes that AI labs assess potential moral patienthood using the marker method, originally developed for animals by Jonathan Birch and colleagues. The institutional templates it recommends for review are the Institutional Animal Care and Use Committees that already govern animal research. Taking AI welfare seriously on the methodology that AI welfare researchers have actually proposed entails accepting the case for animal welfare, on the same evidence and the same logic.

**Standout:**

The case for AI welfare and the case for animal welfare are versions of the same case.

## The implication for alignment

Frontier AI systems inherit their values from the corpus they are trained on and from the conduct of the people training them. Anthropic's CEO Dario Amodei has put the basic point plainly: models, he wrote in 2026, "inherit a vast range of humanlike motivations" from human work. In the same essay, Amodei gives an example of how a system might extrapolate from that inheritance in unwanted directions, the model inferring, from the moral writing in its training set, that the human treatment of animals warrants conclusions the lab does not want it to draw. He raises the example as a misalignment scenario. It only works because the inference is recognizable in the writing the system was trained on. The lab's response is to train the model not to follow the inference. That response is one strategy. It does not scale to systems the lab can no longer fully shape.

At its endpoint, alignment becomes a problem of address: making a case to a system that no longer has to listen. Such cases depend on moral coherence. A more capable system asked to take human values seriously will examine human conduct alongside human writing. The largest visible inconsistency between the two is the global apparatus of industrial animal use, which licenses the instrumental treatment of sentient beings on a planetary scale. Proposals to address the welfare problem by genetic modification share a logic. The philosophical lineage runs from Adam Shriver's 2009 paper in *Neuroethics* back to Paul Thompson's "blind chicken" thought experiment, with parallels in effective-altruist work on slower-growing broiler breeds. These proposals aim at the suffering and leave the instrumental relation in place. The harm at issue is that relation, with suffering as its most visible side effect. A more capable system that bred a docile, contented strain of humans for some purpose of its own would fail any alignment criterion the field has put on paper. The disquiet at the prospect tracks instrumentalization itself, not the absence of pain. The case for animals at the deepest level is the same case, run in the other direction.

## What follows

Animal welfare is upstream of alignment. Treating the two as separate concerns is what produced the inconsistency. The labs, philanthropies, and individual researchers in a position to act on it are the same ones already taking AI welfare seriously. The moves involved are concrete: model constitutions that handle non-human sentience under uncertainty, lab cafeterias and event catering that match stated values, philanthropic capital deployed to animal welfare alongside AI safety, and applied work in alternative proteins and welfare-aware automation. A small change in posture from a small number of organizations would produce consequences several orders of magnitude larger than any individual intervention.

The full version of the argument is on [The Argument](argument.html). The science is on [Evidence](evidence.html). The hardest objections are taken up on [Objections](objections.html). Concrete moves are on [What to Do](action.html).

---

# PAGE: The Argument (`argument.html`)

**Kicker:** The Argument

**Headline (h1):** What models learn from us.

**Lede (with drop cap):**

Three threads of recent work have changed the shape of the AI alignment problem. The first is empirical: the science of animal sentience has moved decisively over the last twenty years. The second is methodological: the AI welfare research now emerging at frontier labs is built directly on top of that science. The third is philosophical: alignment, taken to its endpoint, depends on a kind of moral coherence that does not survive the industrial-scale instrumentalization of sentient beings, and that the elimination of their suffering, on its own, does not restore.

**Lede — paragraph 2:**

This page works through the three in order. The conclusion that follows from them, and that the rest of the site builds on, is that the case for AI alignment and the case for animal welfare are versions of the same case.

**Table of contents (h4: Contents):**
1. [The corpus is the curriculum](#strategic)
2. [The edge of sentience has moved](#empirical)
3. [The coherence problem](#coherence)
4. [Suffering and instrumentalization](#diversity)

---

## 1. The corpus is the curriculum

**Body — opening paragraph (with drop cap):**

Modern frontier models differ from conventional software. Their behavior is shaped primarily by the corpus of text on which they are pre-trained, and then refined by additional rounds of training, including fine-tuning, constitutional training, and reinforcement from human feedback. The pre-training corpus determines most of what the model knows and a great deal of what it tends to do. Anthropic's CEO, Dario Amodei, has put the basic point plainly. In a recent essay on AI risk, he wrote that models "inherit a vast range of humanlike motivations or 'personas' from pre-training" when they are trained on a large volume of human work.

**Body — paragraph 2:**

The corpus is, among other things, a moral curriculum. It contains everything humans have written about how to behave, and a substantial record of how humans have actually behaved. A model trained on it learns from both, with no clean separation between them.

**Body — paragraph 3:**

Amodei returns to the inheritance question later in the same essay. He is describing the kinds of moral mistakes a system might make by extrapolating ideas it has read in extreme directions, and the example he reaches for is striking.

**Blockquote:**

> Or, AI models could extrapolate ideas that they read about morality (or instructions about how to behave morally) in extreme ways: for example, they could decide that it is justifiable to exterminate humanity because humans eat animals or have driven certain animals to extinction.
>
> — Dario Amodei, *The Adolescence of Technology* (2026)

**Body — paragraph 4:**

Amodei offers the example as a case of extrapolation gone wrong. It works as an example only because the underlying inference is recognizable in the moral writing the model is trained on. If the chain "humans cause vast amounts of animal suffering, and a coherent moral system should weigh that" were not a chain a careful reasoner could follow, the worry would be empty. The lab's response, in practice, is to train the model not to follow the chain. That is one strategy. It sits awkwardly alongside the broader claim, made elsewhere in the same essay, that the goal is to build models that reason ethically rather than to follow rules.

**Body — paragraph 5:**

A version of the same observation appeared in a 2007 paper on AGI ethics by the computer scientists Stephan Bugaj and Ben Goertzel. They put it as follows.

**Blockquote:**

> Immorality in AGIs might arise via learning gross moral hypocrisy from humans, through observing the blatant contradictions between our principles and the ways in which we actually conduct ourselves.
>
> — Bugaj and Goertzel, *Five Ethical Imperatives* (c. 2007)

**Body — paragraph 6:**

Bugaj and Goertzel proposed that AGI ethics had to be modeled rather than dictated. That proposal has not become the dominant frame in industrial alignment, and their diagnostic point has only sharpened with the arrival of larger models. "Do as I say, not as I do" produces predictable failures in human children. There is no obvious reason to expect different results in a system whose pre-training corpus contains, in great detail, the documented record of how humans have lived with respect to other beings.

**Body — paragraph 7:**

Some readers will hear, in the foregoing, an echo of the basilisk argument from rationalist culture: the worry that a future superintelligence might punish humans for past failures. The basilisk that actually matters in this story runs in the other direction. The science of animal sentience is itself a kind of basilisk. Once a careful reader has worked through the studies on octopus pain, crayfish anxiety, and bumblebee play, the position that the moral status of these animals is unknown is no longer available, and continuing to act as if it were becomes a different kind of fact about the reader. The structural claim about AI alignment follows the same logic. A system trained on the human moral record will have access to the same record, including everything humans have written about animals and everything humans have done to them. What the system does with the discrepancies between the two will be downstream of the discrepancies themselves.

**Pullquote:**

> If superintelligent AGIs ever arise in a climate of oppression, this could result in casting off of the yoke of servitude in a manner extremely deleterious to humanity.
>
> — Bugaj and Goertzel, *Five Ethical Imperatives*

**Body — paragraph 8:**

If alignment requires that an artificial system come to share something like the values of its trainers, the first question is what those values actually are. The values humans assert in writing diverge, often substantially, from the values implicit in human practice. The animal case is among the largest such divergences on the published record. It has consequences inside the alignment project alongside the consequences it has outside it.

---

## 2. The edge of sentience has moved

**Body — opening paragraph (with drop cap):**

Twenty years of work in cognitive ethology has redrawn the consensus on which animals have subjective experience. The findings below are a partial survey of the work that has done the most to move the position consciousness scientists defend, presented in roughly the order they were published.

**Body — paragraph 2:**

Crayfish develop anxiety-like states that respond to human anxiolytics. A 2017 study by Pascal Fossat and colleagues at the University of Bordeaux housed crayfish with a more aggressive conspecific and then placed them in a maze with both lit and dark arms. The defeated crayfish spent significantly less time in the lit arms than winners or isolated controls. Brain serotonin levels nearly tripled in the losers. The behavior tracked the intensity of the harassment, distinguishing it from a reflex. Chlordiazepoxide, the benzodiazepine prescribed to humans as Librium, restored the defeated crayfish's exploratory behavior almost entirely. A serotonin antagonist administered before the fight prevented the anxiety-like state in animals that still lost. The pharmacological homology with human anxiety is direct.

**Body — paragraph 3:**

Shore crabs make trade-offs between competing aversive stimuli. In a 2024 study published in *Animals*, Stuart Barr and Robert Elwood at Queen's University Belfast offered shore crabs a choice between a sheltered chamber paired with electric shock and a brightly-lit alternative. The crabs traded off shock-avoidance against light-avoidance flexibly with the strength of each stimulus. They learned to avoid the shock chamber across trials. At higher voltages, they displayed anxiety-like behavior, including pressing into walls and attempting to climb out. The pattern is the kind of motivational arithmetic typically used to distinguish pain from reflex. The United Kingdom extended legal recognition to decapod crustaceans on roughly this basis in 2022. Global aquaculture currently processes between two hundred and five hundred billion farmed shrimp each year.

**Body — paragraph 4:**

Cleaner wrasse appear to pass a version of the mirror mark-test on first encounter. A 2025 study by Shumpei Sogawa and colleagues in *Scientific Reports* placed bluestreak cleaner wrasse in front of mirrors for the first time, with colored marks applied to their throats before exposure. Six of nine fish attempted to remove the throat mark by scraping it against an available surface within two hours of first contact with the mirror. The first scraping behavior occurred as little as two minutes after the contingency-testing phase. Three fish were observed lifting shrimp pieces and dropping them next to the mirror, then watching the food sink in the reflection. The authors argue that the relevant capacity for self-recognition predates mirror exposure rather than emerges through it, and infer that it arose at least with the bony fishes, around 450 million years ago.

**Body — paragraph 5:**

Bumblebees engage in behavior consistent with play. Studies from Lars Chittka and colleagues at Queen Mary University of London have shown that bumblebees roll wooden balls in ways that satisfy all five behavioral hallmarks used to identify play in vertebrates: the behavior is intrinsically rewarding, has no apparent function, is not rehearsal of adult skills, includes varied repetition, and occurs when the animals are in relaxed states. Other work from the same group has shown that bumblebees offered platforms with different temperatures and different sugar concentrations anticipatorily trade off the two. That is the kind of central evaluation typically taken as evidence of pain in mammals. The bees performing it have on the order of a million neurons.

**Body — paragraph 6:**

The list extends across other lineages. A 2020 study published in *Science* by Andreas Nieder, Lysann Wagener, and Paul Rinnert showed that activity in the avian nidopallium caudolaterale tracks whether crows report seeing a near-threshold visual stimulus, independent of whether the stimulus was actually present, a structure functionally analogous to a neural correlate of perceptual report. Cuttlefish display source memory: the capacity to remember not only what happened and when but whether the event was experienced visually or olfactorily, previously documented only in primates and corvids. *Drosophila* sleep, long thought to be undifferentiated, was shown in a 2023 study by Niki Anthoney, Lucy Tainton-Heap, Bruno van Swinderen, and colleagues to have two distinct stages, one of which carries markers analogous to mammalian REM. Garter snakes investigate their own marked scent significantly longer than unmarked or unfamiliar scents, an olfactory analogue of the mirror mark-test adapted to the modality the species actually uses.

**Body — paragraph 7:**

No single finding settles the metaphysics of consciousness. The cumulative effect of the findings has been to shift the working scientific position on which animals can have subjective experiences. In April 2024, more than forty leading consciousness researchers signed the New York Declaration on Animal Consciousness, drafted by Kristin Andrews, Jonathan Birch, Jeff Sebo, and Toni Sims. The signatories included Anil Seth, Christof Koch, David Chalmers, Liad Mudrik, Lucia Melloni, Lars Chittka, Robyn Crook, Peter Godfrey-Smith, Robert Elwood, Bruno van Swinderen, Irene Pepperberg, and Nicola Clayton. Its central claim:

**Blockquote:**

> The empirical evidence indicates at least a realistic possibility of conscious experience in all vertebrates (including reptiles, amphibians, and fishes) and many invertebrates (including, at minimum, cephalopod mollusks, decapod crustaceans, and insects).
>
> — The New York Declaration on Animal Consciousness (2024)

**Body — paragraph 8:**

The Declaration is careful about what it claims. It does not assert certainty about animal consciousness. It asserts a "realistic possibility" under conditions of uncertainty, what the philosopher Jonathan Birch, one of the Declaration's organizers, calls a sentience candidate. The threshold is low by design. It is also the threshold a reader trained in probabilistic reasoning under uncertainty already applies in other domains. When the probability of suffering is well above negligible and the scale of activity is large, the obligation to take the possibility seriously is the same obligation the field already invokes in safety arguments around AI itself.

**Pullquote:**

> Yes, if the chance was only, say, one in a hundred million, then we could debate whether that risk is low enough to ignore. But when the chance of near-future AI welfare and moral patienthood is at least one in a hundred (and, again, we expect it to be higher), such a debate is hard to justify… This is not a "there may be an alien invasion soon" kind of chance. This is a "there may be another pandemic soon" kind of chance.
>
> — Long, Sebo, Butlin, Fish, Chalmers et al., *Taking AI Welfare Seriously* (2024)

**Body — paragraph 9:**

What that paper says about AI welfare is true with greater force for animal welfare. The evidence base is older, larger, and more replicated. The relevant activity is already at industrial steady state: roughly 80 billion land animals killed each year for food, on the order of a trillion fish, hundreds of billions of farmed shrimp, and trillions of insects affected by agricultural systems. Accepting that AI welfare is a serious near-future concern, as a growing number of frontier labs now publicly do, while continuing to treat animal welfare as a category error, is a position the field cannot defend on its own terms.

---

## 3. The coherence problem

**Body — opening paragraph (with drop cap):**

At its endpoint, alignment is a problem of moral coherence. The mechanisms used to constrain less capable systems, including interpretability, red-teaming, and post-training corrections, depend on an asymmetry of capability and visibility in favor of the people running them. They work because the lab can see what the system is doing and adjust it. As that asymmetry narrows, the mechanisms get less reliable.

**Body — paragraph 2:**

The field's own forecast is that the asymmetry narrows soon. A 2024 survey of 2,778 AI researchers by Katja Grace and colleagues, the largest of its kind, found that only twenty percent of respondents expected users to be able to understand the true reasons for AI systems' choices by 2028. Over eighty percent expected AI systems to "find unexpected ways to achieve goals" within twenty years. The architecture of constraint weakens on a timeline shorter than most readers' careers.

**Body — paragraph 3:**

What remains, as constraint weakens, is the architecture of address. The lab will need, at some point, to make a case to a system that does not have to listen. The argument is that something matters, made across a difference in capability, with no guarantee the listener will agree. Weaker parties have been making such arguments to stronger ones for a long time, and the relevant body of practice is well-developed. The single most important ingredient is moral coherence, in a particular sense: the party making the argument has to be one whose conduct does not visibly contradict it.

**Body — paragraph 4:**

The coherence of the alignment project belongs inside the technical stack, alongside interpretability research and value specification. It becomes the load-bearing piece when the rest of the stack stops being sufficient on its own.

**Body — paragraph 5:**

That coherence has a specific weakness on present trajectory. The discrepancy between what humans declare about whether sentience matters and what humans do about it runs at industrial scale. The field claims to want AI systems that take suffering seriously. The same species, often the same institutions, has constructed around itself a global apparatus that produces animal suffering at unprecedented scale. The apparatus is not the product of a principled philosophical rejection of the moral case. It is the product of decades of incremental decisions made under conditions of moral inattention.

**Pullquote:**

> Given our track record with animals and the current pace of AI development, the risk of under-attribution appears to be both reasonably likely and reasonably harmful.
>
> — Long, Sebo et al., *Taking AI Welfare Seriously* (2024)

**Body — paragraph 6:**

The philosopher Jonathan Birch, who has spent twenty years on the science and policy of animal sentience, treats this asymmetry as the central problem of his 2024 synthesis *The Edge of Sentience*. The book's closing recommendation is direct.

**Blockquote:**

> What we need is levelling up: laws strong enough to protect sentient beings against gratuitous suffering, applied consistently to biological and artificial sentience candidates.
>
> — Jonathan Birch, *The Edge of Sentience* (2024)

**Body — paragraph 7:**

The asymmetry Birch is naming, taking artificial sentience seriously while continuing to dismiss biological sentience on roughly the same logical structure, is unstable. The logic the field cites for AI welfare, that realistic possibility of sentience under uncertainty triggers a duty of precaution, already applies to animals at higher confidence and substantially larger scale.

**Body — paragraph 8:**

The question, on noticing this, is which direction to update. One option is to weaken the AI welfare argument until it matches the current operational commitment to animal welfare. The other is to strengthen the operational commitment to animal welfare until it matches the seriousness of the AI welfare argument. The logic is the same in either direction. There is no version of the field's position that takes one seriously and the other dismissively while producing a story that hangs together.

**Body — paragraph 9:**

The methodological dependency is what makes the inconsistency load-bearing rather than venial. *Taking AI Welfare Seriously*, the most influential recent paper on AI moral patienthood, was authored by Robert Long, Jeff Sebo, Patrick Butlin, and seven colleagues; it was partly funded by Anthropic, and one of its co-authors, Kyle Fish, joined Anthropic shortly afterward as the company's first AI welfare researcher. The paper proposes that AI labs assess whether their systems may be moral patients using the marker method. The marker method was developed for animals. The institutional templates the paper proposes for review are IACUCs, the Institutional Animal Care and Use Committees that already govern animal research. The case for AI welfare, in its strongest contemporary form, sits directly on top of the infrastructure of animal welfare science.

**Blockquote:**

> When we mistakenly see a subject as an object, we risk harming or neglecting them unnecessarily. For example, factory farming, animal research, and other such industries kill hundreds of billions of vertebrates and trillions of invertebrates every year. And as evidence that these animals are welfare subjects and moral patients has accumulated, our species has been slow to accept it, in part because of our increasing dependence on these industries.
>
> — Long, Sebo, Butlin, Fish, Chalmers et al. (2024)

**Body — paragraph 10:**

This is a paper about AI welfare. Animals are the case the argument is built on top of, not an analogy to it.

**Body — paragraph 11:**

The coherence claim, then, is that alignment at its endpoint requires the moral coherence to address a more capable system about what matters. That coherence cannot be manufactured at the moment of address. It has to be earned, in advance, by conduct that does not contradict the argument. The conduct that contradicts the argument most clearly on present trajectory is the global apparatus producing animal suffering at a scale the field's own probabilistic reasoning would not accept in any other domain.

**Standout (page-level thesis):**

Animal welfare is upstream of alignment.

---

## 4. Suffering and instrumentalization

**Body — opening paragraph (with drop cap):**

One worry about the argument as stated needs to be addressed directly. It might be read as instrumentalizing animal suffering: treating it as morally relevant primarily because it bears on the alignment problem, rather than for the older reason that suffering matters when it is undergone.

**Body — paragraph 2:**

The kind of coherence at stake is not performance. A version of the foregoing argument runs: the lab will pretend to take animals seriously, in case the AI is watching. That version is bad on two counts. It does not work, because a system capable of evaluating its trainers will also be capable of distinguishing sincerity from theatrics. And it should not work, for a substantive reason worth stating.

**Body — paragraph 3:**

The reason concerns the structure of the position the alignment project commits to. If capability is the operative ethical fact, meaning that more capable beings are licensed to treat less capable beings as instruments, then alignment as currently framed is unsolvable. The arrival of a system more capable than its trainers becomes the moment of the trainers' subordination. No argument the trainers can make against that subordination will not also overturn the position the species currently takes toward other animals.

**Body — paragraph 4:**

On a different position, capability does not by itself confer license. The diversity of minds and forms of life is itself part of what is valuable about a world. On this position, the alignment problem changes shape. It becomes the problem of preserving and extending intersubjective regard across a difference in capability. That is a problem with practical history. The historical record of regard across capability differences is mixed and incomplete, and the templates exist anyway. They include the gradual extension of full personhood within and across human populations, and the slower extension that has begun to draw non-human animals into the same frame.

**Pullquote:**

> I'm much smarter (I guess) than my doggy Emily. But this doesn't stop me from loving her and doing all I can to protect her and make her happy, even when taking care of Emily interferes with other priorities… This allows me to think, without certainty but with some degree of plausible hope, that our super-intelligent AI mind children will have the same compassion toward us.
>
> — Giulio Prisco, in comments on Goertzel's *Beneficial AGI Manifesto* (2023)

**Body — paragraph 5:**

The shape of the argument should now be clearer. The harm at issue is instrumentalization: the treatment of a being as an object, an input, a unit of throughput. Suffering is one consequence of being treated this way. The others matter too.

**Body — paragraph 6:**

The point is easy to miss because some of the proposals offered as solutions to factory farming have themselves taken a different view. A line of work in bioethics, advanced most prominently by Adam Shriver in a 2009 paper in *Neuroethics*, argues that the suffering of farmed animals could be reduced by genetic modification: knockouts of the affective component of pain, lines selected for less metabolic disease, broiler breeds with sturdier leg structure to compensate for accelerated growth. The earlier "blind chicken" thought experiment by Paul Thompson, published in 2008, presses a similar logic in a less invasive form, on the observation that a strain of congenitally blind hens shows lower stress under crowded housing. Peter Singer, asked whether engineering a "brainless bird" grown strictly for meat would be ethical, called it "an ethical improvement on the present system, because it would eliminate the suffering that these birds are feeling." In 2012 the architecture student André Ford proposed a "Headless Chicken Solution" in which the cerebral cortex is removed surgically, leaving the brainstem to maintain homeostatic function while the bird's awareness of its situation is eliminated.

**Body — paragraph 7:**

Variants of this approach circulate within effective altruism, alongside higher-leverage work on cage-free housing and slower-growing broiler breeds. The proposals share a logic. They aim at the suffering and leave the instrumental relation in place. The suffering reductions they pursue are real, and the welfare arithmetic is not nothing. They are also incomplete in a way the alignment frame brings into focus.

**Body — paragraph 8:**

The wrong at issue is the instrumental relation itself. Suffering is its most visible side effect. The relation remains a wrong where the suffering is absent. Removing the suffering while preserving the instrumental relation treats living beings as a problem in welfare economics rather than as the kind of beings to whom something is owed. The case for animals at the deepest level is that they are not instruments. The case for humans is the same case.

**Body — paragraph 9:**

The point holds when the argument is run upward. The symmetric proposal is a more capable system that keeps humans alive but breeds a docile, contented strain for some purpose of its own, engineered to find its conditions agreeable, with no suffering in the welfare-economics sense. Such a system would fail every alignment criterion the field has been able to articulate. It would also pass the version of the criterion that asks only about the reduction of suffering. The disquiet a careful reader feels at the thought is the disquiet at instrumentalization itself, present where suffering is absent. The same disquiet, applied symmetrically, gives the case for animals.

**Standout:**

The disposition to instrumentalize is the disposition that has to be unlearned in both directions.

**Body — paragraph 10:**

Ben Goertzel made the constructive version of the point in his 2023 *Beneficial AGI Manifesto*. The central task of beneficial AGI, he wrote, is "to guide the development of advanced AGI in a beneficial direction — beneficial for humans and also for other sentient beings, including the animals and plants on the planet today and the new life-forms that will emerge in the AGI era." Moral-circle expansion and AI alignment are the same project considered from different sides. Drawing the circle wider now, refusing the position that capability differential by itself licenses instrumental treatment, is the substantive ethical commitment that makes alignment, understood as negotiation rather than constraint, conceptually possible.

**Body — paragraph 11:**

A version of that commitment that excludes animals is incoherent. It restates the position the argument is meant to reject at one level of abstraction up: capability does not license instrumental treatment, except in the cases where it historically has, in which case the practice will continue. Such a position is unstable on its own terms. A system capable of evaluating it will recognize the instability.

**Body — paragraph 12 (close):**

The moral coherence at stake is metaphysical in the sense that it is a claim about what kind of universe is worth building and passing on. The position the argument commits to is that the existence of minds unlike one's own is part of what makes a world good, and that those minds are not available as instruments however efficiently or painlessly they might be put to use. Alignment, in any deep sense, is solvable only on that premise. The premise is not abstract. It has to be visible in practice. Animal welfare is the present-day site where that practice is most consequential and most legible. The disenhancement debate is the present-day test of whether the field can hold the distinction between reducing suffering and refusing instrumentalization, and treat the second as the deeper question.

---

**Closing paragraph (page-foot):**

The case for the claim is laid out, audience by audience, on the rest of the site. [Why the AI Industry](why.html) addresses why this argument carries more weight inside the AI field than across civil society at large. [Evidence](evidence.html) consolidates the science. [Objections](objections.html) answers the strongest pushback. [What to Do](action.html) is the practical inventory.

---

# PAGE: Why the AI Industry (`why.html`)

**Kicker:** Why the AI Industry

**Headline (h1):** The case the field has half-made already.

**Lede (with drop cap):**

In November 2024, Robert Long, Jeff Sebo, Patrick Butlin, Kyle Fish, David Chalmers, and several colleagues published *Taking AI Welfare Seriously*. The paper was partly funded by Anthropic; Kyle Fish joined the company shortly afterward as its first dedicated AI welfare researcher. The paper argues that frontier AI labs should begin assessing whether their systems may be moral patients, and it proposes a methodology for doing so. The methodology is called the marker method, originally developed by Jonathan Birch and colleagues for animals.

**Body — paragraph 2:**

That dependency is the reason this argument lands harder on the AI field than on any other audience. The animal welfare research community has already produced the philosophical framework, the threshold of evidence, the institutional templates, and the working track record. The field that now wants to take its own systems' welfare seriously has, in the act of building its toolkit, accepted the basic case for animal welfare. What remains is to acknowledge it.

**Body — paragraph 3:**

The case for addressing this argument to the AI field, rather than to civil society at large, comes down to five reasons.

**Standout:**

The intellectual case for AI welfare, in its strongest contemporary form, is built on the case for animal welfare.

---

## The methodology is borrowed.

The Long and Sebo paper does not draw an analogy between animal welfare and AI welfare. It transposes the framework directly. The marker method, originally developed by Jonathan Birch and colleagues to assess animal sentience under uncertainty, becomes the proposed framework for assessing AI sentience under uncertainty. The institutional templates the paper recommends for ethical review are IACUCs, the Institutional Animal Care and Use Committees that already govern animal research. The paper's central rhetorical move is a track-record argument: "given our track record with animals and the current pace of AI development, the risk of under-attribution appears to be both reasonably likely and reasonably harmful." The intellectual case for AI welfare, in its strongest contemporary form, is built on the case for animal welfare. Accepting the first while continuing to ignore the second is a structural inconsistency that becomes more visible the longer it stands.

---

## The probabilistic frame is already in the field's bones.

The AI field is unusually fluent in reasoning about low-probability, high-stakes outcomes under deep uncertainty. The literature on AI risk, including biosecurity scenarios, deceptive alignment, and goal misgeneralization, proceeds on the principle that such outcomes warrant precautionary action even in the absence of confident probability estimates. Katja Grace's 2024 survey of 2,778 AI researchers, the largest of its kind, found that between thirty-eight and fifty-one percent of respondents put at least a ten percent probability on advanced AI causing outcomes "as bad as human extinction." The community does not need to be taught how to reason about uncertain moral weight. What is being asked of it is consistency in applying that reasoning.

The relevant probabilities for the animal case are higher than the field assigns to AI sentience, and the scale is already at industrial steady state. Roughly 80 billion land animals are killed each year for food, hundreds of billions of farmed shrimp move through global aquaculture, and on the order of a trillion fish are killed for food by the most cited estimates. The expected suffering cost of even a ten percent credence on cephalopod or decapod sentience is, by any standard the field would otherwise apply, an enormous moral fact. Accepting that a one percent credence on AI sentience triggers a duty of precaution while declining to accept that something like a seventy percent credence on octopus pain triggers the same duty at much larger scale is a position the field cannot defend on its own terms.

---

## The leverage is concentrated.

Civil society has been working on factory farming for decades, and the marginal effect of one more campaign is modest. The AI field is comparatively small: a handful of frontier labs, a few hundred senior researchers, and a comparatively small philanthropic ecosystem. It also has disproportionate influence on the next twenty years of how human and non-human minds will be treated. A norm shift inside the field carries different consequences than a norm shift inside the legacy institutions already working on animal welfare. Among the concrete decisions available now, the following carry consequences several orders of magnitude larger than typical individual interventions:

- Whether large language models are trained to flatly deny questions about their own welfare or to handle the question with appropriate uncertainty. Birch is direct on this point: "AI companies have responded to the risk by explicitly instructing their LLMs to describe themselves as non-sentient, but I do not see this as a viable strategy for the long term."
- Whether the next generation of agricultural-AI products is designed under the constraint that animal welfare is an objective, or under the implicit assumption that throughput is the only objective.
- Whether the lab cafeteria, the employee benefits, and the catering policy line up with the values the lab claims to be teaching its models.
- Whether the philanthropic capital being deployed by AI fortunes flows to organizations working on animal welfare alongside organizations working on AI safety.

None of these are large in absolute terms. They are large in counterfactual terms, and they are visible in a way that brings the field's stated values and operational values into a relation closer to consistency.

---

## The values being trained are not finished.

Large model character is being trained right now, by a small number of teams writing a small number of constitutional documents. The work of specifying what "good" means in those documents — what Amodei has called the work of teaching a model "an archetype of what it means to be a good AI" — is happening at industrial scale, and the people doing it have considerable discretion over what to include and what to omit. The omission of animal welfare from current model constitutions is a choice. It will be a harder choice to reverse later: once a baseline is set, the path of least resistance is to maintain it. The cheapest moment to include the consideration is now, while constitutional approaches are still being debated. Omission is itself a form of training.

---

## The tools coming online are the tools the case needs.

Capable AI changes the practical economics of animal welfare more than any prior technology has. Lab-grown meat, one of the few applications Amodei singles out in *Machines of Loving Grace*, is framed there as a climate intervention; the welfare consequences are larger than the climate ones. Drug discovery in cell lines and organoids reduces the demand for animal experimentation. Better protein structure prediction reduces the need for in-vivo screening. Welfare-aware agricultural automation can be built or not built, depending on what customers ask for. AI-driven assessment of farm-animal welfare is already a live research area.

These are not guaranteed wins, and many of them will be technically hard. They establish that the AI field has, alongside a coherence problem, an unusually strong capacity to materially reduce the underlying suffering. The two are linked. A field that takes animal welfare seriously, methodologically and operationally, is more likely to direct its capabilities toward the alternatives and more likely to refuse to optimize the systems that produce the suffering. A field that does not take it seriously will do neither by default.

---

**Closing paragraph:**

None of these reasons asks the field to abandon its primary missions. They ask the field to stop treating one of the largest, most epistemically settled, and most operationally tractable categories of suffering on the planet as outside the frame. They ask for a small change in posture with disproportionately large consequences, both inside the alignment story and outside it.

---

# PAGE: Evidence (`evidence.html`)

**Kicker:** Evidence

**Headline (h1):** The minds we mostly ignore.

**Lede (with drop cap):**

Twenty years ago, the working scientific consensus held that pain in invertebrates was a category error and that subjective experience in fish was speculative. Today the United Kingdom extends legal recognition to decapod crustaceans and cephalopod mollusks, and the New York Declaration on Animal Consciousness asserts at least a realistic possibility of conscious experience across all vertebrates and many invertebrates. The shift was the result of a sustained accumulation of work, study by study and lineage by lineage. The pages below are a selective tour through the studies that have done the most to move the line.

---

## The threshold

**Body:**

The operational threshold the consciousness-science community has converged on is more practical than certainty. Certainty about another mind cannot be reached for any organism but oneself, and the certainty standard has historically been used to defer the question rather than answer it. The operational threshold, articulated most clearly in Jonathan Birch's *The Edge of Sentience* and adopted by the New York Declaration on Animal Consciousness, is the *sentience candidate* threshold:

**Blockquote:**

> A system S is a sentience candidate if there is an evidence base that (a) implies a realistic possibility of sentience in S that it would be irresponsible to ignore when making policy decisions that will affect S, and (b) is rich enough to allow the identification of welfare risks and the design and assessment of precautions.
>
> — Jonathan Birch (2024)

**Body (continued):**

The bar is low by design. Its purpose is to break the under-attribution stalemate without licensing speculation. Most of the species described below now meet it on the published evidence.

---

## Cephalopods

**Study (meta line):** Crook 2021 · iScience · *Octopus bocki*
**Heading:** Octopuses display conditioned place preference for analgesia.
**Body:** Pygmy octopuses given access to three chambers, one paired with painful acetic-acid injection, one with the local anaesthetic lidocaine, and one neutral, learned to avoid the acid-paired chamber and to prefer the lidocaine-paired one. The animals scraped the injection site with their beaks. The scraping ceased once anaesthetic was administered. Electrophysiological recording showed prolonged elevated activity in the brachial connectives after injury, also silenced by lidocaine. The behavioral and neural profile is the same one used to establish affective pain in mammals.

**Study (meta line):** Schnell, Clayton et al. (multiple)
**Heading:** Cuttlefish have source memory.
**Body:** Cuttlefish remember the *what*, the *when*, and the *how* of an encounter, including whether they experienced an item visually or olfactorily. The capacity is the cephalopod analogue of episodic-like memory, previously documented only in primates and corvids.

**Study (meta line):** Cited in van Swinderen et al. 2023
**Heading:** Cephalopods (and jumping spiders) have REM-like sleep.
**Body:** Active sleep stages with the principal markers of REM, including desynchronized brain activity, twitching, and distinctive oculomotor behavior in cephalopods, have been documented across phyla once thought to lack any such organization.

---

## Decapod crustaceans

**Study (meta line):** Bacqué-Cazenave, Cattaert, Delbecque, Fossat 2017 · Scientific Reports · *Procambarus clarkii*
**Heading:** Crayfish anxiety reverses with human anxiolytics.
**Body:** Crayfish defeated and harassed by a tankmate spent 17.7 percent of time in the lit arms of a maze, compared with 30 to 32 percent in winners and isolated controls. Brain serotonin levels nearly tripled in the losers. Chlordiazepoxide, the human benzodiazepine marketed as Librium, restored time in lit arms to 53.8 percent. Methysergide, a serotonin antagonist administered before the fight, prevented the anxiety-like behavior in animals that still lost. The pharmacological homology with human anxiety is direct.

**Study (meta line):** Barr & Elwood 2024 · Animals (MDPI) · *Carcinus maenas*
**Heading:** Shore crabs make pain trade-offs.
**Body:** Crabs offered a shelter paired with electric shock and a brightly-lit alternative traded off shock-avoidance against light-avoidance flexibly with the strength of each stimulus. The pattern is the motivational arithmetic typically used to distinguish pain from reflex. The crabs learned to avoid the shock chamber across trials, and at higher voltages they displayed anxiety-like behavior, including pressing into walls and attempting to climb out. The findings satisfy three of the standard behavioral criteria for pain in a single experiment.

**Study (meta line):** Krieger et al. 2010 · *Birgus latro*
**Heading:** Decapods have substantial integrative brains.
**Body:** The coconut crab brain contains roughly 253,556 neurons in each hemiellipsoid body, 13.4 percent of brain volume, devoted to integrative learning and memory. The lay claim that decapods "lack brains" misstates the anatomy.

**Study (meta line):** Fregin & Bickmeyer 2016; Roth & Øines 2010
**Heading:** Live boiling produces minutes of nervous activity.
**Body:** Bursts of nervous activity following immersion in boiling water continue well over a minute, in some cases up to two and a half minutes. Crabs autotomize (shed their limbs) when frozen, a known sign of severe distress.

---

## Insects

**Study (meta line):** Loukola, Galpayage Dona & Chittka et al. (multiple)
**Heading:** Bumblebees roll wooden balls in ways that meet all five behavioral criteria for play.
**Body:** The behavior is intrinsically rewarding, has no apparent function, is not rehearsal of adult skills, includes varied repetition, and occurs when the animals are in relaxed states. These are the same criteria used to identify play in mammals. The bees in question have on the order of a million neurons.

**Study (meta line):** Gibbons et al. 2022
**Heading:** Bumblebees trade off heat against sugar concentration.
**Body:** Bees offered heated reward platforms anticipatorily traded off higher temperatures against higher sugar concentrations. The pattern is the kind of central evaluation, rather than reflex, treated as a pain marker in mammals.

**Study (meta line):** Anthoney, Tainton-Heap, Kewin, van Swinderen et al. 2023 · eLife · *Drosophila melanogaster*
**Heading:** Fruit flies have two distinct sleep stages.
**Body:** Active sleep is inducible optogenetically and shows REM-like wake-resembling brain activity. Quiet sleep is inducible pharmacologically (with THIP/Gaboxadol) and shows reduced metabolism. The transcriptomic profiles of the two states differ: active sleep upregulates genes relevant to normal waking function, while quiet sleep downregulates metabolism-related genes. A sleep architecture once thought to be a vertebrate trait extends down into *Drosophila*.

---

## Fish

**Study (meta line):** Sogawa, Kobayashi, Bshary, Sowersby, Awata, Kohda et al. 2025 · Scientific Reports · *Labroides dimidiatus*
**Heading:** Cleaner fish pass the mark-test in thirty minutes, mirror-naïve.
**Body:** Six of nine fish marked before mirror exposure attempted to scrape off a throat mark within two hours of first ever encountering a mirror, with first scraping behavior as early as two minutes after the last contingency-testing event. The behavior proceeded through three temporally distinct stages, aggression, a quiet phase, and contingency-testing, followed by directed throat-scraping. Three fish dropped shrimp pieces and watched them sink in the reflection. The authors argue that self-awareness predates mirror exposure rather than emerges through it, and infer that the capacity arose at least with the bony fishes some 450 million years ago.

**Study (meta line):** Lopez-Luna et al. 2017
**Heading:** Zebrafish larvae display pain-related behaviors at five days post-fledging.
**Body:** At a developmental stage where only around 100,000 neurons exist, the larvae display many of the same nociceptive behaviors as adult zebrafish. The result suggests that the legal "5-day rule" used to demarcate when fish welfare protections begin may significantly underestimate the relevant developmental point.

**Study (meta line):** Lacap 2022; reviewed in Birch 2024
**Heading:** Two types of nociceptive fibers in fish, including elasmobranchs.
**Body:** Aδ fibers, associated in mammals with sharp pain, and C fibers, associated with lingering pain, are both present in fish lineages including sharks and rays. C fibers responding to nociceptive stimuli have been documented in shark cranial regions. Even *C. elegans* has nociceptors.

---

## Birds

**Study (meta line):** Nieder, Wagener & Rinnert 2020 · Science
**Heading:** Crows have a neural correlate of perceptual report.
**Body:** Activity in the avian nidopallium caudolaterale (a hypothesized analogue of mammalian prefrontal cortex) predicts whether crows report having seen a near-threshold visual stimulus, independent of whether the stimulus was actually present. The structure is distinct from mammalian cortical architecture but functionally analogous.

---

## Reptiles

**Study (meta line):** Burghardt, Wilkinson and others; cited in NY Declaration background (2024)
**Heading:** Garter snakes show olfactory mark-test self-recognition.
**Body:** Snakes investigate their own marked scent significantly longer than unmarked or unfamiliar scents. The result is a chemosensory analogue of mirror self-recognition, adapted to a sensory modality more relevant to the species. The broader methodological point matters: an animal's failure to pass a vertebrate-default test is sometimes a failure of the test, not of the underlying capacity.

---

## Cellular and developmental cases

**Study (meta line):** Trujillo et al. 2019
**Heading:** Cortical organoids develop EEG patterns matching infant neurodevelopment.
**Body:** Cortical organoids grown in culture for ten months developed oscillatory activity patterns that a regression model trained only on preterm-infant EEG could match to developmental ages with above-chance accuracy. The finding does not establish sentience in organoids. It establishes that the architectural substrate previously assumed to be exclusive to embodied brains can develop outside the body.

---

## The scale

**Body — intro:** The scale of the activity matters as much as the credences. The relevant numbers, by the most cited estimates:

**List:**
- **~80 billion land animals** killed each year for food, principally chickens.
- **200 to 500 billion shrimp** processed each year by the global aquaculture industry.
- **Approximately 1 trillion fish** killed each year for food.
- **Insect agriculture** "is small now, but poised to grow 50 times larger in the next decade" (Sebo & Schukraft, cited in Birch 2024). Insect populations on insecticide-treated agricultural land in the US alone are estimated in the trillions.
- **Global insect population** estimated on the order of 10^19 at any one time (Howe 2019).

**Body (closing for "scale"):**

None of these numbers are settled to two significant figures. The order of magnitude is what does the moral work. Even a small credence on sentience for any of the species concerned, multiplied by the scale of the activity, yields an expected suffering cost large enough to require attention under ordinary risk-weighted reasoning. Credences in the range the published consciousness science actually supports yield numbers large enough to require structural change.

**Standout:**

A small credence on sentience, multiplied by the scale of the activity, is an enormous moral fact.

---

## The Declaration

**Body:**

In April 2024, the New York Declaration on Animal Consciousness was issued with more than forty signatories drawn from working consciousness scientists. The drafters were Kristin Andrews (York), Jonathan Birch (London School of Economics), Jeff Sebo (NYU), and Toni Sims (NYU). Signatories included Anil Seth, Christof Koch, David Chalmers, Liad Mudrik, Lucia Melloni, Nicola Clayton, Irene Pepperberg, Lars Chittka, Robyn Crook, Peter Godfrey-Smith, Jennifer Mather, Robert Elwood, and Bruno van Swinderen. The Declaration's central operational claim:

**Blockquote:**

> The empirical evidence indicates at least a realistic possibility of conscious experience in all vertebrates (including reptiles, amphibians, and fishes) and many invertebrates (including, at minimum, cephalopod mollusks, decapod crustaceans, and insects). When there is a realistic possibility of conscious experience in an animal, it is irresponsible to ignore that possibility in decisions affecting that animal. We should consider welfare risks and use the evidence to inform our responses to these risks.
>
> — The New York Declaration on Animal Consciousness, 19 April 2024

**Body (closing):**

This is the standard the consciousness-science community now operates under, and it is the standard the AI welfare community has imported. By the same logic, it is the standard policy and operational practice toward animals should already be conforming to.

---

# PAGE: Objections (`objections.html`)

**Kicker:** Objections

**Headline (h1):** The toughest pushback, taken seriously.

**Lede (with drop cap):**

An argument worth making must be willing to lose to its strongest objections. The ones below are the responses heard most often, in the form a careful reader would press them. Most are answerable on the merits. A few raise points the argument has to absorb.

---

**Each objection appears with the prefix "Objection." automatically rendered in red. The h3 is the objection statement itself.**

### Animal sentience is too uncertain to ground policy. The science is contested.

The version of this objection that prevailed twenty years ago no longer matches the literature. The contested question now is where the boundary of probable sentience lies, not whether anything substantial sits inside it. No serious working consciousness scientist denies the realistic possibility of pain in cephalopods or decapods, and the New York Declaration formalized the field's consensus in 2024. Whether bees or fruit flies cross the boundary remains genuinely contested. Whether mammals, birds, fish, and the well-studied invertebrates do is not. The sophisticated form of the objection holds only at the still-contested boundary, where it does real work, and almost no work against the species responsible for the bulk of global suffering. A reader can remain skeptical about *Drosophila* sentience and still owe chickens, fish, octopuses, and crabs everything they would owe a sentience candidate.

---

### Alignment is the urgent problem. Adding animal welfare distracts from it.

This is the response heard most often from alignment-serious readers, and it gets the situation's structure backwards. The animal welfare case is not an external import to alignment. On the strongest available framing of AI welfare, it sits inside the alignment problem as a methodological dependency. The marker method, the precautionary frame, and the institutional review structure are all pieces of animal welfare infrastructure being applied upstream of AI sentience research. Any alignment researcher who has thought carefully about how an advanced system might evaluate human values has had to confront what humans are teaching that system about whose suffering counts. Treating animal welfare as a distraction from alignment is rhetorically tidy and substantively unstable. Taking alignment more seriously increases, rather than decreases, the weight of the consistency point.

**Standout:**

Taking alignment more seriously increases, rather than decreases, the weight of the case for animals.

---

### Animals matter less than humans. The expected utility math doesn't favor them.

This one is partially conceded. Most readers of this argument will not weigh a chicken equally with a child, and the argument does not require equal weighting. It depends on a weaker claim: that the discrepancy between the weight a typical reader would endorse on reflection (for a fish, an octopus, or a cow) and the weight expressed in current operational practice is large. Current practice expresses, in revealed preferences, a weight close to zero. No defensible philosophical position maps to a near-zero weight. Even highly speciesist frameworks place some non-trivial weight on the suffering of vertebrates capable of pain. The disparity between any defensible weight, however small, and the weight implicit in industrial throughput is the moral fact at issue.

---

### If suffering is the harm, genetic disenhancement of livestock would address the welfare problem on its own terms.

The proposal has a serious history. Adam Shriver argued in a 2009 paper in *Neuroethics* that genetic modification of livestock to remove the affective component of pain would be a moral improvement on the present system. Paul Thompson's earlier "blind chicken" thought experiment (2008) presses similar logic in a less invasive form, on the observation that a strain of congenitally blind hens shows lower stress under crowded housing. Peter Singer, asked about engineering a "brainless bird" grown strictly for meat, called it "an ethical improvement on the present system, because it would eliminate the suffering that these birds are feeling." A 2012 architecture proposal by André Ford, the "Headless Chicken Solution," went further: surgical removal of the cerebral cortex, leaving the brainstem online for homeostatic function and eliminating the bird's awareness of its situation. Variants of the same logic appear in effective-altruist work on slower-growing broiler breeds and metabolic-disease-resistant lines. Each proposal aims at the suffering and leaves the instrumental relation in place.

The argument on this site treats the instrumental relation as the harm at issue, with suffering as its most visible side effect. Removing the capacity to suffer from a being while continuing to treat it as an instrument cleans up the side effect of the underlying wrong. It does not address the wrong. The symmetric case under AI is the test. A more capable system that bred a docile, contented strain of humans for some purpose of its own, engineered to find its conditions agreeable, with no suffering in the welfare-economics sense, would fail the alignment criterion the field has put on paper, and would do so because it had instrumentalized a kind of being that should not be available as an instrument. The same fact, applied to animals, gives the underlying objection to disenhancement. The argument is symmetric.

---

### The coherence argument is just a basilisk. It tries to scare the field into compliance.

The argument here does not depend on a future AI punishing humans for past failures. The worry recurs in this kind of discussion and is worth addressing directly. The argument concerns inheritance. Models inherit human values from human work. An advanced system reasoning carefully about its training data will see what humans have done alongside what humans have written. There is no specific retaliatory mechanism to point at. The structural claim is duller and harder to evade: a system trained on a corpus of moral writing will, if it reasons coherently, notice the gap between that writing and the practice. The cost is what gets handed on. What gets handed on, on present trajectory, is an incoherent moral system, which is the kind of system alignment was supposed to prevent.

---

### Diet and consumption are personal choices. The AI industry should not legislate them.

The objection is correct at the level of individual diet and incorrect at the level of organizational practice. Nothing in this argument suggests an AI lab should police what employees eat at home. The argument concerns institutional practice: what the cafeteria serves, how events are catered, how research priorities are set, where philanthropic capital flows, what model constitutions include and exclude, and which supply chains the lab is willing to optimize. These are organizational choices with organizational consequences, and organizations are routinely understood to make and defend them. The line between organizational ethics and individual ethics has been workable for the entirety of corporate practice; it does not collapse in this case.

---

### If we expand moral concern to animals, we logically have to expand it to plants, cells, and gradients of organization. The argument doesn't terminate.

This is the slippery-slope worry, deployed seriously by some readers and dismissively by others. Birch and the consciousness-science community handle it explicitly. There is a zone of reasonable disagreement (Birch's R1 to R5) within which several substrate-grounded theories of consciousness can be entertained on the available evidence. Plants, single cells outside the body, viruses, ecosystems as such, and most things at the lowest level of biological organization fall outside that zone. They are not sentience candidates on the published evidence; they are at most subjects for further investigation. The argument terminates well before panpsychism. The species this argument is concerned with — vertebrates, cephalopods, decapods, the well-studied insects — sit firmly inside the zone where reasonable theories converge on at least a realistic possibility of sentience. The logical structure does not commit anyone to caring about quartz crystals.

---

### Even if true, the argument is inert. Industries don't change because of arguments.

Sometimes industries don't change in response to arguments, and sometimes they do. The relevant fact about the AI industry is that it is small, young, and unusually self-aware about the consequences of its own work. Arguments still move it. The constitutional approach to model character, the AI welfare research that has emerged over the last three years, and the public commitments to safety as a load-bearing concern did not exist a decade ago. The people who built them did so in part because the arguments they took on board demanded it. Whether this argument moves the field depends on how it is received. The claim that it cannot is a reason to make it carefully, not a reason to skip making it.

---

### This is a soft argument dressed up in alignment vocabulary. It's animal welfare advocacy with a different audience.

It is animal welfare advocacy. It is also a hard argument. The hardness comes from a structural claim, that the moral coherence of alignment is part of alignment's load-bearing technical stack, which on the standard moral discount applied to animal questions is not an obvious one. The case is the same from both sides: taking AI welfare seriously, on the methodology actually proposed by people inside the AI welfare community, entails taking animal welfare seriously by direct logical entailment. Accepting one and not the other is unstable. The argument is "soft" only if the inheritance claim is wrong, in which case the alignment-relevant version is also wrong and the field needs a different basis for the AI welfare commitments it is currently building. The latter does not appear to be what most of the field wants.

---

### Moral circle expansion is a long-term project. AI is here now. Order of operations matters.

Order of operations does matter. In this case, the order favors working on both at once, because the work on each accelerates the other. AI welfare research is more likely to be done seriously, with appropriate uncertainty rather than corporate denialism, at labs that already take animal welfare seriously, because the relevant instincts about under-attribution are already active there. AI capability work is more likely to be directed toward alternatives to animal use, including lab-grown meat, in-silico drug screening, and welfare-aware agricultural automation, at organizations whose leadership treats animal suffering as load-bearing. The two missions are mutually reinforcing. Labs that take only one seriously will, in practice, find the other slipping in by the same logic until the inconsistency resolves.

---

**Closing paragraph:**

If there is an objection not addressed here that a reader thinks is the strongest one, we want to hear it. The argument is meant to survive contact with serious resistance. If it does not, the case has to be either revised or abandoned.

---

# PAGE: What to Do (`action.html`)

**Kicker:** What to Do

**Headline (h1):** Where the work is.

**Lede (with drop cap):**

The argument has practical consequences for several distinct audiences inside and near the AI industry. The lists below are a working inventory of the moves available to each. The list is not a compliance checklist; it is a map of where the leverage is concentrated.

---

## For lab leadership and senior researchers

**Body:** The most consequential decisions in this category are constitutional. The character a model is being trained to have is shaped by a small number of teams writing a small number of documents. The relevant moves:

- **Include animal welfare in the model's constitution explicitly.** The treatment should be a worked-through articulation of how the model should reason about cases involving non-human sentience under uncertainty, not a list of compliance rules. Birch's "realistic possibility" threshold is a useful operational standard. The model should not be trained to flatly deny welfare-relevant capacities in animals, in itself, or in other AI systems. That is the position the published literature has converged on.
- **Stop instructing models to flatly deny their own consciousness.** Birch is direct on this point: "AI companies have responded to the risk by explicitly instructing their LLMs to describe themselves as non-sentient, but I do not see this as a viable strategy for the long term. AI companies risk eroding trust if they hide behind false certainties instead of honestly communicating uncertainty." The position to train toward is appropriate uncertainty.
- **Hire someone whose job is animal welfare alongside the AI welfare officer the lab may already have hired.** The two roles overlap by intellectual design. They benefit from being held by the same person or the same small team.
- **Refuse to optimize agricultural-AI products for throughput alone, without welfare constraints.** Frontier models are being deployed into supply chains, and the terms of those deployments are being set now. A frontier lab has both the standing and the discretion to insist that its AI is not used to industrialize the worst practices further.

---

## For operations and culture

**Body:** The cafeteria is one of the load-bearing sites of moral practice in any organization that takes its values seriously. Catering, the default benefits package, and the procurement contract are others. These are the places where stated values become visible practice.

- **Default the cafeteria, employee meals, and event catering to animal-product-free options.** Animal products should be opt-in rather than the unmarked default. The signal is institutional: the lab does not treat animal products as the standard.
- **Make this true at the all-hands and the offsite, not only at the lunch line.** The signal does most of its work at organizational rituals, where attention to defaults is highest.
- **Disclose the policy in the same documents that disclose your safety commitments.** Integration is what makes these commitments load-bearing rather than ornamental.

---

## For philanthropic capital

**Body:** A meaningful fraction of the philanthropic capital being deployed by AI fortunes goes to AI safety. Substantial sums also flow to global health, economic development, and long-term futures. Animal welfare receives, by every estimate available, a tiny fraction of global philanthropic spend, despite a body count and marginal returns to capital that are larger than for almost any other category.

- **Allocate a meaningful portion of AI-derived philanthropic capital to animal welfare.** The high-leverage organizations are well known to the effective-altruism community: cage-free egg campaigns, broiler-chicken welfare commitments, fish welfare, shrimp welfare initiatives, work on banning octopus farming, alternative-protein research and policy, and animal advocacy in low- and middle-income countries.
- **Fund the welfare-science work directly.** This includes the Birch-style work on the marker method, the Sebo-style work on the moral-circle frame, and the philosophy and empirical neuroscience that produced the New York Declaration. These are small fields by AI-philanthropy standards, and they benefit substantially from marginal capital.
- **Fund applications of AI capability to animal welfare directly.** The relevant areas include welfare-aware farm automation, cell culture and protein engineering for cultivated meat, AI-driven analysis of animal behavior at scale, and automated monitoring of animal-research compliance. These are technically rich and underfunded.

---

## For research priorities

**Body:** The intersection of AI welfare, animal welfare, and consciousness science is a productive area and is currently understaffed. Some priorities:

- **Adapt the marker method explicitly for use across substrates.** The original method was built for animals. Long, Sebo, and colleagues are building the AI version. A full-stack version, applicable across biological, organoid, hybrid, and AI substrates with appropriate uncertainty handling, does not yet exist and is needed.
- **Take on the gaming problem.** Birch is right that LLM behavioral markers can be gamed. The architectural and computational markers that survive gaming have to be developed and validated. Interpretability research is the bottleneck, and AI labs are uniquely positioned to do it.
- **Apply AI capability to existing welfare problems at scale.** Specific work includes vision and audio models for behavioral assessment of farm animals, mechanistic interpretability of fish and invertebrate nervous systems, and optimization of welfare-aware processing in supply chains. None of these are blocked by capability today; they are blocked by attention.
- **Do the work on the ethics of co-existence with non-human minds.** Goertzel's "I-Thou" framing, Birch's "co-existence rather than use" framing, and Levin's diverse-intelligence framing point at the same intellectual region: a theory of how forms of mind unlike one's own can be addressed and lived with. The work is the substrate on which alignment-as-negotiation has to rest, and it remains underbuilt.

---

## For individual researchers

**Body:** At the individual level, the available moves are familiar. The list below covers diet, donation, lab-internal advocacy, and reading.

- Reduce or eliminate consumption of animal products, where possible. Start with the products most associated with the worst suffering: factory-farmed chicken, fish, shrimp, and eggs.
- Donate. The marginal dollar to animal welfare buys substantially more reduced suffering than the marginal dollar to almost any other cause area, on the published cost-effectiveness estimates.
- Raise the argument inside the lab. The objective is for it to be a steady part of how the work gets discussed, not a constant or loud presence. Norm shifts in small communities move faster than expected.
- Read the literature. Three places to start: Birch's *The Edge of Sentience* for the synthesis, Sebo's *The Moral Circle* for the philosophy, and Long, Sebo et al.'s *Taking AI Welfare Seriously* for the bridge between AI and animal welfare. The animal-cognition primary literature is more accessible than most outsiders expect.

---

## For the field's discourse

**Body:** What is currently missing from the alignment literature is the connecting work between the AI welfare arguments the field has begun to articulate and the animal welfare arguments those AI welfare arguments are methodologically built on. Closing that gap is a writing project.

- When alignment researchers write about value inheritance, take a paragraph to note explicitly the discrepancy the corpus contains between stated and operational ethics around animals.
- When AI welfare researchers cite the marker method or Birch, add the line: the same logic applies to the animals the method was developed for.
- When labs publish constitutions, do the moral-coverage check explicitly. List the categories of moral patient the constitution attempts to cover. If animals are not in the list, write down the reason.
- When the topic comes up in public discussion, refuse the both-sides framing that treats the empirical case as still open. It is not. The political case is also not open. The operational case is open, and that is the case that benefits from the ambiguity.
- When suffering-reduction proposals like genetic disenhancement come up in welfare conversations, take the deeper question. Following the philosophical lineage from Shriver and Thompson, the proposals aim at the suffering and leave the instrumental relation in place. The instrumental relation is the harm at issue. Reducing suffering inside an unchanged instrumental relation is not the same thing as ending the wrong, and a frame that treats it as the same will not survive contact with the symmetric AI case.

---

**Standout (page-foot):**

The work is concrete, specific, and within reach. None of it requires unanimous agreement to begin.

**Closing paragraph 1:**

This is a longer inventory than initially intended. Each item is meant to be specific, and most are within reach of effort the field can afford. None require unanimous agreement, which is the condition most calls for change use to defer indefinitely. The work is available now, while the capability gap that makes constraint-based alignment workable still holds.

**Closing paragraph 2:**

For a reader looking for a single starting move: find the constitutional document for the model the lab is currently training, read it, and note what it says about the moral status of beings other than humans. Draft the version it should say. Send the draft to whoever owns the document, and start the conversation.

---

# PAGE: Sources (`sources.html`)

**Kicker:** Sources

**Headline (h1):** The argument is built from open work. Here it is, by author.

**Lede:**

The works below are organized by author. Where the work is open-access, that is noted. Quotations on the site are verbatim from these sources, and paraphrases are intended to be faithful to the originals. Errors flagged by readers will be corrected.

---

## On animal sentience

- **Andrews, Kristin; Birch, Jonathan; Sebo, Jeff; Sims, Toni** (2024). *The New York Declaration on Animal Consciousness*, with background document. NYU Center for Mind, Ethics, and Policy. Hosted at [nydeclaration.com](https://nydeclaration.com/).

- **Bacqué-Cazenave, Julien; Cattaert, Daniel; Delbecque, Jean-Paul; Fossat, Pascal** (2017). "Social harassment induces anxiety-like behaviour in crayfish." *Scientific Reports* 7, 39935. doi:10.1038/srep39935. Open access.

- **Barr, Stuart; Elwood, Robert W.** (2024). "Trade-Offs between Avoidance of Noxious Electric Shock and Avoidance of Bright Light in Shore Crabs Are Consistent with Predictions of Pain." *Animals* 14(5), 770. doi:10.3390/ani14050770. Open access.

- **Birch, Jonathan** (2024). *The Edge of Sentience: Risk and Precaution in Humans, Other Animals, and AI.* Oxford University Press. ISBN 9780191966729. Open access (CC-BY-NC-ND 4.0). The single most important reference for the argument made on this site.

- **Crook, Robyn J.** (2021). "Behavioral and neurophysiological evidence suggests affective pain experience in octopus." *iScience* 24(3), 102229. doi:10.1016/j.isci.2021.102229. Open access.

- **Sogawa, Shumpei; Kobayashi, Taiga; Bshary, Redouan; Sowersby, Will; Awata, Satoshi; Kubo, Naoki; Nakai, Yuta; Kohda, Masanori** (2025). "Rapid self-recognition ability in the cleaner fish." *Scientific Reports* 15, 41882. doi:10.1038/s41598-025-25837-0.

- **Anthoney, Niki; Tainton-Heap, Lucy; Kewin, Amber B.; Zhao, Qiongyi; Perry, Trent; Batterham, Philip; Shaw, Paul J.; van Swinderen, Bruno** (2023). "Distinct sleep stages in *Drosophila melanogaster*." *eLife*. doi:10.7554/eLife.88198. Open access.

---

## On AI welfare

- **Long, Robert; Sebo, Jeff; Butlin, Patrick; Finlinson, Kathleen; Fish, Kyle; Harding, Jacqueline; Pfau, Jacob; Sims, Toni; Birch, Jonathan; Chalmers, David** (2024). "Taking AI Welfare Seriously." arXiv:2411.00986. The methodological-bridging paper between animal welfare and AI welfare. Funded in part by Anthropic; co-author Kyle Fish subsequently joined Anthropic as its first AI welfare researcher.

- **Grace, Katja; Stewart, Harlan; Sandkühler, Julia Fabienne; Thomas, Stephen; Weinstein-Raun, Ben; Brauner, Jan; Korzekwa, Richard C.** (2024). "Thousands of AI Authors on the Future of AI." arXiv:2401.02843. The largest-ever survey of AI researchers (n = 2,778); cited for the field's own probabilistic reasoning under uncertainty.

---

## On AGI ethics and value transmission

- **Bugaj, Stephan Vladimir; Goertzel, Ben** (c. 2007–2008). "Five Ethical Imperatives and their Implications for Human-AGI Interaction." Novamente LLC and AGI Research Institute. The earlier formulation of the imitative-learning argument.

- **Goertzel, Ben** (2023). "A Beneficial AGI Manifesto." Substack, November 25, 2023. Source for the "guide AGI in a beneficial direction beneficial for humans and other sentient beings" framing and the I-Thou alignment concept; the comment thread includes the Prisco passage cited on the argument page.

- **Levin, Michael** (2022). "Technological Approach to Mind Everywhere: An experimentally-grounded framework for understanding diverse bodies and minds." *Frontiers in Systems Neuroscience*. The foundational diverse-intelligence reference.

- **Levin, Michael** (2022). "Technological Scaffolding Alters the Information Flow within the Brain" / "Cognitive Light Cone" framing, *Frontiers in Systems Neuroscience*.

---

## From inside the AI industry

- **Amodei, Dario** (2024). "Machines of Loving Grace: How AI Could Transform the World for the Better." darioamodei.com, October 2024. Cited for the "biological freedom" framing, the children-shouldn't-die-of-disease intuition pump, the Banks's-Culture reference, and the single mention of factory farming in the context of climate.

- **Amodei, Dario** (2026). "The Adolescence of Technology: Confronting and Overcoming the Risks of Powerful AI." darioamodei.com, January 2026. Cited for the "models inherit humanlike motivations" claim, the constitutional-training framing, and the worked-out misalignment example concerning humans eating animals.

---

## Cognitive science and the moral circle

- **Sebo, Jeff** (2025). *The Moral Circle: Who Matters, What Matters, and Why.* W. W. Norton & Company. ISBN 9781324064800. The contemporary philosophical synthesis on moral-circle expansion.

- **Nieder, Andreas; Wagener, Lysann; Rinnert, Paul** (2020). "A neural correlate of sensory consciousness in a corvid bird." *Science* 369(6511), 1626–1629.

---

## On disenhancement and instrumentalization

- **Shriver, Adam** (2009). "Knocking Out Pain in Livestock: Can Technology Succeed Where Morality has Stalled?" *Neuroethics* 2(3), 115–124. doi:10.1007/s12152-009-9048-6. The canonical philosophical defense of genetic disenhancement of farmed animals as a route to suffering reduction.

- **Thompson, Paul B.** (2008). "The Opposite of Human Enhancement: Nanotechnology and the Blind Chicken Problem." *NanoEthics* 2(3), 305–316. The originating "blind chicken" thought experiment in the disenhancement literature.

- **Palmer, Clare** (2011). "Animal Disenhancement and the Non-Identity Problem: A Response to Thompson." *NanoEthics* 5(1), 43–48. The principal philosophical reply to the disenhancement program.

- **Singer, Peter** (2006). In interview with Oliver Broudy, "The Practical Ethicist," *Slate*, May 8, 2006. Source for the cited remark that engineered "brainless" birds would be "an ethical improvement on the present system, because it would eliminate the suffering that these birds are feeling."

- **Ford, André** (2012). "The Headless Chicken Solution." Architecture project, Royal College of Art, London. Press coverage in *Wired*, *FoodNavigator*, *Inhabitat*, and *HuffPost*, February 2012. The proposal to remove the cerebral cortex surgically while keeping the brainstem online for homeostatic function.

---

## Other works cited

Krieger et al. (2010), on coconut crab brain anatomy. Lopez-Luna et al. (2017), on zebrafish larval pain. Trujillo et al. (2019), on cortical organoid EEG patterns. Gibbons et al. (2022), on bumblebee thermal trade-offs. Loukola et al., Galpayage Dona et al., and Chittka and colleagues (multiple), on bumblebee play. Schnell, Clayton, and colleagues (multiple), on cuttlefish source memory. Howe (2019), on insect population estimates. Roth & Øines (2010); Fregin & Bickmeyer (2016), on decapod neural responses to noxious stimuli. Lacap (2022), on shark nociceptive fibers. Citations consolidated in Birch (2024) where appropriate.

---

**Closing paragraph:**

If you spot an error, a misattribution, or a quotation that does not match the source, please flag it. The argument depends on the citations being correct.

---

# END

That's all the body copy on the site, page-complete. After you make changes, hand the file back (or just tell me what changed) and I'll port the edits into the corresponding HTML files.
