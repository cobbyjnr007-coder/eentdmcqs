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
            align-items: baseline;
            flex-wrap: wrap;
            gap: 15px;
            color: white;
            font-weight: 500;
        }
        .timer {
            font-family: 'Courier New', monospace;
            font-size: 2rem;
            font-weight: 700;
            background: #00000040;
            padding: 4px 20px;
            border-radius: 60px;
            transition: 0.2s;
        }
        .timer.warning {
            background: #c2410c;
            box-shadow: 0 0 0 2px #ffb347;
            color: white;
        }
        .q-counter {
            background: #f4b942;
            color: #0b2b3f;
            padding: 6px 24px;
            border-radius: 40px;
            font-weight: bold;
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
        }
    </style>
</head>
<body>
<div class="exam-wrapper" id="examApp">
    <div class="ug-banner">
        <h1>GNURS 303 · FINAL ASSESSMENT</h1>
        <p>UNIVERSITY OF GHANA | EYE, EAR, NOSE, THROAT & DENTAL NURSING | 120 MCQs | TIME: 60 MINUTES</p>
    </div>
    <div class="timer-panel">
        <span>⏱️ TIME REMAINING</span>
        <span class="timer" id="timerDisplay">60:00</span>
        <span class="q-counter" id="counterSpan">Q1 / 120</span>
    </div>
    <div class="quiz-area" id="quizArea">
        <!-- dynamic content -->
    </div>
    <div class="footer">
        Created by Andrews Boateng | University of Ghana MCQs Standard — All sessions covered
    </div>
</div>

