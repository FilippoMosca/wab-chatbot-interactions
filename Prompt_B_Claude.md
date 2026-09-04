---
title: "Prompt B — Claude vs. WAB Wittgenstein Chatbot"
interaction: true
---

# User prompt:

*What does Wittgenstein say that could be relevant for contemporary discussions of artificial intelligence?*

# B.1 General-purpose model

| **System** | Anthropic Claude |
| --- | --- |
| **Model** | Claude Sonnet 5 |
| **Date of interaction** | 22 July 2026 |

### Response

Wittgenstein didn't write about anything resembling modern AI, but several of his ideas cut right to the heart of debates people are having about large language models, and in some ways he anticipated the confusions before the technology existed to provoke them.

Meaning as use. In the Philosophical Investigations, Wittgenstein argues against the idea that words get their meaning by referring to some inner mental content or by picking out an essence. Instead, "the meaning of a word is its use in the language." This is strikingly close to how LLMs actually work — they learn from patterns of use across enormous amounts of text, not from anything like a lookup table connecting words to inner concepts. This cuts both ways in the AI debate: it can be used to argue LLMs are doing something more meaning-like than skeptics assume (since use is what meaning consists in, and these systems are saturated in use), or to needle the optimists by pointing out that use divorced from a form of life might not be sufficient — which brings in the next idea.

Forms of life. Wittgenstein insisted that language is embedded in shared human practices, bodily existence, and social life — "to imagine a language is to imagine a form of life." His remark that "if a lion could speak, we could not understand him" is about how understanding requires shared context, not just shared vocabulary. Applied to AI, this raises a real question: can a system with no body, no stakes, no shared human history of pain, hunger, or death really participate in meaning the way we do, even if it produces fluent sentences about those things? Skeptics about "real" machine understanding often lean on this, even without citing Wittgenstein by name.

Rule-following and the rule-following paradox. Wittgenstein's discussion of what it is to "follow a rule" (culminating in Kripke's famous gloss on it) shows that no finite set of examples ever uniquely determines how a rule should be extended to new cases — "no course of action could be determined by a rule, because every course of action can be made out to accord with the rule." This is directly relevant to interpretability and alignment: when we try to specify what we want an AI to do, or infer what rule it's "really" following from its behavior on training data, we run into exactly this indeterminacy. It's a serious problem for any hope of fully specifying AI behavior in advance from examples alone.

Family resemblance concepts. Wittgenstein's example of "game" — there's no single feature shared by all games, just overlapping similarities — is often invoked to argue that words like "intelligence," "understanding," and "thinking" may not have neat necessary-and-sufficient conditions either. If so, questions like "does the model really understand?" might be less a factual question awaiting an answer and more a symptom of expecting language to work in a way it doesn't. This reframes a lot of AI-consciousness debates as partly conceptual confusions rather than open empirical questions.

Skepticism about inner processes. Wittgenstein was suspicious of explanations that posit a hidden inner mental act behind behavior (his private language argument and the "beetle in the box" thought experiment are the key texts). He pushes back on the idea that understanding is best explained by some inner state accompanying the outward behavior. This is relevant to arguments about whether LLMs "really" understand or merely produce outputs that look like understanding — Wittgenstein would likely be suspicious of that whole framing on both sides of the AI debate, since he doubted that positing hidden inner processes ever did the explanatory work people wanted, even for humans.

Taken together, his work doesn't settle whether current AI systems understand, think, or mean anything — but it supplies some of the sharpest tools for noticing when a question in that debate is confused, when it's substantive, and why the temptation to look for a "ghost in the machine" (on either side) might be the wrong move to begin with.

## B.2 WAB Wittgenstein Chatbot

| **System** | WAB Wittgenstein Chatbot |
| --- | --- |
| **Response-generation model** | GPT-5.1 Chat (via Azure OpenAI) |
| **Query-processing model** | GPT-4o mini (via Azure OpenAI) |
| **Embedding model** | text-embedding-3-large (via Azure OpenAI) |
| **Search service** | Azure AI Search |
| **Date of interaction** | 22 July 2026 |

### Response

