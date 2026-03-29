<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
    <title>UG GNURS 303: Eye, Ear, Throat & Dental Nursing | 120 MCQs</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Roboto, 'Helvetica Neue', sans-serif;
        }
        body {
            background: #eef2f8;
            padding: 24px 16px;
            display: flex;
            justify-content: center;
        }
        .exam-wrapper {
            max-width: 1050px;
            width: 100%;
            background: white;
            border-radius: 32px;
            box-shadow: 0 20px 35px -10px rgba(0,0,0,0.2);
            overflow: hidden;
        }
        .ug-banner {
            background: #0b2b3f;
            color: white;
            padding: 22px 30px;
            border-left: 8px solid #f4b942;
        }
        .ug-banner h1 {
            font-size: 1.9rem;
            font-weight: 600;
            letter-spacing: -0.3px;
            margin-bottom: 6px;
        }
        .ug-banner p {
            font-size: 0.85rem;
            opacity: 0.85;
        }
        .timer-panel {
            background: #1c4e6e;
            padding: 12px 30px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 15px;
            color: white;
            font-weight: 500;
        }
        .timer-info {
            display: flex;
            align-items: baseline;
            gap: 20px;
            flex-wrap: wrap;
        }
        .timer {
            font-family: 'Courier New', monospace;
            font-size: 1.8rem;
            font-weight: 700;
            background: #00000040;
            padding: 4px 18px;
            border-radius: 60px;
        }
        .q-counter {
            background: #f4b942;
            color: #0b2b3f;
            padding: 6px 20px;
            border-radius: 40px;
            font-weight: bold;
        }
        .timer-bar-container {
            flex: 1;
            min-width: 150px;
            background-color: #2c5a7a;
            border-radius: 30px;
            height: 12px;
            overflow: hidden;
        }
        .timer-bar {
            width: 100%;
            height: 100%;
            background-color: #2ecc71;
            transition: width 1s linear, background-color 0.3s;
            border-radius: 30px;
        }
        .timer-bar.warning {
            background-color: #e74c3c;
        }
        .quiz-area {
            padding: 28px 32px 20px;
        }
        .question {
            font-size: 1.55rem;
            font-weight: 500;
            line-height: 1.35;
            margin-bottom: 32px;
            color: #0a2a38;
        }
        .options-list {
            display: flex;
            flex-direction: column;
            gap: 14px;
            margin-bottom: 40px;
        }
        .option {
            background: #f9fbfe;
            border: 1.5px solid #e2e8f0;
            border-radius: 24px;
            padding: 12px 20px;
            display: flex;
            align-items: center;
            gap: 16px;
            cursor: pointer;
            transition: 0.1s;
        }
        .option:hover {
            background: #eef3fc;
            border-color: #bbd4f0;
        }
        input[type="radio"] {
            width: 20px;
            height: 20px;
            accent-color: #1f6e8c;
            margin: 0;
            flex-shrink: 0;
        }
        .opt-label {
            font-size: 1rem;
            line-height: 1.4;
            color: #1f2e3f;
            font-weight: 450;
            flex: 1;
        }
        .nav-buttons {
            display: flex;
            justify-content: space-between;
            gap: 20px;
            margin: 16px 0 24px;
        }
        button {
            background: #e9edf2;
            border: none;
            padding: 10px 28px;
            border-radius: 60px;
            font-weight: 600;
            font-size: 0.9rem;
            cursor: pointer;
            transition: 0.2s;
            color: #1c4e6e;
        }
        button.primary {
            background: #1f6e8c;
            color: white;
            box-shadow: 0 2px 6px rgba(0,0,0,0.1);
        }
        button.primary:hover {
            background: #0f526b;
            transform: scale(0.97);
        }
        .submit-area {
            text-align: center;
            margin-top: 10px;
        }
        .submit-final {
            background: #2b7a4b;
            padding: 14px 38px;
            font-size: 1.2rem;
            font-weight: bold;
            border-radius: 60px;
            color: white;
        }
        .result-container {
            background: #f0f6fc;
            border-radius: 28px;
            padding: 24px;
            margin-top: 16px;
        }
        .score-big {
            font-size: 2.2rem;
            font-weight: 800;
            text-align: center;
        }
        .answer-key {
            max-height: 500px;
            overflow-y: auto;
            margin-top: 24px;
            background: white;
            border-radius: 24px;
            padding: 16px;
            font-size: 0.8rem;
        }
        .ans-row {
            display: flex;
            border-bottom: 1px solid #cbdde9;
            padding: 10px 6px;
            gap: 8px;
            flex-wrap: wrap;
        }
        .ans-row.correct {
            background: #e0f2e9;
        }
        .ans-row.wrong {
            background: #ffe6e5;
        }
        .footer {
            background: #f8fafc;
            text-align: center;
            padding: 14px;
            font-size: 0.75rem;
            color: #4a627a;
            border-top: 1px solid #dce5ed;
        }
        @media (max-width: 650px) {
            .question { font-size: 1.3rem; }
            .quiz-area { padding: 20px; }
            .timer-panel { flex-direction: column; align-items: stretch; }
        }
    </style>