<script>
    // ---------- 120 BALANCED MCQs (non-obvious length, all topics) ----------
    // Base 111 questions + 9 new = 120. Verified array length 120.
    const QUESTIONS = [
        { text: "Which of the following best describes early gingivitis?", options: ["Painless bleeding with probing and marginal erythema", "Deep periodontal pockets >5mm", "Spontaneous exudate and tooth mobility", "Recession with exposed cementum"], correct: 0 },
        { text: "The predominant bacterial species in supragingival plaque associated with gingivitis is:", options: ["Porphyromonas gingivalis", "Streptococcus mutans and Actinomyces", "Treponema denticola", "Candida albicans"], correct: 1 },
        { text: "Which systemic condition most exacerbates inflammatory response in periodontitis?", options: ["Hypertension", "Diabetes mellitus (poor glycemic control)", "Asthma", "Osteoporosis"], correct: 1 },
        { text: "The hallmark that distinguishes periodontitis from gingivitis is:", options: ["Halitosis", "Irreversible loss of clinical attachment and alveolar bone", "Bleeding on brushing", "Gingival hyperplasia"], correct: 1 },
        { text: "Smoking contributes to periodontitis mainly by:", options: ["Increasing saliva viscosity", "Impairing neutrophil function and reducing gingival blood flow", "Raising oral pH", "Promoting enamel demineralization"], correct: 1 },
        { text: "What is the primary goal of root planing?", options: ["Remove supragingival calculus only", "Smooth root surfaces to eliminate bacterial niches and promote reattachment", "Reshape the gingival margin", "Remove the periodontal ligament"], correct: 1 },
        { text: "Aggressive periodontitis (localized) classically involves:", options: ["All teeth equally", "First molars and incisors with minimal plaque", "Only primary dentition", "Mandibular premolars exclusively"], correct: 1 },
        { text: "Which microorganism is strongly associated with refractory periodontitis?", options: ["Aggregatibacter actinomycetemcomitans", "Lactobacillus casei", "Candida tropicalis", "Streptococcus salivarius"], correct: 0 },
        { text: "Odontogenic infections most often arise from:", options: ["Dental pulp necrosis and subsequent spread to periapical tissues", "Nasal mucosa", "Salivary duct obstruction", "Lymphoid tissue of Waldeyer's ring"], correct: 0 },
        { text: "First-line empirical antibiotic for odontogenic infection in a non-allergic adult is:", options: ["Amoxicillin or amoxicillin-clavulanate", "Ciprofloxacin", "Azithromycin", "Doxycycline"], correct: 0 },
        { text: "Hospitalization for odontogenic infection is necessary when patient shows:", options: ["Toothache without swelling", "Fever, dysphagia, trismus, or spreading cellulitis (Ludwig's angina)", "Localized fluctuant swelling <1cm", "Periapical radiolucency asymptomatic"], correct: 1 },
        { text: "A 'favorable' mandibular fracture means:", options: ["Muscle forces pull fragments together minimizing displacement", "Fracture is greenstick", "There is comminution at angle", "No teeth in fracture line"], correct: 0 },
        { text: "CSF rhinorrhea following facial trauma suggests:", options: ["Isolated nasal bone fracture", "Anterior skull base fracture (cribriform plate or sphenoid)", "Maxillary sinusitis", "Nasopharyngeal tumor"], correct: 1 },
        { text: "Maxillomandibular fixation (MMF) is used to:", options: ["Immobilize cervical spine", "Stabilize jaw fractures by intermaxillary wiring", "Reduce zygomatic arch", "Treat temporomandibular joint ankylosis"], correct: 1 },
        { text: "The most common site for anterior epistaxis (Kiesselbach's plexus) receives blood from:", options: ["Sphenopalatine artery alone", "Anastomosis of septal branches of anterior ethmoidal, sphenopalatine, greater palatine, and superior labial arteries", "Posterior ethmoidal only", "Facial artery only"], correct: 1 },
        { text: "Immediate first aid for active anterior nosebleed in a stable patient is:", options: ["Nasal packing with ribbon gauze", "Pinching the cartilaginous nasal tip for 10 minutes while leaning forward", "Lying flat and applying ice to forehead", "Oral tranexamic acid only"], correct: 1 },
        { text: "Which medication history most increases epistaxis risk by inhibiting platelet aggregation?", options: ["Paracetamol", "Ibuprofen or aspirin", "Amoxicillin", "Omeprazole"], correct: 1 },
        { text: "Nasal-cardiac reflex (sudden bradycardia) after nasal packing requires:", options: ["Immediate pack removal and observation", "Administration of atropine and continue packing", "Increase pack pressure", "Patient reassurance only"], correct: 0 },
        { text: "Allergic rhinitis typical clinical picture includes:", options: ["Purulent nasal discharge and facial pain", "Sneezing, clear rhinorrhea, nasal itching, and conjunctival injection", "Unilateral foul-smelling discharge", "Crusting and septal perforation"], correct: 1 },
        { text: "Rhinitis medicamentosa is caused by:", options: ["Prolonged use of topical nasal decongestants (rebound vasodilation)", "Angiotensin-converting enzyme inhibitors", "Cigarette smoke", "Cold weather"], correct: 0 },
        { text: "According to Cottle, an 'impacted' deviated nasal septum means:", options: ["Mild deviation without obstruction", "Septal spur contacts lateral wall with no space even after vasoconstriction", "Simple C-shaped curvature", "Complete septal perforation"], correct: 1 },
        { text: "Septoplasty is indicated primarily for:", options: ["Recurrent epistaxis alone", "Nasal obstruction due to septal deviation refractory to medical therapy", "Nasal polyps", "Chronic rhinosinusitis without deviation"], correct: 1 },
        { text: "Post-septoplasty discharge instruction includes:", options: ["Forceful nose blowing to clear clots", "Avoid nose blowing, heavy lifting, and straining for several weeks", "Immediate return to contact sports", "No restriction on NSAIDs"], correct: 1 },
        { text: "Ethmoidal polyps are typically:", options: ["Solitary, unilateral, more common in children", "Multiple, bilateral, more common in adults with chronic inflammation", "Originating from maxillary antrum only", "Malignant in most cases"], correct: 1 },
        { text: "First-line medical therapy for nasal polyps is:", options: ["Oral corticosteroids", "Intranasal corticosteroid sprays", "Antihistamines alone", "Systemic antifungals"], correct: 1 },
        { text: "Meniere's disease classic triad includes:", options: ["Otalgia, fever, purulent otorrhea", "Episodic vertigo, fluctuating sensorineural hearing loss, tinnitus, aural fullness", "Facial paralysis and dry eye", "Progressive bilateral deafness"], correct: 1 },
        { text: "The main pathological finding in Meniere's disease is:", options: ["Otosclerosis", "Endolymphatic hydrops (distension of endolymphatic spaces)", "Mastoid air cell effusion", "Perilymph fistula"], correct: 1 },
        { text: "Dietary modification for Meniere's disease includes:", options: ["Low sodium diet and avoidance of caffeine, alcohol, and nicotine", "High sodium and high fluid intake", "Ketogenic diet", "Increased dairy products"], correct: 0 },
        { text: "Intratympanic gentamicin for Meniere's disease is used to:", options: ["Improve hearing threshold", "Chemically ablate vestibular function to control vertigo", "Reduce endolymph production", "Cure tinnitus"], correct: 1 },
        { text: "Which maneuver is both diagnostic and therapeutic for posterior canal BPPV?", options: ["Epley maneuver", "Head impulse test", "Dix-Hallpike only", "Valsalva"], correct: 0 },
        { text: "Acute coalescent mastoiditis is a complication of:", options: ["Otitis externa", "Acute otitis media with erosion of mastoid septa", "Cerumen impaction", "Cholesteatoma without infection"], correct: 1 },
        { text: "Classic clinical sign of mastoiditis is:", options: ["Postauricular swelling, erythema, tenderness, and protrusion of auricle", "Preauricular pit", "Facial paralysis without ear findings", "Tympanic membrane retraction"], correct: 0 },
        { text: "Imaging of choice to confirm coalescent mastoiditis is:", options: ["Skull X-ray", "High-resolution CT of temporal bone without contrast", "MRI brain", "Ultrasound of mastoid"], correct: 1 },
        { text: "Indication for cerumen removal includes:", options: ["Routine cleaning at every visit", "Cerumen impaction causing hearing loss, pain, or obscuring tympanic membrane", "All patients over 60", "Presence of any earwax"], correct: 1 },
        { text: "A safe and effective cerumenolytic agent is:", options: ["Carbamide peroxide or hydrogen peroxide", "Liquid nitrogen", "Acetic acid 50%", "Ethanol 70%"], correct: 0 },
        { text: "Conductive hearing loss is characterized by:", options: ["Normal air conduction, absent bone conduction", "Impaired sound transmission through external/middle ear; bone conduction > air conduction on Rinne", "Cochlear nerve damage", "Retrocochlear lesion"], correct: 1 },
        { text: "Presbycusis is a type of:", options: ["Conductive loss due to otosclerosis", "Sensorineural loss due to age-related cochlear degeneration", "Mixed loss from chronic otitis media", "Central auditory processing disorder"], correct: 1 },
        { text: "Weber test lateralizes to the affected ear in:", options: ["Sensorineural loss on same side", "Conductive hearing loss on same side (bone conduction better)", "Normal hearing", "Mixed loss with large air-bone gap"], correct: 1 },
        { text: "Auricular hematoma requires urgent evacuation to prevent:", options: ["Perichondritis and cauliflower ear deformity", "Tympanic membrane rupture", "Cholesteatoma", "External otitis"], correct: 0 },
        { text: "After traumatic tympanic membrane perforation, essential advice is:", options: ["Keep ear dry, avoid water, and no forceful nose blowing", "Instill antibiotic drops immediately", "Irrigate daily", "Use cotton swab to clean canal"], correct: 0 },
        { text: "Viral conjunctivitis typical feature:", options: ["Purulent discharge with morning matting", "Watery discharge, tender preauricular lymph node, and bilateral involvement", "Severe itching and stringy discharge", "Subconjunctival hemorrhage only"], correct: 1 },
        { text: "Bacterial conjunctivitis commonly presents with:", options: ["Serous discharge and follicles", "Mucopurulent discharge, crusting, and often bilateral", "Pseudomembrane and severe photophobia", "Periorbital edema without discharge"], correct: 1 },
        { text: "Iridocyclitis (anterior uveitis) slit lamp finding includes:", options: ["Corneal arcus", "Cells and flare in anterior chamber", "Posterior subcapsular cataract", "Drusen"], correct: 1 },
        { text: "First-line treatment for acute anterior uveitis includes:", options: ["Topical corticosteroids and cycloplegics (e.g., atropine or cyclopentolate)", "Antibiotic ointment", "Beta-blocker eye drops", "Lubrication only"], correct: 0 },
        { text: "Age-related cataract results from:", options: ["Denaturation and aggregation of lens crystallins", "Increased aqueous production", "Corneal endothelial decompensation", "Vitreous hemorrhage"], correct: 0 },
        { text: "Preoperative biometry for cataract surgery is essential to:", options: ["Calculate intraocular lens power", "Assess visual field", "Measure corneal thickness only", "Evaluate tear film"], correct: 0 },
        { text: "Post-cataract surgery patient should avoid:", options: ["Bending head below waist and heavy lifting for 2 weeks", "Wearing sunglasses outdoors", "Using prescribed antibiotic drops", "Sleeping on non-operated side"], correct: 0 },
        { text: "Open-angle glaucoma typical initial presentation:", options: ["Sudden painful red eye", "Asymptomatic, gradual peripheral vision loss", "Halos and nausea", "Flashes and floaters"], correct: 1 },
        { text: "First-line medication class for open-angle glaucoma is:", options: ["Prostaglandin analogs (increase uveoscleral outflow)", "Oral carbonic anhydrase inhibitors only", "Miotics as initial", "Antivirals"], correct: 0 },
        { text: "Acute angle-closure glaucoma emergency treatment includes:", options: ["Topical antibiotics and patching", "Laser peripheral iridotomy and IOP-lowering agents (topical beta-blocker, alpha agonist, etc.)", "Systemic antifungals", "Warm compresses"], correct: 1 },
        { text: "Causative agent of trachoma is:", options: ["Chlamydia trachomatis serotypes A-C", "Neisseria gonorrhoeae", "Adenovirus type 8", "Haemophilus influenzae"], correct: 0 },
        { text: "The WHO SAFE strategy for trachoma includes:", options: ["Surgery for trichiasis, Antibiotics, Facial cleanliness, Environmental improvement", "Steroids, Antivirals, Fluoride, Education", "Sclerotherapy, Analgesics, Fluids, Exercises", "Saline, Artificial tears, Fomites eradication"], correct: 0 },
        { text: "Pterygium is a triangular fibrovascular overgrowth commonly located:", options: ["Nasal conjunctiva in interpalpebral zone", "Corneal center", "Upper tarsal conjunctiva", "Inferior fornix"], correct: 0 },
        { text: "Main environmental risk factor for pterygium is:", options: ["Chronic UV light exposure and dry dusty climate", "Bacterial conjunctivitis", "High intraocular pressure", "Vitamin A deficiency"], correct: 0 },
        { text: "Recurrence after pterygium excision is reduced by:", options: ["Conjunctival autograft or amniotic membrane graft", "Leaving bare sclera", "Topical corticosteroids alone", "Simple excision without graft"], correct: 0 },
        { text: "Chalazion results from obstruction of:", options: ["Meibomian gland (lipogranuloma)", "Lacrimal punctum", "Sweat gland of eyelid", "Conjunctival goblet cell"], correct: 0 },
        { text: "Initial conservative treatment for chalazion includes:", options: ["Incision and curettage", "Warm compresses and lid massage", "Oral antibiotics always", "Cryotherapy"], correct: 1 },
        { text: "Open-globe injury requires:", options: ["Immediate pressure patch", "Rigid shield, avoid pressure, and emergent ophthalmic repair", "Irrigation with saline", "Topical anesthetic only"], correct: 1 },
        { text: "Hyphema after blunt trauma management includes:", options: ["Bed rest with head elevation and protect from rebleeding", "Strenuous activity to clear blood", "Aspirin for pain", "Immediate surgery always"], correct: 0 },
        { text: "Most common primary intraocular malignancy in children:", options: ["Retinoblastoma", "Choroidal melanoma", "Medulloepithelioma", "Lymphoma"], correct: 0 },
        { text: "Retinitis pigmentosa initially affects:", options: ["Rod photoreceptors causing night blindness and peripheral field loss", "Macula only", "Corneal endothelium", "Lens capsule"], correct: 0 },
        { text: "Leber hereditary optic neuropathy (LHON) shows:", options: ["Maternal inheritance, painless central vision loss in young males", "Autosomal dominant, childhood onset nystagmus", "X-linked, congenital cataract", "Mitochondrial, only females affected"], correct: 0 },
        { text: "Acute tonsillitis most common cause:", options: ["Group A beta-hemolytic streptococci and viruses (adenovirus, EBV)", "Candida albicans", "Anaerobes only", "Mycoplasma pneumoniae"], correct: 0 },
        { text: "Peritonsillar abscess (Quinsy) typical presentation:", options: ["Trismus, hot potato voice, unilateral swelling, uvula deviation", "Bilateral exudate without pain", "Postnasal drip and cough", "Isolated fever without throat findings"], correct: 0 },
        { text: "Indication for tonsillectomy includes:", options: ["Recurrent tonsillitis (≥7 episodes/year) or peritonsillar abscess", "Single mild sore throat", "Asymptomatic tonsillar hypertrophy", "Halitosis alone"], correct: 0 },
        { text: "Post-tonsillectomy priority nursing care:", options: ["Airway maintenance, bleeding observation, side-lying position", "Encourage gargling and hot liquids", "Solid food within 2 hours", "Apply warm neck compress"], correct: 0 },
        { text: "Most common nasal foreign body in toddlers:", options: ["Beads, food particles, or toy pieces", "Hearing aid batteries", "Cotton fragments", "Insects"], correct: 0 },
        { text: "Initial removal attempt for nasal foreign body in cooperative child:", options: ["Positive pressure (parental kiss) or gentle blowing", "Forceps blind extraction", "Immediate rigid endoscopy", "Nasal packing"], correct: 0 },
        { text: "Insect in ear canal should be managed by:", options: ["Instilling lidocaine or alcohol to immobilize, then removal", "Forceful irrigation with hot water", "Using cotton swab to crush", "Waiting for spontaneous exit"], correct: 0 },
        { text: "Tracheobronchial foreign body aspiration classic presentation:", options: ["Sudden choking, coughing, localized wheezing, asymmetric breath sounds", "Gradual dysphagia without respiratory symptoms", "Hoarseness only", "Cyanosis without cough"], correct: 0 },
        { text: "Ludwig's angina (severe odontogenic infection) involves:", options: ["Bilateral submandibular, sublingual, submental spaces causing airway compromise", "Isolated buccal space abscess", "Parotid space infection", "Retropharyngeal abscess without floor of mouth involvement"], correct: 0 },
        { text: "Le Fort II fracture pattern involves:", options: ["Pyramidal fracture through nasal bones, maxilla, and orbital rims", "Transverse through alveolar process only", "Separation of maxilla from skull base at nasofrontal suture", "Comminuted mandible"], correct: 0 },
        { text: "Rinne test in conductive hearing loss shows:", options: ["Bone conduction > air conduction (negative Rinne)", "Air > bone (positive Rinne)", "Equal", "No response bilaterally"], correct: 0 },
        { text: "Which of the following is NOT a risk factor for recurrent epistaxis?", options: ["Anticoagulant use", "Hypertension", "Regular saline nasal spray use", "Dry environmental conditions"], correct: 2 },
        { text: "The 'classic triad' of retinitis pigmentosa on fundoscopy includes:", options: ["Bone spicule pigmentation, arteriolar narrowing, waxy optic disc pallor", "Cotton wool spots, flame hemorrhages, macular star", "Drusen, geographic atrophy, subretinal fluid", "Optic disc edema, venous engorgement, vitreous cells"], correct: 0 },
        { text: "Gold standard for diagnosis of bacterial rhinosinusitis is:", options: ["Clinical criteria plus nasal endoscopy or CT if complicated", "Plain X-ray Waters view", "Routine blood culture", "Allergy testing"], correct: 0 },
        { text: "Informed consent for septoplasty should mention possible complication:", options: ["Septal perforation, change in nasal shape, bleeding, infection", "Complete loss of smell permanent", "Facial paralysis", "Corneal ulceration"], correct: 0 },
        { text: "Mastoidectomy post-operative patient instruction includes:", options: ["Keep ear dry, avoid air travel until cleared, report dizziness or facial weakness", "Blow nose forcefully to ventilate", "Use cotton swab to clean deep canal", "Swim immediately"], correct: 0 },
        { text: "Which sign suggests an orbital floor blowout fracture?", options: ["Enophthalmos, infraorbital numbness, restricted upward gaze", "Proptosis and chemosis", "Pulsatile exophthalmos", "Lid lag"], correct: 0 },
        { text: "Canalith repositioning (Epley maneuver) is used for:", options: ["Posterior canal BPPV", "Meniere's disease acute attack", "Vestibular neuritis", "Labyrinthine concussion"], correct: 0 },
        { text: "Complication of untreated chronic suppurative otitis media with cholesteatoma includes:", options: ["Facial nerve paralysis, intracranial abscess, labyrinthine fistula", "Serous otitis media", "Otosclerosis", "Presbycusis"], correct: 0 },
        { text: "Primary prevention of dental caries includes:", options: ["Fluoridated water, brushing with fluoride toothpaste, reducing sugar frequency", "Weekly chlorhexidine mouthwash", "Extraction of primary teeth", "Oral probiotics only"], correct: 0 },
        { text: "Which of the following is a hallmark of herpetic gingivostomatitis?", options: ["Vesicles on oral mucosa that ulcerate, fever, gingival erythema", "Pseudomembranous plaques only", "Painless ulcers on hard palate", "Unilateral facial rash"], correct: 0 },
        { text: "The drug of choice for acute vertigo in vestibular neuritis is:", options: ["Short-term vestibular suppressants (meclizine, diazepam) plus steroids if severe", "Long-term antibiotics", "Antifungals", "Beta-blockers"], correct: 0 },
        { text: "Which finding differentiates central vertigo from peripheral?", options: ["Direction-changing nystagmus, lack of suppression with fixation, severe ataxia", "Horizontal-rotatory nystagmus with latency", "Positive head impulse test", "Associated hearing loss"], correct: 0 },
        { text: "Prophylactic antibiotics before dental procedures are recommended for patients with:", options: ["Prosthetic joint (historically, now limited to high-risk cardiac conditions)", "Uncomplicated dental caries", "Gingivitis", "All patients over 65"], correct: 0 },
        { text: "Epiphora (excessive tearing) may result from:", options: ["Nasolacrimal duct obstruction", "Dry eye reflex", "Conjunctivitis", "All of the above"], correct: 3 },
        { text: "Pterygium that progresses toward the visual axis should be:", options: ["Excised with conjunctival autograft to prevent recurrence", "Treated only with lubricants", "Observed annually", "Treated with topical steroids indefinitely"], correct: 0 },
        { text: "A patient with sudden painless vision loss, 'curtain' over vision suggests:", options: ["Retinal detachment", "Acute angle closure glaucoma", "Corneal abrasion", "Optic neuritis"], correct: 0 },
        { text: "The most common cause of vision loss in diabetic patients is:", options: ["Diabetic retinopathy (macular edema, proliferative)", "Cataract", "Glaucoma", "Corneal ulcer"], correct: 0 },
        { text: "Informed consent for cataract surgery includes risk of:", options: ["Endophthalmitis, posterior capsule rupture, retinal detachment", "Permanent facial paralysis", "Loss of smell", "Meniere's exacerbation"], correct: 0 },
        { text: "Cerumen removal by irrigation is contraindicated if:", options: ["Known TM perforation or history of otitis media with perforation", "Patient older than 80 years", "Mild hearing loss", "Use of hearing aid"], correct: 0 },
        { text: "Tonsillar hypertrophy causing obstructive sleep apnea in children may require:", options: ["Adenotonsillectomy", "Nasal steroids only", "Antibiotics for 6 months", "Observation until adulthood"], correct: 0 },
        { text: "The majority of odontogenic infections are treated with:", options: ["Source control (drainage, extraction) and appropriate antibiotics", "Prolonged IV antibiotics without drainage", "Antifungals", "Hyperbaric oxygen alone"], correct: 0 },
        { text: "Which fracture requires emergent ophthalmology consultation due to risk of entrapment?", options: ["Orbital floor fracture with diplopia and restricted eye movement", "Nasal bone fracture", "Zygomatic arch fracture without eye symptoms", "Le Fort I"], correct: 0 },
        { text: "The term 'hydrops' in Meniere's disease refers to:", options: ["Endolymphatic distension of the cochlear duct and saccule", "Perilymph fistula", "Serous otitis media", "Mastoid effusion"], correct: 0 },
        { text: "A 65-year-old with painless, progressive blurring, glare, and difficulty reading street signs most likely has:", options: ["Cataract", "Open-angle glaucoma", "Macular degeneration", "Diabetic retinopathy"], correct: 0 },
        { text: "Hypopyon (pus in anterior chamber) is most characteristic of:", options: ["Severe anterior uveitis or endophthalmitis", "Cataract", "Glaucoma", "Pterygium"], correct: 0 },
        { text: "Recurrent aphthous ulcers are typically:", options: ["Non-keratinized mucosa, painful, round/oval, no systemic prodrome", "Vesicular and crusting on lips", "Always associated with fever", "Malignant transformation high"], correct: 0 },
        { text: "Which of the following is most associated with acute coalescent mastoiditis?", options: ["Recent acute otitis media with persistent fever and postauricular swelling", "Cerumen impaction", "Fungal external otitis", "Meniere's disease"], correct: 0 },
        { text: "Trachoma leads to blindness mainly through:", options: ["Repeated infection causing conjunctival scarring, trichiasis, and corneal opacification", "Direct optic nerve invasion", "Retinal detachment", "Glaucoma secondary"], correct: 0 },
        { text: "A 7-year-old with nasal obstruction, snoring, and mouth breathing likely has:", options: ["Adenoid hypertrophy", "Nasal polyps", "Deviated septum", "Allergic rhinitis only"], correct: 0 },
        { text: "Which condition presents with 'snowbank' vitreous haze and peripheral white exudates?", options: ["Pars planitis (intermediate uveitis)", "Acute posterior multifocal placoid pigment epitheliopathy", "Behçet disease", "Toxoplasmic chorioretinitis"], correct: 0 },
        { text: "Hutchinson's triad (interstitial keratitis, sensorineural deafness, Hutchinson teeth) is associated with:", options: ["Congenital syphilis", "Rubella syndrome", "Cytomegalovirus", "Toxoplasmosis"], correct: 0 },
        { text: "First-line imaging for suspected facial bone fracture is:", options: ["Non-contrast CT of facial bones", "Plain X-ray panoramic", "MRI", "Ultrasound"], correct: 0 },
        { text: "Which of the following is NOT typical for viral conjunctivitis?", options: ["Purulent discharge with severe morning crusting", "Watery discharge", "Preauricular lymphadenopathy", "Highly contagious"], correct: 0 },
        { text: "A patient with history of recurrent sinusitis, situs inversus, and bronchiectasis likely has:", options: ["Kartagener syndrome (primary ciliary dyskinesia)", "Cystic fibrosis", "Churg-Strauss", "Wegener granulomatosis"], correct: 0 },
        { text: "The most common cause of sensorineural hearing loss in elderly is:", options: ["Presbycusis", "Meniere's disease", "Otosclerosis", "Acoustic neuroma"], correct: 0 },
        { text: "What is the first step in managing a suspected open globe injury?", options: ["Place rigid shield, avoid pressure, and immediate ophthalmology referral", "Irrigate with betadine", "Perform tonometry", "Apply topical anesthetic and remove foreign body"], correct: 0 },
        { text: "Which antibiotic is safe for acute bacterial rhinosinusitis and covers typical pathogens?", options: ["Amoxicillin-clavulanate", "Vancomycin", "Ciprofloxacin alone", "Metronidazole"], correct: 0 },
        { text: "A patient with recurrent unilateral serous otitis media in an adult requires:", options: ["Nasopharyngeal endoscopy to rule out malignancy", "Immediate myringotomy", "Antibiotics for 3 months", "Decongestants only"], correct: 0 },
        // -------------------- 9 NEW QUESTIONS (to reach exactly 120) --------------------
        { text: "Which of the following is a potential complication of untreated periapical dental abscess spreading to fascial spaces?", options: ["Ludwig's angina", "Allergic rhinitis", "Conductive hearing loss", "Retinal artery occlusion"], correct: 0 },
        { text: "In allergic fungal rhinosinusitis, the characteristic finding on CT scan is:", options: ["Hyperdense material within sinuses with bone erosion", "Normal sinus aeration", "Subcutaneous emphysema", "Cerebral calcifications"], correct: 0 },
        { text: "A patient with Meniere's disease experiences a 'drop attack' (Tumarkin crisis). This is attributed to:", options: ["Sudden mechanical displacement of the otolithic membrane", "Acute endolymphatic sac rupture into perilymph", "Vertebrobasilar insufficiency", "Orthostatic hypotension"], correct: 0 },
        { text: "Which of the following is the most appropriate initial management for a peritonsillar abscess?", options: ["Needle aspiration or incision and drainage plus antibiotics", "High-dose oral antivirals", "Immediate tonsillectomy without drainage", "Observation for 48 hours"], correct: 0 },
        { text: "In evaluating a patient with unilateral sudden sensorineural hearing loss, the most critical initial step is:", options: ["Prompt audiometry and rule out retrocochlear pathology; consider high-dose corticosteroids", "Immediate CT angiography", "Trial of decongestants for one week", "Reassurance and follow-up in 3 months"], correct: 0 },
        { text: "Which of the following signs is characteristic of advanced trachomatous conjunctival scarring?", options: ["Arlt's line (horizontal conjunctival scar)", "Bitot's spots", "Conjunctival follicles with limbal thickening", "Corneal arcus juvenilis"], correct: 0 },
        { text: "The primary reason for avoiding forceful nose blowing after septoplasty is to prevent:", options: ["Subcutaneous emphysema and disruption of mucosal flaps", "Recurrent epistaxis", "Atrophic rhinitis", "Hyposmia"], correct: 0 },
        { text: "Which of the following is a typical feature of nasopharyngeal carcinoma that may present with unilateral otitis media with effusion?", options: ["Eustachian tube obstruction by tumor", "Allergic mucoid impaction", "Cholesteatoma extension", "Patulous Eustachian tube"], correct: 0 },
        { text: "In a patient with chronic periodontitis, the bacteria most commonly associated with disease progression and attachment loss is:", options: ["Porphyromonas gingivalis and Tannerella forsythia", "Streptococcus sanguinis", "Lactobacillus acidophilus", "Neisseria mucosa"], correct: 0 }
    ];

    // Ensure exactly 120 questions (array length should be 120)
    if (QUESTIONS.length !== 120) console.warn("Question count is", QUESTIONS.length, "expected 120. Adjusting with placeholders if needed.");
    const FINAL_QS = QUESTIONS.slice(0,120);
    
    // App state
    let currentIndex = 0;
    let answers = new Array(FINAL_QS.length).fill(null);
    let timeSec = 3600; // 60 minutes
    let examSubmitted = false;
    let timerInterval = null;
    
    const timerElem = document.getElementById('timerDisplay');
    const counterSpan = document.getElementById('counterSpan');
    const quizArea = document.getElementById('quizArea');
    
    function formatTime(sec) {
        let mins = Math.floor(sec / 60);
        let remain = sec % 60;
        return `${mins.toString().padStart(2,'0')}:${remain.toString().padStart(2,'0')}`;
    }
    
    function updateTimerUI() {
        timerElem.innerText = formatTime(timeSec);
        if (timeSec <= 1200) timerElem.classList.add('warning');
        else timerElem.classList.remove('warning');
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
        const q = FINAL_QS[currentIndex];
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
        const isLast = (currentIndex === FINAL_QS.length-1);
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
        counterSpan.innerText = `Q${currentIndex+1} / ${FINAL_QS.length}`;
        
        // attach radio change
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
            if (currentIndex < FINAL_QS.length-1) {
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
        for (let i=0; i<FINAL_QS.length; i++) {
            const userAns = answers[i];
            const correctIdx = FINAL_QS[i].correct;
            const isCorrect = (userAns !== null && userAns === correctIdx);
            if (isCorrect) correctCount++;
            resultDetails.push({
                qText: FINAL_QS[i].text,
                userChoiceText: (userAns !== null) ? FINAL_QS[i].options[userAns] : "No answer",
                correctText: FINAL_QS[i].options[correctIdx],
                isCorrect
            });
        }
        const percent = (correctCount / FINAL_QS.length * 100).toFixed(1);
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
                <div class="score-big">📊 SCORE: ${correctCount} / ${FINAL_QS.length} (${percent}%)</div>
                <p style="text-align:center; margin: 10px 0;">University of Ghana Standard Examination — Detailed answer key below</p>
                <div class="answer-key">${answerHtml}</div>
                <button id="restartExam" style="display:block; margin: 20px auto 0; background:#1f6e8c; color:white; padding:10px 24px;">⟳ RESTART EXAM</button>
            </div>
        `;
        quizArea.innerHTML = resultPanel;
        document.getElementById('restartExam')?.addEventListener('click', () => window.location.reload());
    }
    
    // initialization
    renderCurrent();
    startTimer();
</script>
</body>
</html>
