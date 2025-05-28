<!--Copyright 2020 The HuggingFace Team. All rights reserved.

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with
the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on
an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the
specific language governing permissions and limitations under the License.

⚠️ Note that this file is in Markdown but contain specific syntax for our doc-builder (similar to MDX) that may not be
rendered properly in your Markdown viewer.

-->

# 🤗 Transformers

Învățarea Automată în PyTorch, TensorFlow și JAX - la standardul zilei.
🤗 Transformers oferă API-uri pentru a descărca și antrena cu ușurință modele pre-antrenate de ultimă generație.
Utilizarea modelelor pre-antrenate poate reduce costurile, amprenta de carbon și timpul necesar pentru a antrena un model de la zero. Modelele pot fi folosite pentru diverse sarcini:

📝 Texte: clasificare, extragere de informații, întrebări și răspunsuri, rezumare, traducere și generare de texte în peste 100 de limbi.

🖼 Imagini: clasificare, detecție de obiecte și segmentare.

🗣 Audio: recunoaștere vocală și clasificare audio.

🐙 Multimodal: întrebări și răspunsuri pe tabele, recunoaștere optică a caracterelor (OCR), extragere de informații din documente scanate, clasificare video, întrebări și răspunsuri vizuale.

Biblioteca noastră permite integrarea continuă între trei dintre cele mai populare biblioteci de învățare profundă:
PyTorch, TensorFlow și JAX.
Antrenează-ți modelul în trei linii de cod într-un framework și rulează-l într-altul.

Fiecare arhitectură 🤗 Transformers este definită într-un modul de Python individual, pentru a fi ușor personalizabilă în scopuri de cercetare și experimente.

## Dacă căutați sprijin din partea echipei Hugging Face, vă rugăm să vizitați:
<a target="_blank" href="https://huggingface.co/support">
    <img alt="HuggingFace Expert Acceleration Program" src="https://huggingface.co/front/thumbnails/support.png" style="width: 100%; max-width: 600px; border: 1px solid #eee; border-radius: 4px; box-shadow: 0 1px 2px 0 rgba(0, 0, 0, 0.05);">
</a>

## Conţinut

Documentația este împărțită în cinci părți:
    - **ÎNTRODUCERE** conține un tur rapid de instalare și instrucțiuni pentru a începe să folosiți 🤗 Transformers.
    - **TUTORIALE** sunt perfecte pentru a începe să învețe despre biblioteca noastră. Această secțiune vă va ajuta să vă dezvoltați
    abilități de bază necesare pentru a folosi 🤗 Transformers.
    - **GHIDURI PRACTICE** vă vor arăta cum să atingeți un anumit obiectiv, cum ar fi reglarea fină a unui model pre-antrenat
    pentru modelarea limbii sau cum să creați un antet personalizat pentru un model.
    - **GHIDURI CONCEPTUALE** vă vor oferi discuții și explicații suplimentare despre conceptele și ideile fundamentale din spatele modelelor,
    sarcinile și filosofia de design din spatele 🤗 Transformers.
    - **API** descrie modul în care funcționează fiecare clasă și funcție, grupate în:

    - **CLASE PRINCIPALE** pentru clasele care expun API-urile importante ale bibliotecii.
    - **MODELE** pentru clasele și funcțiile aferente fiecărui model implementat în bibliotecă.
    - **AJUTOR INTERN** pentru clase și funcții utilizate intern.

În prezent, biblioteca conține implementări ale PyTorch, TensorFlow și JAX, ponderi pentru modele pre-antrenate și scripturi de utilizare și conversie pentru următoarele modele:

## Modelele actuale

<!--This list is updated automatically from the README with _make fix-copies_. Do not update manually! -->