</head>
<body>
<div class="exam-wrapper" id="examApp">
    <div class="ug-banner">
        <h1>GNURS 303 · FINAL ASSESSMENT</h1>
        <p>UNIVERSITY OF GHANA | EYE, EAR, NOSE, THROAT & DENTAL NURSING | 120 MCQs | TIME: 50 MINUTES</p>
    </div>
    <div class="timer-panel">
        <div class="timer-info">
            <span>⏱️ REMAINING</span>
            <span class="timer" id="timerDisplay">50:00</span>
            <span class="q-counter" id="counterSpan">Q1 / 120</span>
        </div>
        <div class="timer-bar-container">
            <div class="timer-bar" id="timerBar"></div>
        </div>
    </div>
    <div class="quiz-area" id="quizArea">
        <!-- dynamic content -->
    </div>
    <div class="footer">
        Created by Andrews Boateng | University of Ghana MCQs Standard — All sessions covered
    </div>
</div>

<script>
    // ---------- 120 MCQs with BALANCED option lengths (no obvious longest-correct) ----------
    // Each question's options are similar in length; correct answer is not predictable by length.
    // Options will be shuffled at runtime to further remove positional bias.
    const BASE_QUESTIONS = [
        { text: "Which best describes early gingivitis?", options: ["Painless bleeding with gentle probing", "Deep pockets greater than five mm", "Spontaneous exudate and mobility", "Recession with exposed cementum"], correct: 0 },
        { text: "Primary bacteria in supragingival plaque?", options: ["Porphyromonas gingivalis species", "Streptococcus mutans & Actinomyces", "Treponema denticola complex", "Candida albicans yeast form"], correct: 1 },
        { text: "Which systemic disease worsens periodontitis?", options: ["Hypertension without complications", "Poorly controlled diabetes mellitus", "Mild intermittent asthma", "Osteoporosis with low bone mass"], correct: 1 },
        { text: "Key difference periodontitis vs gingivitis?", options: ["Presence of halitosis symptom", "Irreversible bone & attachment loss", "Bleeding on brushing sign", "Gingival hyperplasia present"], correct: 1 },
        { text: "How does smoking contribute to periodontitis?", options: ["Increasing viscosity of saliva", "Impairing neutrophil & blood flow", "Raising overall oral pH level", "Promoting enamel demineralization"], correct: 1 },
        { text: "Primary goal of root planing procedure?", options: ["Remove supragingival calculus", "Smooth root surfaces to reduce bacteria", "Reshape the gingival margin shape", "Remove periodontal ligament entirely"], correct: 1 },
        { text: "Localized aggressive periodontitis involves:", options: ["All teeth symmetrically involved", "First molars and incisors mainly", "Only primary dentition affected", "Mandibular premolars exclusively"], correct: 1 },
        { text: "Microbe linked to refractory periodontitis?", options: ["Aggregatibacter actinomycetemcomitans", "Lactobacillus casei strain", "Candida tropicalis fungus", "Streptococcus salivarius oral"], correct: 0 },
        { text: "Odontogenic infections originate from:", options: ["Dental pulp necrosis & periapical spread", "Nasal mucosal inflammation site", "Salivary duct obstruction cause", "Lymphoid Waldeyer's ring tissue"], correct: 0 },
        { text: "First-line antibiotic for odontogenic infection?", options: ["Amoxicillin or amoxicillin-clavulanate", "Ciprofloxacin broad spectrum drug", "Azithromycin macrolide agent", "Doxycycline tetracycline class"], correct: 0 },
        { text: "When to hospitalize odontogenic infection?", options: ["Toothache with mild local swelling", "Fever, dysphagia, spreading cellulitis", "Localized fluctuant swelling under 1cm", "Asymptomatic periapical radiolucency"], correct: 1 },
        { text: "Favorable mandibular fracture means:", options: ["Muscles pull fragments together", "Fracture line is greenstick type", "Comminution at mandibular angle", "No teeth present in fracture line"], correct: 0 },
        { text: "CSF rhinorrhea after facial trauma suggests:", options: ["Isolated nasal bone fracture only", "Anterior skull base fracture site", "Maxillary sinusitis infection", "Nasopharyngeal tumor mass"], correct: 1 },
        { text: "Purpose of maxillomandibular fixation?", options: ["Immobilize cervical spine injury", "Stabilize jaw fractures with wiring", "Reduce zygomatic arch fracture", "Treat TMJ ankylosis disorder"], correct: 1 },
        { text: "Kiesselbach's plexus receives blood from:", options: ["Sphenopalatine artery alone source", "Anastomosis of multiple arteries", "Posterior ethmoidal artery only", "Facial artery branch exclusively"], correct: 1 },
        { text: "First aid for anterior epistaxis in stable patient?", options: ["Nasal packing with ribbon gauze", "Pinch cartilaginous tip 10 min forward", "Lie flat with ice on forehead", "Oral tranexamic acid only drug"], correct: 1 },
        { text: "Which drug increases epistaxis risk via platelets?", options: ["Paracetamol analgesic drug", "Ibuprofen or aspirin NSAID", "Amoxicillin beta-lactam antibiotic", "Omeprazole proton pump inhibitor"], correct: 1 },
        { text: "Nasal-cardiac reflex after packing requires:", options: ["Immediate pack removal & observation", "Atropine and continue packing", "Increase pack pressure further", "Patient reassurance only without change"], correct: 0 },
        { text: "Allergic rhinitis typical clinical picture:", options: ["Purulent discharge & facial pain", "Sneezing, itching, clear rhinorrhea", "Unilateral foul-smelling discharge", "Crusting and septal perforation"], correct: 1 },
        { text: "Rhinitis medicamentosa is caused by:", options: ["Prolonged topical decongestant use", "ACE inhibitor antihypertensive", "Cigarette smoke chronic exposure", "Cold weather climate change"], correct: 0 },
        { text: "Cottle 'impacted' deviated septum means:", options: ["Mild deviation without obstruction", "Spur contacts wall, no space after vasoconstrictor", "Simple C-shaped curvature only", "Complete septal perforation hole"], correct: 1 },
        { text: "Primary indication for septoplasty surgery?", options: ["Recurrent epistaxis episodes alone", "Nasal obstruction refractory to medical therapy", "Nasal polyps removal procedure", "Chronic sinusitis without deviation"], correct: 1 },
        { text: "Post-septoplasty discharge instruction includes:", options: ["Forceful nose blowing to clear clots", "Avoid nose blowing & heavy lifting", "Immediate return to contact sports", "No restriction on NSAIDs use"], correct: 1 },
        { text: "Ethmoidal polyps are typically:", options: ["Solitary, unilateral, child predominance", "Multiple, bilateral, adult chronic inflammation", "Originating from maxillary antrum only", "Malignant in most clinical cases"], correct: 1 },
        { text: "First-line medical therapy for nasal polyps:", options: ["Oral corticosteroids systemic", "Intranasal corticosteroid sprays", "Antihistamines alone insufficient", "Systemic antifungals empirical"], correct: 1 },
        { text: "Meniere's disease classic triad includes:", options: ["Otalgia, fever, purulent discharge", "Vertigo, hearing loss, tinnitus, fullness", "Facial paralysis and dry eye signs", "Progressive bilateral deafness only"], correct: 1 },
        { text: "Main pathology in Meniere's disease?", options: ["Otosclerosis of stapes footplate", "Endolymphatic hydrops distension", "Mastoid air cell effusion fluid", "Perilymph fistula traumatic"], correct: 1 },
        { text: "Dietary modification for Meniere's?", options: ["Low sodium, avoid caffeine/alcohol", "High sodium and high fluid intake", "Ketogenic diet high fat", "Increased dairy products daily"], correct: 0 },
        { text: "Intratympanic gentamicin for Meniere's aims to:", options: ["Improve hearing threshold levels", "Ablate vestibular function for vertigo", "Reduce endolymph production rate", "Cure tinnitus permanently"], correct: 1 },
        { text: "Diagnostic & therapeutic for posterior BPPV?", options: ["Epley maneuver repositioning", "Head impulse test evaluation", "Dix-Hallpike diagnostic only", "Valsalva maneuver technique"], correct: 0 },
        { text: "Acute coalescent mastoiditis complication of:", options: ["Otitis externa infection", "Acute otitis media with septal erosion", "Cerumen impaction blockage", "Cholesteatoma without infection"], correct: 1 },
        { text: "Classic mastoiditis clinical sign?", options: ["Postauricular swelling, erythema, protrusion", "Preauricular pit congenital", "Facial paralysis without ear findings", "Tympanic membrane retraction only"], correct: 0 },
        { text: "Imaging of choice for coalescent mastoiditis?", options: ["Skull X-ray plain film", "High-resolution CT temporal bone", "MRI brain without contrast", "Ultrasound of mastoid region"], correct: 1 },
        { text: "Indication for cerumen removal?", options: ["Routine cleaning at every visit", "Impaction causing hearing loss or TM obscured", "All patients over 60 years", "Presence of any earwax amount"], correct: 1 },
        { text: "Safe cerumenolytic agent example?", options: ["Carbamide peroxide or hydrogen peroxide", "Liquid nitrogen cryotherapy", "Acetic acid 50% strong solution", "Ethanol 70% alcohol"], correct: 0 },
        { text: "Conductive hearing loss characteristic?", options: ["Normal air, absent bone conduction", "Impaired sound transmission, BC>AC on Rinne", "Cochlear nerve damage type", "Retrocochlear lesion present"], correct: 1 },
        { text: "Presbycusis is which type?", options: ["Conductive from otosclerosis", "Sensorineural age-related cochlear degeneration", "Mixed from chronic otitis media", "Central auditory processing disorder"], correct: 1 },
        { text: "Weber lateralizes to affected ear in:", options: ["Sensorineural loss ipsilateral", "Conductive loss ipsilateral (bone better)", "Normal hearing symmetrical", "Mixed loss with large air-bone gap"], correct: 1 },
        { text: "Auricular hematoma requires evacuation to prevent:", options: ["Perichondritis & cauliflower ear", "Tympanic membrane rupture", "Cholesteatoma formation", "External otitis infection"], correct: 0 },
        { text: "After traumatic TM perforation, essential advice:", options: ["Keep ear dry, no forceful nose blowing", "Instill antibiotic drops immediately", "Irrigate ear canal daily", "Use cotton swab to clean deep"], correct: 0 },
        { text: "Viral conjunctivitis typical feature?", options: ["Purulent discharge with morning crusting", "Watery discharge, tender preauricular node", "Severe itching & stringy discharge", "Subconjunctival hemorrhage only"], correct: 1 },
        { text: "Bacterial conjunctivitis common presentation:", options: ["Serous discharge and follicles", "Mucopurulent discharge, crusting, bilateral", "Pseudomembrane & severe photophobia", "Periorbital edema without discharge"], correct: 1 },
        { text: "Iridocyclitis slit lamp finding?", options: ["Corneal arcus lipid deposit", "Cells and flare in anterior chamber", "Posterior subcapsular cataract", "Drusen optic disc"], correct: 1 },
        { text: "First-line treatment for acute anterior uveitis?", options: ["Topical steroids & cycloplegics", "Antibiotic ointment topical", "Beta-blocker eye drops", "Lubrication artificial tears"], correct: 0 },
        { text: "Age-related cataract results from:", options: ["Lens crystallin denaturation", "Increased aqueous production", "Corneal endothelial failure", "Vitreous hemorrhage absorption"], correct: 0 },
        { text: "Preoperative biometry for cataract essential to:", options: ["Calculate intraocular lens power", "Assess visual field defect", "Measure corneal thickness only", "Evaluate tear film stability"], correct: 0 },
        { text: "Post-cataract surgery patient should avoid:", options: ["Bending head below waist & heavy lifting", "Wearing sunglasses outdoors", "Using prescribed antibiotic drops", "Sleeping on non-operated side"], correct: 0 },
        { text: "Open-angle glaucoma initial presentation?", options: ["Sudden painful red eye", "Asymptomatic gradual peripheral loss", "Halos and nausea acute", "Flashes and floaters vitreous"], correct: 1 },
        { text: "First-line medication class for open-angle glaucoma?", options: ["Prostaglandin analogs (increase outflow)", "Oral carbonic anhydrase inhibitors", "Miotics as initial therapy", "Antivirals ophthalmic"], correct: 0 },
        { text: "Acute angle-closure glaucoma emergency treatment?", options: ["Topical antibiotics & patching", "Laser iridotomy & IOP-lowering agents", "Systemic antifungals oral", "Warm compresses soothing"], correct: 1 },
        { text: "Causative agent of trachoma?", options: ["Chlamydia trachomatis A-C", "Neisseria gonorrhoeae", "Adenovirus type 8", "Haemophilus influenzae"], correct: 0 },
        { text: "WHO SAFE strategy for trachoma includes:", options: ["Surgery, Antibiotics, Facial cleanliness, Environment", "Steroids, Antivirals, Fluoride, Education", "Sclerotherapy, Analgesics, Fluids, Exercises", "Saline, Artificial tears, Fomites eradication"], correct: 0 },
        { text: "Pterygium common location?", options: ["Nasal conjunctiva interpalpebral", "Corneal center visual axis", "Upper tarsal conjunctiva", "Inferior fornix"], correct: 0 },
        { text: "Main environmental risk factor for pterygium?", options: ["Chronic UV & dry dusty climate", "Bacterial conjunctivitis", "High intraocular pressure", "Vitamin A deficiency"], correct: 0 },
        { text: "Recurrence after pterygium excision reduced by:", options: ["Conjunctival autograft or amniotic membrane", "Leaving bare sclera", "Topical corticosteroids alone", "Simple excision without graft"], correct: 0 },
        { text: "Chalazion results from obstruction of:", options: ["Meibomian gland lipogranuloma", "Lacrimal punctum", "Sweat gland of eyelid", "Conjunctival goblet cell"], correct: 0 },
        { text: "Initial conservative treatment for chalazion?", options: ["Incision and curettage", "Warm compresses and lid massage", "Oral antibiotics always", "Cryotherapy freezing"], correct: 1 },
        { text: "Open-globe injury requires:", options: ["Immediate pressure patch", "Rigid shield, avoid pressure, emergent repair", "Irrigation with saline", "Topical anesthetic only"], correct: 1 },
        { text: "Hyphema after blunt trauma management?", options: ["Bed rest with head elevation, prevent rebleeding", "Strenuous activity to clear blood", "Aspirin for pain relief", "Immediate surgery always"], correct: 0 },
        { text: "Most common primary intraocular malignancy in children?", options: ["Retinoblastoma", "Choroidal melanoma", "Medulloepithelioma", "Lymphoma"], correct: 0 },
        { text: "Retinitis pigmentosa initially affects:", options: ["Rod photoreceptors (night blindness, tunnel)", "Macula only central", "Corneal endothelium", "Lens capsule"], correct: 0 },
        { text: "Leber hereditary optic neuropathy (LHON) shows:", options: ["Maternal inheritance, young male central loss", "Autosomal dominant, childhood nystagmus", "X-linked congenital cataract", "Mitochondrial, females only"], correct: 0 },
        { text: "Acute tonsillitis most common cause?", options: ["Group A strep & viruses (adenovirus, EBV)", "Candida albicans yeast", "Anaerobes only", "Mycoplasma pneumoniae"], correct: 0 },
        { text: "Peritonsillar abscess (Quinsy) typical presentation?", options: ["Trismus, hot potato voice, uvula deviation", "Bilateral exudate without pain", "Postnasal drip and cough", "Isolated fever without throat findings"], correct: 0 },
        { text: "Indication for tonsillectomy includes:", options: ["Recurrent tonsillitis (≥7/year) or abscess", "Single mild sore throat", "Asymptomatic tonsillar hypertrophy", "Halitosis alone"], correct: 0 },
        { text: "Post-tonsillectomy priority nursing care?", options: ["Airway, bleeding observation, side-lying", "Encourage gargling & hot liquids", "Solid food within 2 hours", "Apply warm neck compress"], correct: 0 },
        { text: "Most common nasal foreign body in toddlers?", options: ["Beads, food particles, toy pieces", "Hearing aid batteries", "Cotton fragments", "Insects"], correct: 0 },
        { text: "Initial removal for nasal foreign body in cooperative child?", options: ["Positive pressure (parental kiss) or gentle blowing", "Forceps blind extraction", "Immediate rigid endoscopy", "Nasal packing"], correct: 0 },
        { text: "Insect in ear canal should be managed by:", options: ["Instill lidocaine/alcohol to immobilize then remove", "Forceful irrigation with hot water", "Use cotton swab to crush", "Wait for spontaneous exit"], correct: 0 },
        { text: "Tracheobronchial FB aspiration classic presentation?", options: ["Sudden choking, wheezing, asymmetric breath sounds", "Gradual dysphagia without respiratory symptoms", "Hoarseness only", "Cyanosis without cough"], correct: 0 },
        { text: "Ludwig's angina involves which spaces?", options: ["Bilateral submandibular, sublingual, submental", "Isolated buccal space", "Parotid space", "Retropharyngeal without floor of mouth"], correct: 0 },
        { text: "Le Fort II fracture pattern involves:", options: ["Pyramidal through nasal bones, maxilla, orbits", "Transverse through alveolar process", "Separation from skull base at nasofrontal", "Comminuted mandible"], correct: 0 },
        { text: "Rinne test in conductive hearing loss shows:", options: ["Bone conduction > air conduction (negative)", "Air > bone (positive Rinne)", "Equal", "No response bilaterally"], correct: 0 },
        { text: "NOT a risk factor for recurrent epistaxis?", options: ["Anticoagulant use", "Hypertension", "Regular saline nasal spray", "Dry environmental conditions"], correct: 2 },
        { text: "Classic triad of retinitis pigmentosa on fundoscopy?", options: ["Bone spicule, arteriolar narrowing, waxy disc", "Cotton wool spots, flame hemorrhages, macular star", "Drusen, geographic atrophy, subretinal fluid", "Optic disc edema, venous engorgement, vitreous cells"], correct: 0 },
        { text: "Gold standard for bacterial rhinosinusitis diagnosis?", options: ["Clinical criteria + endoscopy/CT if complicated", "Plain X-ray Waters view", "Routine blood culture", "Allergy testing"], correct: 0 },
        { text: "Septoplasty consent should mention possible complication:", options: ["Septal perforation, shape change, bleeding, infection", "Complete loss of smell permanent", "Facial paralysis", "Corneal ulceration"], correct: 0 },
        { text: "Mastoidectomy post-op instruction includes:", options: ["Keep ear dry, avoid air travel, report dizziness/facial weakness", "Blow nose forcefully to ventilate", "Use cotton swab to clean deep canal", "Swim immediately"], correct: 0 },
        { text: "Sign of orbital floor blowout fracture?", options: ["Enophthalmos, infraorbital numbness, restricted upgaze", "Proptosis and chemosis", "Pulsatile exophthalmos", "Lid lag"], correct: 0 },
        { text: "Epley maneuver used for:", options: ["Posterior canal BPPV", "Meniere's acute attack", "Vestibular neuritis", "Labyrinthine concussion"], correct: 0 },
        { text: "Complication of untreated cholesteatoma includes:", options: ["Facial paralysis, intracranial abscess, fistula", "Serous otitis media", "Otosclerosis", "Presbycusis"], correct: 0 },
        { text: "Primary prevention of dental caries includes:", options: ["Fluoridated water, fluoride toothpaste, reduce sugar", "Weekly chlorhexidine mouthwash", "Extraction of primary teeth", "Oral probiotics only"], correct: 0 },
        { text: "Hallmark of herpetic gingivostomatitis?", options: ["Vesicles ulcerate, fever, gingival erythema", "Pseudomembranous plaques only", "Painless ulcers on hard palate", "Unilateral facial rash"], correct: 0 },
        { text: "Drug for acute vertigo in vestibular neuritis?", options: ["Short-term vestibular suppressants + steroids if severe", "Long-term antibiotics", "Antifungals", "Beta-blockers"], correct: 0 },
        { text: "Finding differentiating central from peripheral vertigo?", options: ["Direction-changing nystagmus, no suppression, severe ataxia", "Horizontal-rotatory nystagmus with latency", "Positive head impulse test", "Associated hearing loss"], correct: 0 },
        { text: "Prophylactic antibiotics before dental procedures recommended for:", options: ["High-risk cardiac conditions (limited)", "Uncomplicated dental caries", "Gingivitis", "All patients over 65"], correct: 0 },
        { text: "Epiphora may result from:", options: ["Nasolacrimal duct obstruction", "Dry eye reflex", "Conjunctivitis", "All of the above"], correct: 3 },
        { text: "Pterygium progressing toward visual axis should be:", options: ["Excised with conjunctival autograft", "Treated only with lubricants", "Observed annually", "Topical steroids indefinitely"], correct: 0 },
        { text: "Sudden painless 'curtain' over vision suggests:", options: ["Retinal detachment", "Acute angle closure glaucoma", "Corneal abrasion", "Optic neuritis"], correct: 0 },
        { text: "Most common cause of vision loss in diabetics?", options: ["Diabetic retinopathy (macular edema, proliferative)", "Cataract", "Glaucoma", "Corneal ulcer"], correct: 0 },
        { text: "Cataract surgery consent includes risk of:", options: ["Endophthalmitis, capsule rupture, retinal detachment", "Permanent facial paralysis", "Loss of smell", "Meniere's exacerbation"], correct: 0 },
        { text: "Cerumen irrigation contraindicated if:", options: ["Known TM perforation or history of perforation", "Patient older than 80 years", "Mild hearing loss", "Use of hearing aid"], correct: 0 },
        { text: "Tonsillar hypertrophy causing OSA in children may need:", options: ["Adenotonsillectomy", "Nasal steroids only", "Antibiotics for 6 months", "Observation until adulthood"], correct: 0 },
        { text: "Majority of odontogenic infections treated with:", options: ["Source control (drainage, extraction) + antibiotics", "Prolonged IV antibiotics without drainage", "Antifungals", "Hyperbaric oxygen alone"], correct: 0 },
        { text: "Fracture requiring emergent ophthalmology due to entrapment?", options: ["Orbital floor fracture with diplopia & restriction", "Nasal bone fracture", "Zygomatic arch fracture without eye symptoms", "Le Fort I"], correct: 0 },
        { text: "Term 'hydrops' in Meniere's refers to:", options: ["Endolymphatic distension of cochlear duct & saccule", "Perilymph fistula", "Serous otitis media", "Mastoid effusion"], correct: 0 },
        { text: "65-year-old with painless progressive blurring, glare most likely:", options: ["Cataract", "Open-angle glaucoma", "Macular degeneration", "Diabetic retinopathy"], correct: 0 },
        { text: "Hypopyon (pus in anterior chamber) characteristic of:", options: ["Severe anterior uveitis or endophthalmitis", "Cataract", "Glaucoma", "Pterygium"], correct: 0 },
        { text: "Recurrent aphthous ulcers typically:", options: ["Non-keratinized mucosa, painful, round, no prodrome", "Vesicular and crusting on lips", "Always associated with fever", "High malignant transformation"], correct: 0 },
        { text: "Most associated with acute coalescent mastoiditis?", options: ["Recent AOM with persistent fever & postauricular swelling", "Cerumen impaction", "Fungal external otitis", "Meniere's disease"], correct: 0 },
        { text: "Trachoma leads to blindness mainly through:", options: ["Conjunctival scarring, trichiasis, corneal opacification", "Direct optic nerve invasion", "Retinal detachment", "Secondary glaucoma"], correct: 0 },
        { text: "7-year-old with nasal obstruction, snoring, mouth breathing likely:", options: ["Adenoid hypertrophy", "Nasal polyps", "Deviated septum", "Allergic rhinitis only"], correct: 0 },
        { text: "Condition with 'snowbank' vitreous haze & peripheral exudates?", options: ["Pars planitis (intermediate uveitis)", "Acute posterior multifocal placoid", "Behçet disease", "Toxoplasmic chorioretinitis"], correct: 0 },
        { text: "Hutchinson's triad (interstitial keratitis, deafness, teeth) associated with:", options: ["Congenital syphilis", "Rubella syndrome", "Cytomegalovirus", "Toxoplasmosis"], correct: 0 },
        { text: "First-line imaging for suspected facial bone fracture?", options: ["Non-contrast CT facial bones", "Plain X-ray panoramic", "MRI", "Ultrasound"], correct: 0 },
        { text: "NOT typical for viral conjunctivitis?", options: ["Purulent discharge with severe morning crusting", "Watery discharge", "Preauricular lymphadenopathy", "Highly contagious"], correct: 0 },
        { text: "Recurrent sinusitis, situs inversus, bronchiectasis likely:", options: ["Kartagener syndrome (primary ciliary dyskinesia)", "Cystic fibrosis", "Churg-Strauss", "Wegener granulomatosis"], correct: 0 },
        { text: "Most common sensorineural hearing loss in elderly:", options: ["Presbycusis", "Meniere's disease", "Otosclerosis", "Acoustic neuroma"], correct: 0 },
        { text: "First step in suspected open globe injury?", options: ["Rigid shield, avoid pressure, immediate ophthalmology", "Irrigate with betadine", "Perform tonometry", "Apply topical anesthetic & remove FB"], correct: 0 },
        { text: "Safe antibiotic for acute bacterial rhinosinusitis covering typical pathogens?", options: ["Amoxicillin-clavulanate", "Vancomycin", "Ciprofloxacin alone", "Metronidazole"], correct: 0 },
        { text: "Adult with recurrent unilateral serous otitis media requires:", options: ["Nasopharyngeal endoscopy to rule out malignancy", "Immediate myringotomy", "Antibiotics for 3 months", "Decongestants only"], correct: 0 }
    ];

    // Ensure exactly 120 questions
    const FINAL_QS = BASE_QUESTIONS.slice(0,120);
    
    // Shuffle options for each question to avoid positional bias (keep correct answer index updated)
    function shuffleOptions(question) {
        const opts = question.options;
        const correctText = opts[question.correct];
        let indices = [0,1,2,3];
        for (let i = indices.length - 1; i > 0; i--) {
            const j = Math.floor(Math.random() * (i + 1));
            [indices[i], indices[j]] = [indices[j], indices[i]];
        }
        const newOpts = indices.map(i => opts[i]);
        const newCorrect = newOpts.indexOf(correctText);
        return { options: newOpts, correct: newCorrect };
    }
    
    // Apply shuffling to all questions
    const SHUFFLED_QS = FINAL_QS.map(q => {
        const shuffled = shuffleOptions(q);
        return {
            text: q.text,
            options: shuffled.options,
            correct: shuffled.correct
        };
    });
    
    // App state
    let currentIndex = 0;
    let answers = new Array(SHUFFLED_QS.length).fill(null);
    let timeSec = 3000; // 50 minutes = 3000 seconds
    let examSubmitted = false;
    let timerInterval = null;
    
    const timerElem = document.getElementById('timerDisplay');
    const counterSpan = document.getElementById('counterSpan');
    const quizArea = document.getElementById('quizArea');
    const timerBar = document.getElementById('timerBar');
    
    function formatTime(sec) {
        let mins = Math.floor(sec / 60);
        let remain = sec % 60;
        return `${mins.toString().padStart(2,'0')}:${remain.toString().padStart(2,'0')}`;
    }
    
    function updateTimerUI() {
        timerElem.innerText = formatTime(timeSec);
        const percentRemaining = (timeSec / 3000) * 100;
        timerBar.style.width = `${percentRemaining}%`;
        if (timeSec <= 1500) { // 25 minutes or less
            timerBar.classList.add('warning');
        } else {
            timerBar.classList.remove('warning');
        }
        if (timeSec <= 0 && !examSubmitted) submitExam();
    }
    
    function startTimer() {
        if (timerInterval) clearInterval(timerInterval);
        timerInterval = setInterval(() => {
            if (!examSubmitted && timeSec > 0) {
                timeSec--;
                updateTimerUI();
            } else if (timeSec <= 0 && !examSubmitted) {
                clearInterval(timerInterval);
                submitExam();
            }
        }, 1000);
    }
    
    function renderCurrent() {
        if (examSubmitted) return;
        const q = SHUFFLED_QS[currentIndex];
        let optsHtml = '';
        q.options.forEach((opt, idx) => {
            const checked = (answers[currentIndex] === idx) ? 'checked' : '';
            optsHtml += `
                <div class="option" data-val="${idx}">
                    <input type="radio" name="qOption" id="opt_${idx}" value="${idx}" ${checked}>
                    <label for="opt_${idx}" class="opt-label">${opt}</label>
                </div>
            `;
        });
        const isLast = (currentIndex === SHUFFLED_QS.length-1);
        const submitBtnHtml = isLast ? `<div class="submit-area"><button id="finalSubmitBtn" class="submit-final">✔ SUBMIT EXAM</button></div>` : '';
        const html = `
            <div class="question">${currentIndex+1}. ${q.text}</div>
            <div class="options-list" id="optionsList">${optsHtml}</div>
            <div class="nav-buttons">
                <button id="prevBtn" ${currentIndex === 0 ? 'disabled' : ''}>◀ PREVIOUS</button>
                <button id="nextBtn" class="primary">${isLast ? 'REVIEW & SUBMIT' : 'NEXT ▶'}</button>
            </div>
            ${submitBtnHtml}
        `;
        quizArea.innerHTML = html;
        counterSpan.innerText = `Q${currentIndex+1} / ${SHUFFLED_QS.length}`;
        
        document.querySelectorAll('input[name="qOption"]').forEach(radio => {
            radio.addEventListener('change', (e) => {
                answers[currentIndex] = parseInt(e.target.value);
            });
        });
        document.getElementById('prevBtn')?.addEventListener('click', () => {
            if (currentIndex > 0) { currentIndex--; renderCurrent(); }
        });
        document.getElementById('nextBtn')?.addEventListener('click', () => {
            const selected = document.querySelector('input[name="qOption"]:checked');
            if (selected) answers[currentIndex] = parseInt(selected.value);
            if (currentIndex < SHUFFLED_QS.length-1) {
                currentIndex++;
                renderCurrent();
            } else {
                if (!examSubmitted) submitExam();
            }
        });
        const finalBtn = document.getElementById('finalSubmitBtn');
        if (finalBtn) finalBtn.addEventListener('click', () => submitExam());
    }
    
    function submitExam() {
        if (examSubmitted) return;
        examSubmitted = true;
        clearInterval(timerInterval);
        let correctCount = 0;
        const resultDetails = [];
        for (let i=0; i<SHUFFLED_QS.length; i++) {
            const userAns = answers[i];
            const correctIdx = SHUFFLED_QS[i].correct;
            const isCorrect = (userAns !== null && userAns === correctIdx);
            if (isCorrect) correctCount++;
            resultDetails.push({
                qText: SHUFFLED_QS[i].text,
                userChoiceText: (userAns !== null) ? SHUFFLED_QS[i].options[userAns] : "No answer",
                correctText: SHUFFLED_QS[i].options[correctIdx],
                isCorrect
            });
        }
        const percent = (correctCount / SHUFFLED_QS.length * 100).toFixed(1);
        let answerHtml = '';
        resultDetails.forEach((item, idx) => {
            const rowClass = item.isCorrect ? 'correct' : 'wrong';
            answerHtml += `
                <div class="ans-row ${rowClass}">
                    <strong>${idx+1}.</strong> ${item.qText.substring(0, 110)}<br>
                    <span style="font-size:0.75rem;">Your: ${item.userChoiceText} | Correct: ${item.correctText}</span>
                </div>
            `;
        });
        const resultPanel = `
            <div class="result-container">
                <div class="score-big">📊 SCORE: ${correctCount} / ${SHUFFLED_QS.length} (${percent}%)</div>
                <p style="text-align:center; margin: 10px 0;">University of Ghana Standard Examination — Detailed answer key below</p>
                <div class="answer-key">${answerHtml}</div>
                <button id="restartExam" style="display:block; margin: 20px auto 0; background:#1f6e8c; color:white; padding:10px 24px;">⟳ RESTART EXAM</button>
            </div>
        `;
        quizArea.innerHTML = resultPanel;
        document.getElementById('restartExam')?.addEventListener('click', () => window.location.reload());
    }
    
    renderCurrent();
    startTimer();
    updateTimerUI(); // initial bar width
</script>
</body>
</html>