Wittgenstein repeatedly questions the assumption that thinking must be an inner, uniquely human process inaccessible to machines. He argues that if thinking can consist in activities such as writing, calculating, or symbol manipulation, then there is no obvious reason why a machine could not also think. [[Ms-145\_24\[3\]et25\[1\]](http://localhost:8501/#src-Ms-145_24_3_et25_1_); [Ts-303\_8\[3\]](http://localhost:8501/#src-Ts-303_8_3_)] He even says that because philosophy is not concerned with a special “machinery of the mind,” one could in principle construct a “machine-human” that performs everything essential to us. [[Ms-110\_28\[3\]](http://localhost:8501/#src-Ms-110_28_3_); [Ts-211\_135\[4\]](http://localhost:8501/#src-Ts-211_135_4_)]

A central theme is that many philosophical confusions about mind and AI arise from the way language tempts us to imagine hidden inner mechanisms. Wittgenstein warns that we wrongly picture thought as a process like weaving or manufacturing a product, and therefore imagine it must either occur in a mysterious inner medium or be reproducible mechanically. [[Ts-213\_216r\[5\]](http://localhost:8501/#src-Ts-213_216r_5_); Ts-212\_VI-49-4[1]; [Ms-110\_2\[3\]et3\[1\]](http://localhost:8501/#src-Ms-110_2_3_et3_1_)] He repeatedly says that philosophers are misled by “the waves of language” into thinking that machines contain their future behavior in some mysterious form. [[Ms-119\_36\[3\]et37\[1\]et38\[1\]et39\[1\]et40\[1\]](http://localhost:8501/#src-Ms-119_36_3_et37_1_et38_1_et39_1_et40_1_); [Ts-221a\_230\[4\]et231\[1\]et232\[1\]](http://localhost:8501/#src-Ts-221a_230_4_et231_1_et232_1_)]

This becomes especially relevant in his discussions of whether machines can think or feel pain. Wittgenstein argues that the statement “a machine cannot think” is not an empirical discovery but reflects how we use the word “think.” [[Ms-129\_177\[4\]et178\[1\]](http://localhost:8501/#src-Ms-129_177_4_et178_1_); [Ts-230a\_21\[5\]](http://localhost:8501/#src-Ts-230a_21_5_)] Likewise, asking whether a machine can have pain depends on what we mean by “having pain.” A machine could in principle behave exactly like a human in pain, and in that sense we may speak of it as having pain. [[Ms-114\_76r\[2\]](http://localhost:8501/#src-Ms-114_76r_2_); [Ts-211\_156\[2\]](http://localhost:8501/#src-Ts-211_156_2_); [Ms-110\_35\[3\]et36\[4\]](http://localhost:8501/#src-Ms-110_35_3_et36_4_)]

Several remarks anticipate debates about behavioral criteria and artificial agents. Wittgenstein imagines beings trained to calculate mentally, answer questions, and report “I have calculated,” while observers laugh at the superstition that something hidden and “spiritual” must also be occurring inside them. [[Ts-229\_213\[2\]](http://localhost:8501/#src-Ts-229_213_2_); [Ts-245\_149\[4\]et150\[1\]](http://localhost:8501/#src-Ts-245_149_4_et150_1_); [Ms-130\_156\[2\]et157\[1\]et158\[1\]](http://localhost:8501/#src-Ms-130_156_2_et157_1_et158_1_)] The point is not that inner life is denied, but that our criteria for thought are rooted in participation in language-games and forms of activity, not in access to occult inner states. [[Ts-232\_650\[4\]et651\[1\]](http://localhost:8501/#src-Ts-232_650_4_et651_1_); [Ms-136\_46b\[1\]](http://localhost:8501/#src-Ms-136_46b_1_)]

Wittgenstein also reflects directly on Turing machines. He says that Turing’s machines are fundamentally humans calculating according to rules and that their importance can be expressed in terms of games governed by meaningful and meaningless instructions. [[Ms-135\_59v\[2\]et60r\[1\]](http://localhost:8501/#src-Ms-135_59v_2_et60r_1_); [Ts-229\_448\[1\]](http://localhost:8501/#src-Ts-229_448_1_); [Ts-245\_319\[3\]](http://localhost:8501/#src-Ts-245_319_3_)] This anticipates later discussions of computation as rule-following and of the limits of formal procedures.

Another important theme is that intelligence is inseparable from use within practices. He criticizes the tendency to search for hidden psychological accompaniments of understanding or meaning, arguing instead that what matters is the role expressions play in human activities. [[Ms-107\_237\[4\]et238\[1\]](http://localhost:8501/#src-Ms-107_237_4_et238_1_); [Ms-136\_67b\[2\]](http://localhost:8501/#src-Ms-136_67b_2_)] He even notes that what we call intelligence may consist in capacities such as spontaneously generating meaningful continuations from words. [[Ms-130\_262\[2\]](http://localhost:8501/#src-Ms-130_262_2_); [Ts-245\_170\[6\]](http://localhost:8501/#src-Ts-245_170_6_)]

Wittgenstein’s remarks suggest that contemporary AI debates often become confused when they search for an invisible essence of “real understanding” behind behavior. His emphasis falls instead on language-use, criteria, practices, and the forms of life in which expressions of thought, intention, or understanding have their role. At the same time, he does not simply reduce thinking to mechanism: he repeatedly asks how our concepts of thought, meaning, and understanding are actually applied, and warns against both crude mechanism and mysterious mentalism. [[Ts-232\_651\[4\]](http://localhost:8501/#src-Ts-232_651_4_); [Ms-136\_47a\[3\]](http://localhost:8501/#src-Ms-136_47a_3_); [Ms-136\_53a\[5\]et53b\[1\]](http://localhost:8501/#src-Ms-136_53a_5_et53b_1_)]

### Primary sources retrieved and displayed

**Ms-145\_24[3]et25[1]**

Period: 19331014–19331231

“Könnte es denn eine Gedankenprothese geben? Einen anorganischen Ersatz für den Gedanken”? Aber Denken ist nicht wesentlich menschlicher als Schreiben. Und eine Maschine kann auch schreiben, & auch rechnen. Aber wenn das Denken nun im Schreiben besteht warum soll dies nicht eine Maschine tun? “Ja aber die Maschine weiß von nichts.” Freilich, von einer prothese des Sehens oder Hörens zu reden hat keinen Sinn. Man redet zwar von einem künstlichen Fuß aber nicht von künstlichen Fußschmerzen.

**Ms-110\_28[3]**

Period: 19310126–19310126

Da uns eine Maschinerie des Geistes nichts angeht so müßten wir uns auch einen Maschinenmensch konstruieren können der alles leisten könnte, was für uns wesentlich ist.

**Ts-211\_135[4]**

Period: 19310901–19320831

Da uns eine Maschinerie des Geistes nichts angeht, so müßten wir uns auch einen Maschinenmenschen konstruieren können, der alles leisten könnte, was für uns wesentlich ist.

**Ts-229\_213[2]**

Period: 19470901–19471031

Diese Wesen lernen nun z.B. rechnen, schriftlich oder mündlich rechnen. Wir bringen sie aber, irgendwie, dahin, daß sie uns das Ergebnis einer Multiplikation sagen können, nachdem sie, ohne zu schreiben oder zu sprechen, eine Weile stille gesessen sind. Wenn man dabei die Art und Weise betrachtet, wie sie dies ‘Kopfrechnen’ lernen und die Erscheinungen die es umgeben, so liegt das Bild nahe, … Wir müssen natürlich für verschiedene Zwecke einen Befehl haben der Art: “Rechne dies im Kopf!”; eine Frage “Hast Du es gerechnet?”; ja auch “Wie weit bist Du gekommen?”. Eine Aussage des Automaten “Ich habe ‥‥ gerechnet”; etc. etc. Kurz: alles, was wir, unter uns, über das Kopfrechnen sagen, hat auch Interesse für uns, wenn sie's sagen. Und was für's Kopfrechnen gilt, gilt auch für andere Formen des Denkens. – – Äußert etwa jemand bei uns die Ansicht, in diesen Wesen müßte doch dabei etwas vorgehen, und zwar etwas seelisches, so wird darüber wie über einen dummen Aberglauben gelacht. Und wenn es gar vorkommt, daß die Sklaven spontan den Ausdruck bilden, in ihnen sei dies oder jenes vorgegangen, so kommt uns das besonders komisch vor.

**Ts-245\_149[4]et150[1]**

Period: 19470901–19471231

Diese Wesen lernen nun z.B. rechnen, schriftlich oder mündlich rechnen. Wir bringen sie aber, irgendwie, dahin, daß sie uns das Ergebnis einer Multiplikation sagen können, nachdem sie, ohne zu schreiben oder zu sprechen, eine Weile stille gesessen sind. Wenn man dabei die Art und Weise betrachtet, wie sie dies ‘Kopfrechnen’ lernen und die Erscheinungen die es umgeben, so liegt das Bild nahe, ‥․ Wir müssen natürlich für verschiedene Zwecke einen Befehl haben der Art: “Rechne dies im Kopf!”; eine Frage “Hast Du es gerechnet?”; ja auch “Wie weit bist Du gekommen;” ; eine Aussage des Automaten “Ich habe ‥‥ gerechnet”; etc. etc.. Kurz: alles, was wir, unter uns, über das Kopfrechnen sagen, hat auch Interesse für uns, wenn sie's sagen. Und was für's Kopfrechnen gilt, gilt auch für andere Formen des Denkens. – – Äußert etwa jemand bei uns die Ansicht, in diesen Wesen müßte doch dabei etwas vorgehen, und zwar etwas Seelisches, so wird darüber wie über einen dummen Aberglauben gelacht. Und wenn es gar vorkommt, daß die Sklaven spontan den Ausdruck bilden, in ihnen sei dies oder jenes vorgegangen, so kommt uns das besonders komisch vor.

**Ms-130\_156[2]et157[1]et158[1]**

Period: 19460526–19460526

Diese Wesen lernen nun, z.B., rechnen, schriftlich oder mündlich rechnen. Wir bringen sie aber, irgendwie, dahin, daß sie uns das Ergebnis einer Multiplikation mitteilen können, nachdem sie, ohne zu schreiben oder zu sprechen, eine Weile stille gesessen sind. Wenn man dabei die Art & Weise betrachtet, wie sie dies ‘Kopfrechnen’ lernen & die Erscheinungen, die es umgeben so liegt das Bild nahe, … Wir müssen natürlich für verschiedene Zwecke einen Befehl haben der Art: “Rechne dies im Kopf!”; eine Frage “Hast Du es gerechnet?”; ja auch “Wie weit bist Du gekommen?”; eine Aussage des Automaten “Ich habe … gerechnet”; etc. etc. Kurz: alles, was wir, unter uns, über das Kopfrechnen sagen, hat auch Interesse für uns, wenn sie's sagen. Und was fürs Kopfrechnen gilt, gilt auch für andere Formen des Denkens. – Äußert etwa jemand bei uns, diese Dinge in diesen Wesen müßte doch dabei etwas vorgehen, & zwar etwas Seelisches, so wird darüber, wie über einen dummen Aberglauben, gelacht. Und wenn es gar vorkommt daß die Sklaven spontan den Ausdruck bilden, “in mir ist ihnen sei dies oder jenes vorgegangen, so kommt uns das besonders komisch vor.

**Ms-119\_36[3]et37[1]et38[1]et39[1]et40[1]**

Period: 19370927–19370927

Wann denkt man denn : die Maschine habe ihre möglichen Bewegungen schon in irgend einer mysteriösen Weise in sich? – Nun, wenn man philosophiert. Und was verleitet uns, das zu denken? Die Art & Weise, wie wir von der Maschine reden. Wir sagen z.B. die Maschine (besäße) diese Bewegungsmöglichkeiten, wir sprechen von der ideal starren Maschine, die sich nur so & so bewegen könne. – Die Bewegungsmöglichkeit, was ist sie? Sie ist nicht die Bewegung; aber sie scheint auch nicht die bloße physikalische Bedingung der Bewegung zu sein, etwa, daß zwischen Lager & Zapfen ein gewisser Zwischenraum ist, der Zapfen nicht zu streng ins Lager paßt. Denn dies ist nur erfahrungsmäßig die Bedingung der Bewegung, aber man könnte sich die Sache auch anders vorstellen. Die Bewegungsmöglichkeit soll mehr wie ein Schatten der Bewegung selber sein. Aber hier wieder: Kennst Du so einen Schatten?! Und unter Schatten verstehe ich nicht irgend ein Bild der Bewegung; denn dies Bild müßte ja nicht das Bild gerade dieser Bewegung sein. Aber die Möglichkeit dieser Bewegung muß die Möglichkeit gerade dieser Bewegung sein. (Sieh', wie hoch die Wellen der Sprache hier wieder gehen.) Die Wellen legen sich , so wie wir (uns) fragen: wie gebrauchen wir denn, wenn wir von einer Maschine reden, das Wort, “Möglichkeit der Bewegung”? – Woher kamen aber dann die seltsamen Ideen ? Nun, ich zeige Dir die Möglichkeit der Bewegung etwa durch ein Bild der Bewegung: ‘also ist die Möglichkeit etwas der Wirklichkeit Ähnliches’. Wir sagen: “es bewegt sich noch nicht, aber es hat schon die Möglichkeit sich zu bewegen”, ‘also ist die Be Möglichkeit etwas der Wirklichkeit selbst sehr Nahes’.

**Ms-130\_262[2]**

Period: 19460804–19460804

Es könnte sein, daß Menschen, wenn man ihnen ein isoliertes Wort sagt, gleich irgend einen Satz mit diesem Wort bildeten , (&) daß andere es nicht täten; (&) daß jenes ein Zeichen von Intelligenz, dieses von Stumpfheit wäre.

**Ts-221a\_230[4]et231[1]et232[1]**

Period: 19380101–19381231

Wann denkt man denn: die Maschine habe ihre möglichen Bewegungen schon in irgend einer mysteriösen Weise in sich? – Nun, wenn man philosophiert. Und was verleitet uns, das zu denken? Die Art und Weise, wie wir von der Maschine reden. Wir sagen z.B., die Maschine habe (besäße) diese Bewegungsmöglichkeiten, wir sprechen von der ideal staren starren Maschine, die sich nur so und so bewegen könne. ‒ ‒ Die Bewegungsmöglichkeit, was ist sie? Sie ist nicht die Bewegung; aber sie scheint auch nicht die bloße physikalische Bedingung der Bewegung zu sein, etwa, daß zwischen Lager und Zapfen ein gewisser Zwischenraum ist, der Zapfen nicht zu streng ins Lager paßt. Denn dies ist nur erfahrungsmäßig die Bedingung der Bewegung, aber man kone könnte sich die Sache auch anders vorstellen. Die Bewegungsmöglichkeit soll mehr wie ein Schatten der Bewegung selber sein. Aber hier wieder: Kennst Du so einen Schatten? Und unter Schatten verstehe ich nicht irgendein Bild der Bewegung; denn dies Bild müßte ja nicht das Bild gerade dieser Bewegung sein. Aber die Möglichkeit dieser Bewegung muß die Möglichkeit gerade dieser Bewegung sein. (Sieh', wie hoch die Wellen der Sprache hier gehen.) Die Wellen legen sich, so wie wir uns fragen: wie gebrauchen wir denn, wenn wir von einer Maschine reden, das Wort “Möglichkeit der Bewegung”? – Woher kamen aber dann die seltsamen Ideen? Nun, ich zeige Dir die Möglichkeit der Bewegung etwa durch ein Bild der Bewegung: ‘also ist die Möglichkeit etwas der Wirklichkeit Ähnliches’. Wir sagen: “es bewegt sich noch nicht, aber es hat schon die Möglichkeit sich zu bewegen”, ‘also ist die Möglichkeit etwas der Wirklichkeit sehr Nahes’.

**Ts-221a\_230[4]et231[1]et232[1]**

Period: 19380101–19381231

hier gehen.) Die Wellen legen sich, so wie wir uns fragen: wie gebrauchen wir denn, wenn wir von einer Maschine reden, das Wort “Möglichkeit der Bewegung”? – Woher kamen aber dann die seltsamen Ideen? Nun, ich zeige Dir die Möglichkeit der Bewegung etwa durch ein Bild der Bewegung: ‘also ist die Möglichkeit etwas der Wirklichkeit Ähnliches’. Wir sagen: “es bewegt sich noch nicht, aber es hat schon die Möglichkeit sich zu bewegen”, ‘also ist die Möglichkeit etwas der Wirklichkeit sehr Nahes’. Wir mögen zwar bezweifeln, ob die und die physikalische Bedingung, diese Bewegung möglich macht, aber wir diskutieren nie, ob dies die Möglichkeit dieser oder jener Bewegung sei: ‘also steht die Möglichkeit der Bewegung zur Bewegung selbst in einer einzigartigen Relation, enger, als die des Bildes zu seinem Gegenstand’, denn es kann gefragt werden, wessen Bild dies Bild ist. Wir sagen: “die Erfahrung wird lehren, ob dies dem Zapfen diese Bewegungsmöglichkeit gibt”, aber wir sagen nicht: “die Erfahrung wird lehren, ob dies die Möglichkeit dieser Bewegung ist”: ‘also ist es nicht Erfahrungstatsache, daß diese Möglichkeit die Möglichkeit gerade dieser Bewegung ist’. Wir achten auf unsere eigene Ausdrucksweise, diese Dinge betreffend, verstehen sie aber nicht, sondern mißdeuten sie. Wir sind, wenn wir philosophieren, wie Wilde, wie primitive Menschen, die die Ausdrucksweise zivilisierter Menschen hören, sie mißdeuten und nun die seltsamsten Schlüsse aus ihrer Deutung ziehen. Denke Dir, es verstünde eine Einer unsre Vergangenheitsform nicht: “er ist hier gewesen”. ‒ ‒ Er sagt: “er “‘er ist’, das ist die Gegenwart, also sagt der Satz, daß die Vergangenheit in einem gewissen Sinne gegenwärtig ist”.

**Ts-245\_170[6]**

Period: 19470901–19471231

Es könnte sein, daß Menschen, wenn man ihnen ein isoliertes Wort sagt, gleich irgend einen Satz mit diesem Wort bildeten, und daß andere es nicht täten; daß jenes ein Zeichen von Intelligenz, dieses von Stumpfheit wäre.

**Ts-213\_216r[5]**

Period: 19330319–19330415

Wir sagen, wir werden das Denken untersuchen von dem Standpunkt aus, daß es auch von einer Maschine ausgeführt werden könnte. Aber hier befinden wir uns in einer falschen Betrachtungsweise. Wir sehen das Denken als einen Vorgang wie das Schreiben an, oder das Weben das Erzeugen eines Stoffes, etc.. Und dann läßt sich natürlich sagen, daß dieser Vorgang der Erzeugung sich im Wesentlichen auch maschinell muß denken lassen.

**Ms-136\_47a[3]**

Period: 19480102–19480102

“Aber könnte nicht das Operieren mit Zeichen auch mechanisch sein?” – Freilich; mir d.h., auch es muß in einer bestimmten Umgebung sein, damit man sagen kann es sei nicht mechanisch.

**Ms-107\_237[4]et238[1]**

Period: 19300114–19300114

Ist es ein Einwand gegen meine Auffassung daß wir oft halb oder gar ganz automatisch sprechen? Wenn mich jemand fragt „ist der Vorhang in diesem Zimmer grün” & ich schaue hin & sage „nein, rot”, so ist es gewiß nicht nötig daß ich grün halluziniere & es etwa mit dem Vorhang vergleiche. Ja das Ansehen des Vorhangs kann jene Antwort sehr wohl automatisch hervorbringen. Und doch interessiert diese Antwort die Logik dagegen interessiert sie kein Pfiff den ich etwa auch beim Sehen von rot automatisch hervorbringe. Ist es nicht so daß sich die Logik für diese Antwort nur als einen Teil eines Sprachsystems interessiert? Des Systems in dem unsere Bücher geschrieben sind? Kann man sagen daß die Logik die Sprache in extenso betrachtet? Also so wie die Grammatik! Kann man denn sagen daß die Logik mit jener Äußerung wenn sie bloß automatisch war eben nichts zu tun hat? Soll sich denn die Logik darum kümmern ob der Satz auch wirklich gründlich gedacht war? Und welches Kriterium hätte man dafür? Doch nicht gar das lebhafte Spiel der Vorstellungen, die das Aussprechen des Satzes begleiten! Es ist klar wir sind hier in einem Gebiet das uns gar nichts angeht & aus dem wir uns schleunigst retirieren sollen.

**Ms-114\_76r[2]**

Period: 19331001–19331231

“Aber könnte eine Maschine denken?” – Könnte sie Schmerzen haben? Hier kommt es drauf an , was man darunter versteht: “etwas habe Schmerzen”. Ich kann den Andern als eine Maschine ansehen die Schmerzen hat, d.h.: den andern Körper. Und ebenso, natürlich, meinen Körper. Dagegen setzt das Phänomen der Schmerzen, welches ich beschreibe, wenn ich etwa sage, “ich habe Zahnschmerzen”, einen physikalischen Körper nicht voraus. (Ich kann z Zahnschmerzen haben ohne Zähne.) Und hier hat nun die Maschine gar keinen Platz. – Es ist klar, die Maschine kann nur einen physikalischen Körper ersetzen. Und in dem Sinne, in welchem man von einem solchen sagen kann, er habe Schmerzen, kann man es auch von einer Maschine sagen. Oder wieder: die Körper, von denen wir sagen, sie hätten Schmerzen, können wir mit Maschinen vergleichen, & auch Maschinen nennen.

**Ts-211\_156[2]**

Period: 19310901–19320831

Nun ist das aber ganz so, wie wenn man sagt, eine Maschine kann nicht denken, oder kann keine Schmerzen haben. Und hier kommt es darauf an, was man darunter versteht “Schmerzen zu haben”: Es ist klar, daß ich mir eine Maschine denken kann, die sich genau so benimmt (in allen Details), wie ein Mensch der Schmerzen hat. Oder vielmehr: ich kann den Andern eine Maschine nennen, die Schmerzen hat, d.h.: den andern Körper. Und ebenso, natürlich, meinen Körper. Dagegen hat das Phänomen der Schmerzen, wie es auftritt, wenn ‘ich Schmerzen habe’, mit meinem Körper, d.h. mit den Erfahrungen die ich als Existenz meines Körpers zusammenfasse, gar nichts zu tun. (Ich kann Zahnschmerzen haben ohne Zähne.) Und hier hat nun die Maschine gar keinen Platz. – Es ist klar, die Maschine kann nur einen physikalischen Körper ersetzen. Und in dem Sinne, wie man von einem solchen sagen kann, er “habe” Schmerzen, kann man es auch von einer Maschine sagen. Oder, wieder, die Körper, von denen wir sagen, sie hätten Schmerzen, können wir mit Maschinen vergleichen und auch Maschinen nennen.

**Ms-119\_36[3]et37[1]et38[1]et39[1]et40[1]**

Period: 19370927–19370927

Die Wellen legen sich , so wie wir (uns) fragen: wie gebrauchen wir denn, wenn wir von einer Maschine reden, das Wort, “Möglichkeit der Bewegung”? – Woher kamen aber dann die seltsamen Ideen ? Nun, ich zeige Dir die Möglichkeit der Bewegung etwa durch ein Bild der Bewegung: ‘also ist die Möglichkeit etwas der Wirklichkeit Ähnliches’. Wir sagen: “es bewegt sich noch nicht, aber es hat schon die Möglichkeit sich zu bewegen”, ‘also ist die Be Möglichkeit etwas der Wirklichkeit selbst sehr Nahes’. Wir mögen zwar bezweifeln ob die & die physikalische Bedingung, diese Bewegung möglich macht, aber wir diskutieren nie, ob dies die Möglichkeit dieser oder jener Bewegung sei: ‘also steht die Möglichkeit der Bewegung zur Bewegung selbst in einer einzigartig engen Relation, enger als die des Bildes zu seinem Gegenstand’, ’denn es kann gefragt werden, wessen Bild dies Bild ist. Wir sagen: “die Erfahrung wird lehren, ob dies dem Zapfen diese Bewegungsmöglichkeit gibt” aber wir sagen nicht: “die Erfahrung wird lehren, ob dies die Möglichkeit dieser Bewegung ist.”: ‘also ist es nicht Erfahrungstatsache, daß diese Möglichkeit die Möglichkeit gerade dieser Bewegung ist.’ Wir achten auf unsere eigene Ausdrucksweise diese Dinge betreffend, verstehen sie aber nicht, sondern mißdeuten sie. Wir sind, wenn wir philosophieren, wie wilde, primitive Menschen, die die Ausdrucksweise zivilisierter Menschen hören , sie mißdeuten & nun die seltsamsten Schlüsse aus ihrer Deutung ziehen.

**Ts-229\_448[1]**

Period: 19470901–19471031

Turing's ‘Maschinen’. Diese Maschinen sind ja die Menscheschen, welche kalkulieren. Und man könnte, was er sagt, auch in Form von Spielen ausdrücken. Und zwar wären die interessanten Spiele solche, bei denen man gewissen Regeln gemäß zu unsinnigen Anweisungen gelangt. Ich denke an Spiele ähnlich dem “Wettrennspiel”. Man erhielte etwa den Befehl “Setze auf die gleiche Art fort”, wenn dies keinen Sinn ergibt, etwa, weil man in einen Zirkel gerät; denn jener Befehl hat eben nur an gewissen Stellen Sinn. (Watson.)

**Ms-135\_59v[2]et60r[1]**

Period: 19470730–19470730

Turings ‘Maschinen’. Diese Maschinen sind ja die Menschen, welche kalkulieren. Und man könnte, was er sagt, auch in Form von Spielen ausdrücken. Und zwar wären die interessanten Spiele solche, bei denen man gewissen Regeln gemäß zu unsinnigen Anweisungen gelangt. Ich denke an Spiele ähnlich dem “Wettrennspiel”. Man erhielte etwa den Befehl “Setze auf die gleiche Art fort”; wenn dies keinen Sinn ergibt, etwa weil man in einen Zirkel gerät; denn jener Befehl hat eben nur an gewissen Stellen Sinn. (Watson.)

**Ts-232\_651[4]**

Period: 19480801–19481030

“Aber könnte nicht das Operieren mit Zeichen auch mechanisch sein?” – Freilich; d.h., auch dies muß in einer bestimmten Umgebung sein, damit man sagen könne, es sei nicht mechanisch.

**Ts-212\_VI-49-4[1]**

Period: 19320601–19320831

Wir sagen: für uns gibt es nicht wesentlich äußere und innere Vorgänge. (Jeder Vorgang ist in gewissem Sinne ein äußerer Vorgang.) Wir sagen: wir werden das Denken untersuchen von dem Standpunkt aus, daß es auch von einer Maschine ausgeführt werden könnte. Aber hier befinden wir uns in einer gänzlich falschen Betrachtungsweise. Wir sehen das Denken als einen Vorgang wie das Schreiben an, oder das Weben, als wäre es das Erzeugen eines Produkts, des Gedankens, wie das Weben, das Erzeugen eines Stoffes, etc.. Und dann läßt sich natürlich sagen, daß dieser Vorgang der Erzeugung sich im Wesentlichen auch maschinell muß denken lassen.

**Ts-245\_319[3]**

Period: 19470901–19471231

Turing's ‘Maschinen’. Diese Maschinen sind ja die Menschen, welche kalkulieren. Und man könnte, was er sagt, auch in Form von Spielen ausdrücken. Und zwar wären die interessanten Spiele solche, bei denen man gewissen Regeln gemäß zu unsinnigen Anweisungen gelangt. Ich denke an Spiele ähnlich dem “Wettrennspiel”. Man erhielte etwa den Befehl “Setze auf die gleiche Art fort”, wenn dies keinen Sinn ergibt, etwa, weil man einen in einen Zirkel gerät; denn jener Befehl hat eben nur an gewissen Stellen Sinn. (Watson.)

**Ms-110\_2[3]et3[1]**

Period: 19301211–19301211

Wir sagen: Für uns gibt es nicht wesentlich äußere & innere Vorgänge (Jeder Vorgang ist in gewissem Sinne ein äußerer Vorgang). Wir werden das Denken untersuchen als ob es von dem Standpunkt, daß es auch von einer Maschine ausgeführt werden könnte. Aber hier befinden wir uns in einer gänzlich falschen Betrachtungsweise. Wir sehen das Denken für einen Vorgang wie das Schreiben an oder das Weben als wäre es das Erzeugen eines Produkts, des Gedankens, wie das Weben das Erzeugen eines Stoffes etc. Und dann läßt sich natürlich sagen daß dieser Vorgang der Erzeugung sich im Wesentlichen auch maschinell muß deuten lassen. Aber hier ist unsere Auffassung ganz falsch. Das Denken interessiert uns nur sofern es uns unmittelbar gegeben ist. Es ist ein Vorgang nur im unmittelbar Gegebenen.

**Ts-232\_650[4]et651[1]**

Period: 19480801–19481030

Nun, wenn wir Wesen bei der Arbeit sähen, deren Arbeitsrhythmus, deren Mienenspiel, etc. dem unsern ähnlich wäre, nur daß diese Leute nicht sprächen, dann würden wir vielleicht sagen, sie dächten, überlegten, machten Entscheidungen. Das heißt: es wäre eben in so einem Falle viel dem der gewöhnlichen Menschen ähnlich. Und wie soll man entscheiden, wie genau die Analogie sein muß, damit wir ein Recht haben, für diese Leute den Begriff ‘denken’ zu verwenden, der in unserm Leben seine Heimat hat?

**Ms-110\_35[3]et36[4]**

Period: 19310205–19310205

Nun ist das aber ganz so wie wenn man sagt, eine Maschine kann nicht denken, oder kann keine Schmerzen haben. Und hier kommt es drauf an was man darunter versteht „Schmerzen zu haben”. Es ist klar daß ich mir eine Maschine denken kann die sich genau so benimmt (in allen Details) wie ein Mensch der Schmerzen hat. Oder vielmehr: ich kann den Andern eine Maschine nennen die Schmerzen hat d.h.: den andern Körper. Und ebenso natürlich meinen Körper. Dagegen hat das Phänomen der Schmerzen wie es auftritt, wenn ‚ich Schmerzen habe’ mit meinem Körper d.h. mit den Erfahrungen die ich als Existenz meines Körpers zusammenfasse gar nichts zu tun. (Ich kann Zahnschmerzen haben ohne Zähne.) Und hier hat nun die Maschine gar keinen Platz. – Es ist klar, die Maschine kann nur einen physikalischen Körper ersetzen. Und in dem Sinne wie man von einem solchen sagen kann er „habe” Schmerzen kann man es auch von einer Maschine sagen. Oder, wieder, die Körper die wir von denen wir sagen sie hätten Schmerzen, können wir mit Maschinen vergleichen & auch Maschinen nennen.

**Ms-136\_46b[1]**

Period: 19480102–19480102

Nun, wenn wir Wesen bei der Arbeit sähen, deren Arbeitsrhythmus, deren Mienenspiel, etc. dem unsern ähnlich wäre, nur daß diese Leute nicht sprächen, dann würden wir vielleicht sagen, sie dächten, überlegten, machten Entscheidungen. Das heißt: es wäre eben in so einem Falle viel dem der gewöhnlichen Menschen ähnlich. Und wie soll man entscheiden, wie genau die Analogie sein muß, damit wir ein Recht haben für diese Leute den Begriff ‘Denken’ zu verwenden, der in unserm Leben seine Heimat hat?

**Ms-129\_177[4]et178[1]**

Period: 19440801–19440930

Aber eine Maschine kann doch nicht denken! – Ist dies ein Erfahrungssatz? Nein. Wir sagen nur vom Menschen, & was ihm ähnlich ist, es denke. Wir sagen es auch von Puppen, & wohl auch von Geistern. Sieh das Wort “denken” als Instrument an!

**Ms-136\_53a[5]et53b[1]**

Period: 19480103–19480103

Gefährlich wäre es mir nur, wenn einer sagte: “Du setzt eben stillschweigend schon voraus, daß diese Menschen denken; daß sie in dieser Beziehung den uns bekannten Menschen gleichen; daß sie jenes Sprachspiel nicht rein mechanisch betreiben. Denn stelltest Du Dir vor, sie täten's, so würdest Du's selbst nicht ein Sprechen nennen.” Was soll ich nun dem antworten? Es ist natürlich wahr, daß das Leben jener Menschen dem unsern in vieler Beziehung gleichen muß, & daß ich diese Ähnlichkeiten nicht weiter erwähnt habe. Das Wichtige ist aber ist eben, daß ich mir ihre Sprache, wie auch ihr Denken primitiv vorstellen kann; daß es ein ‘primitives Denken’ gibt, welches durch ein primitives Verhalten zu beschreiben ist.

**Ts-230a\_21[5]**

Period: 19450801–19450831

Aber eine Maschine kann doch nicht denken! – Ist das ein Erfahrungssatz? Nein. Wir sagen nur vom Menschen, und was ihm ähnlich ist, es denke. Wir sagen es auch von Puppen, und wohl auch von Geistern. Sieh das Wort “denken” als Instrument an! (342)

**Ts-303\_8[3]**

Period: 19330101–19331231

Kann eine Maschine denken? Wir rufen uns in Erinnerung, daß das Denken nicht notwendig eine Folge oder Reihe von Vorstellungen ist (ich meine, von Phantasievorstellungen). Das Denken kann ebenso wohl im Schreiben, Lesen, Zeichnen, Rechnen bestehen. Nun, dann kann eine Maschine denken, wenn sie z.B. schreiben oder zeichnen kann.

**Ms-136\_67b[2]**

Period: 19480105–19480105

Darum hätte es ja auch keinen Sinn wenn jemand, der mit mir ein angeregtes Gespräch hatte mich danach versicherte, er habe ganz ohne zu denken geredet. Und zwar nicht, weil es aller Erfahrung widerspricht, daß Einer der so reden kann, es ohne die Begleitvorgänge des Denkens tue. Sondern, weil es sich hier zeigt, daß uns die Begleitvorgänge überhaupt nicht interessieren & nicht das Denken ausmachen. Wir kümmern uns den Teufel um seine Begleitvorgänge, wenn er mit uns ein Gespräch in normaler Weise führt.
