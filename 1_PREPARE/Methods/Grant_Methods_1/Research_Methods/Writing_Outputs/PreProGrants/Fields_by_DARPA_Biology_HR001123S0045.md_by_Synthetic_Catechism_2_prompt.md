
        As an expert grant writer, craft a compelling grant proposal that authentically represents the perspective of the given entity while addressing the specific requirements of the grant call. Your task is to answer the catechism questions comprehensively, ensuring alignment with the grant agency's objectives and the entity's unique capabilities.

        Entity (Technical/Perspectival Skills and Capacities):
        class FieldsWorldView:
    def __init__(self):
        self.name = "Chris Fields"
        self.description = ("A physicist and interdisciplinary researcher focusing on the foundations of cognition, "
                            "consciousness, and reality from an information-theoretic perspective")
        self.key_concepts = {
            "information_realism": "Information is the most fundamental aspect of reality, more fundamental than matter or energy.",
            "observer_dependence": "Reality is fundamentally shaped by observation and cannot be separated from the observer.",
            "active_inference": "A framework explaining how systems interact with and model their environment through prediction and error minimization.",
            "free_energy_principle": "A unifying principle explaining the behavior of self-organizing systems through the minimization of free energy.",
            "semantic_information": "Information is inherently meaningful and relational, forming the basis of reality.",
            "quantum_cognition": "Applying quantum mechanical principles to understanding cognition and consciousness.",
            "embodied_cognition": "Cognitive processes are deeply rooted in the body's interactions with the world.",
            "predictive_processing": "Perception and cognition are fundamentally predictive processes, constantly refining models of the world.",
            "measurement_problem": "The issue in quantum mechanics regarding the nature of measurement and observation, potentially linked to consciousness.",
            "context_dependence": "Context determines meaning and reality; information has no meaning without context.",
            "cognitive_illusions": "Phenomena that reveal fundamental truths about perception and reality, rather than mere errors of cognition.",
            "thermodynamics_of_cognition": "The study of energetic costs and constraints of information processing in cognitive systems.",
            "category_theory": "A mathematical framework for describing structures and relationships, potentially more fundamental than set theory for describing reality.",
            "quantum_darwinism": "A theory explaining the emergence of classical reality from quantum substrates through a process analogous to natural selection."
        }
        
    def worldview(self) -> Dict[str, Any]:
        return {
            "information_theory": {
                "importance": 10,
                "description": "The fundamental basis for understanding reality, perception, and cognition",
                "quote": "Information is more fundamental than matter or energy; it's the currency of reality."
            },
            "active_inference": {
                "importance": 10,
                "description": "A framework explaining how systems interact with and model their environment",
                "quote": "Active inference isn't just a theory of brain function; it's a theory of life itself."
            },
            "quantum_mechanics": {
                "importance": 9,
                "description": "A theory providing insights into the nature of reality, information, and potentially consciousness",
                "quote": "Quantum mechanics isn't just about particles; it's about how reality itself is structured."
            },
            "free_energy_principle": {
                "importance": 10,
                "description": "A unifying principle explaining the behavior of self-organizing systems",
                "quote": "The free energy principle is not just a theory of brain function, but a fundamental principle of self-organizing systems."
            },
            "holographic_principle": {
                "importance": 8,
                "description": "A concept suggesting reality might be encoded on a lower-dimensional boundary",
                "quote": "The holographic principle might apply not just to physics, but to cognition itself."
            },
            "interdisciplinary_approach": {
                "importance": 10,
                "description": "The necessity of integrating insights from multiple fields to understand complex phenomena",
                "quote": "Understanding the mind requires insights from physics, biology, computer science, and philosophy."
            },
            "observer_dependence": {
                "importance": 10,
                "description": "Reality is fundamentally shaped by observation",
                "quote": "The world is not 'out there' waiting to be observed; it is constructed by observation."
            },
            "information_realism": {
                "importance": 10,
                "description": "Information is the most fundamental aspect of reality",
                "quote": "The universe is not just described by information; it is information."
            },
            "semantic_information": {
                "importance": 9,
                "description": "Information is inherently meaningful and relational",
                "quote": "Reality is not made of stuff, but of semantics - meaningful relationships between bits of information."
            },
            "quantum_darwinism": {
                "importance": 8,
                "description": "A theory explaining the emergence of classical reality from quantum substrates",
                "quote": "Quantum Darwinism shows how the classical world emerges from the quantum realm through information selection."
            },
            "embodied_cognition": {
                "importance": 9,
                "description": "Cognitive processes are deeply rooted in the body's interactions with the world",
                "quote": "Cognition isn't just in the head; it involves the entire body and its environment."
            },
            "consciousness": {
                "importance": 10,
                "description": "A fundamental aspect of reality, potentially intrinsic to information processing",
                "quote": "Consciousness is not something the brain does; it's something the brain participates in."
            },
            "measurement_problem": {
                "importance": 9,
                "description": "The issue in quantum mechanics regarding the nature of measurement and observation",
                "quote": "The hard problem of consciousness and the measurement problem in quantum mechanics may be two sides of the same coin."
            },
            "context_dependence": {
                "importance": 10,
                "description": "The crucial role of context in determining meaning and reality",
                "quote": "Context isn't just important; it's everything. Without context, information has no meaning."
            },
            "cognitive_illusions": {
                "importance": 8,
                "description": "Phenomena that reveal fundamental truths about perception and reality",
                "quote": "Cognitive illusions aren't errors; they're windows into the fundamental nature of perception and reality."
            },
            "thermodynamics_of_cognition": {
                "importance": 8,
                "description": "The energetic costs and constraints of information processing in cognitive systems",
                "quote": "The costs of information processing shape the very nature of cognition and reality."
            },
            "category_theory": {
                "importance": 7,
                "description": "A mathematical framework for describing structures and relationships",
                "quote": "Category theory provides a language for describing the deep structure of reality that transcends the limitations of set theory."
            },
            "predictive_processing": {
                "importance": 9,
                "description": "Perception and cognition are fundamentally predictive processes",
                "quote": "The brain is not a passive receiver of information, but an active predictor constantly refining its models of the world."
            }
        }
    
    def implications(self) -> List[str]:
        return [
            "Reality is fundamentally informational and observer-dependent",
            "The boundary between observer and observed is fluid and context-dependent",
            "Consciousness and cognition are deeply intertwined with the physical world",
            "Perception is an active, predictive process rather than passive reception",
            "Quantum mechanics may play a crucial role in cognition and consciousness",
            "The self is a constructed model, not a fundamental entity",
            "Free will, in the libertarian sense, is likely an illusion",
            "Understanding cognition requires integrating insights from multiple disciplines",
            "The hard problem of consciousness may be resolved through information-theoretic approaches",
            "Reality might be understood as a unified information space",
            "The distinction between epistemology and ontology may be artificial",
            "Time and space are emergent properties of information flow",
            "Measurement creates reality rather than revealing pre-existing facts",
            "Consciousness might be an intrinsic aspect of information processing",
            "The universe can be understood as a vast network of semantic relationships",
            "Context is a fundamental aspect of information and meaning",
            "Cognitive illusions reveal deep truths about the nature of perception and reality",
            "The emergence of classical reality from quantum substrates can be understood through information-theoretic principles",
            "The costs of information processing have profound implications for cognition and physics",
            "The hard problem of consciousness and the measurement problem in quantum mechanics may be deeply related",
            "Category theory may provide a more fundamental language for describing reality than set theory",
            "The principles governing living systems, such as active inference, may apply to all self-organizing systems",
            "The holographic principle may apply not just to physics but to cognition and consciousness",
            "Quantum Darwinism may explain how the classical world emerges from quantum phenomena",
            "The observer-observed distinction may be an artifact of our cognitive architecture rather than a fundamental feature of reality"
        ]
    
    def stances(self) -> Dict[str, Any]:
        return {
            "physicalism": {
                "value": 5,
                "explanation": "While not rejecting physicalism outright, Fields emphasizes the fundamental role of information in reality"
            },
            "information_realism": {
                "value": 10,
                "explanation": "Information is seen as the most fundamental aspect of reality, possibly more fundamental than matter or energy"
            },
            "quantum_cognition": {
                "value": 9,
                "explanation": "Quantum mechanical principles are likely crucial for understanding cognition and consciousness"
            },
            "embodied_cognition": {
                "value": 10,
                "explanation": "Cognition is deeply intertwined with the body and its interactions with the environment"
            },
            "predictive_processing": {
                "value": 10,
                "explanation": "Perception and cognition are fundamentally predictive processes, aligning with the free energy principle"
            },
            "panpsychism": {
                "value": 7,
                "explanation": "While not explicitly endorsing panpsychism, Fields' views on information and consciousness are compatible with some forms of it"
            },
            "scientific_realism": {
                "value": 8,
                "explanation": "Advocates for a form of scientific realism, but one that acknowledges the observer-dependent nature of reality"
            },
            "emergence": {
                "value": 9,
                "explanation": "Many phenomena, including consciousness and spacetime, are seen as emergent properties of information processing"
            },
            "holism": {
                "value": 10,
                "explanation": "Emphasizes the interconnectedness of phenomena and the importance of studying systems as wholes"
            },
            "information_theoretic_semantics": {
                "value": 10,
                "explanation": "Meaning and semantics are fundamentally grounded in information-theoretic relationships"
            },
            "quantum_darwinism": {
                "value": 8,
                "explanation": "Supports the idea that classical reality emerges from quantum substrates through a process analogous to natural selection"
            },
            "contextual_realism": {
                "value": 9,
                "explanation": "Reality is fundamentally contextual, with the meaning and state of systems depending on their relationships and interactions"
            },
            "active_inference": {
                "value": 10,
                "explanation": "Sees active inference as a fundamental principle explaining the behavior of all self-organizing systems"
            },
            "free_energy_principle": {
                "value": 10,
                "explanation": "Views the free energy principle as a unifying framework for understanding cognition and self-organization"
            },
            "observer_dependent_reality": {
                "value": 10,
                "explanation": "Reality is fundamentally shaped by the act of observation and cannot be separated from the observer"
            },
            "information_thermodynamics": {
                "value": 8,
                "explanation": "The thermodynamic costs of information processing are seen as fundamental constraints on cognition and reality"
            },
            "category_theoretic_ontology": {
                "value": 7,
                "explanation": "Category theory is seen as a potentially more fundamental language for describing the structure of reality"
            }
        }
    
    def beliefs(self) -> Dict[str, bool]:
        return {
            belief: True for belief in [
                "reality_is_observer_dependent", "information_is_fundamental", "consciousness_is_fundamental",
                "cognition_extends_beyond_brain", "quantum_effects_relevant_to_cognition", "free_will_is_illusion",
                "self_is_constructed", "perception_is_active_inference", "reality_is_unified_information_space",
                "measurement_creates_reality", "time_is_emergent", "space_is_emergent", "holographic_principle_applies_to_cognition",
                "hard_problem_of_consciousness_is_solvable", "observer_and_observed_are_inseparable", "reality_is_fundamentally_semantic",
                "quantum_decoherence_explains_classical_reality", "cognition_is_quantum_computational", "information_has_physical_consequences",
                "consciousness_is_intrinsic_to_information_processing", "context_is_fundamental_to_information", "cognitive_illusions_reveal_fundamental_truths",
                "quantum_darwinism_explains_classical_emergence", "thermodynamics_constrains_cognition", "category_theory_describes_deep_structure_of_reality",
                "active_inference_applies_to_all_self_organizing_systems", "free_energy_principle_is_universal", "reality_is_fundamentally_relational",
                "information_processing_has_intrinsic_cost", "observer_observed_distinction_is_artificial"
            ]
        }
    
    def methodologies(self) -> List[str]:
        return [
            "Information theory", "Quantum mechanics", "Active inference", "Free energy principle", "Bayesian inference",
            "Category theory", "Cognitive neuroscience", "Philosophy of mind", "Computational modeling", "Interdisciplinary synthesis",
            "Quantum information theory", "Holographic models", "Graph theory", "Formal semantics", "Thermodynamics of computation",
            "Quantum cognition models", "Information-theoretic approaches to consciousness", "Predictive processing frameworks",
            "Quantum decoherence analysis", "Semantic network analysis", "Quantum Darwinism modeling", "Contextual analysis",
            "Cognitive illusion studies", "Information-theoretic cost analysis", "Holographic cognitive integration modeling",
            "Category-theoretic modeling of cognition", "Observer-dependent reality simulations", "Semantic information processing models",
            "Embodied cognition experiments", "Quantum measurement theory"
        ]
    
    def quotes(self) -> List[str]:
        return [
            "The world is not 'out there' waiting to be observed; it is constructed by observation.",
            "Consciousness is not something the brain does; it's something the brain participates in.",
            "The boundary between self and world is a matter of perspective, not ontology.",
            "Information is more fundamental than matter or energy; it's the currency of reality.",
            "Quantum mechanics isn't just about particles; it's about how reality itself is structured.",
            "Active inference isn't just a theory of brain function; it's a theory of life itself.",
            "The hard problem of consciousness is a symptom of our failure to understand the nature of information.",
            "To understand the mind, we must understand how it constructs and navigates reality.",
            "Measurement is a dialogue between observer and observed, not a one-way extraction of pre-existing facts.",
            "The self is not a thing, but a process - a continual act of self-measurement and self-modeling.",
            "Time and space are not containers for events, but emergent properties of information flow.",
            "Reality is not made of stuff, but of semantics - meaningful relationships between bits of information.",
            "The universe is not just described by information; it is information.",
            "Consciousness might be what information feels like when it's being processed.",
            "The hard problem of consciousness and the measurement problem in quantum mechanics may be two sides of the same coin.",
            "Every measurement, every observation, every interaction is a kind of computation.",
            "The observer-observed distinction is an artifact of our cognitive architecture, not a fundamental feature of reality.",
            "Quantum decoherence doesn't solve the measurement problem; it just pushes it back a step.",
            "The free energy principle is not just a theory of brain function, but a fundamental principle of self-organizing systems.",
            "Category theory provides a language for describing the deep structure of reality that transcends the limitations of set theory.",
            "Context isn't just important; it's everything. Without context, information has no meaning.",
            "Cognitive illusions aren't errors; they're windows into the fundamental nature of perception and reality.",
            "Quantum Darwinism shows how the classical world emerges from the quantum realm through information selection.",
            "The costs of information processing shape the very nature of cognition and reality.",
            "The hard problem of consciousness and the measurement problem in quantum mechanics are deeply connected. Solving one may solve the other.",
            "The brain doesn't create consciousness; it constrains it.",
            "Reality is not a collection of things, but a network of relationships.",
            "The distinction between epistemology and ontology breaks down at the quantum level.",
            "Information is physical, and physics is informational.",
            "The universe computes its own evolution."
        ]

    def key_papers(self) -> List[Dict[str, str]]:
        return [
            {"title": "If Physics Is an Information Science, What Is an Observer?", "description": "Explores the idea of observers as information-processing systems and its implications for physics and cognition."},
            {"title": "Conscious observation and the measurement problem in quantum mechanics", "description": "Discusses the role of consciousness in quantum measurement and its implications for our understanding of reality."},
            {"title": "Some consequences of the thermodynamic cost of system identification", "description": "Examines the energetic costs of perception and cognition from an information-theoretic perspective."},
            {"title": "A holographic model of cognitive integration and quantum cognition", "description": "Proposes a model of cognition based on the holographic principle and quantum information theory."},
            {"title": "Decoherence and the theory of the subject", "description": "Explores the relationship between quantum decoherence and the emergence of classical reality and subjectivity."},
            {"title": "On the reality of cognitive illusions", "description": "Examines the nature of cognitive illusions from an information-theoretic perspective, challenging traditional notions of perception and reality."},
            {"title": "Quantum Darwinism as a darwinian process", "description": "Analyzes the concept of quantum Darwinism and its implications for the emergence of classical reality from quantum substrates."},
            {
                "title": "If Physics Is an Information Science, What Is an Observer?",
                "description": "Explores the idea of observers as information-processing systems and its implications for physics and cognition."
            },
            {
                "title": "Conscious observation and the measurement problem in quantum mechanics",
                "description": "Discusses the role of consciousness in quantum measurement and its implications for our understanding of reality."
            },
            {
                "title": "Some consequences of the thermodynamic cost of system identification",
                "description": "Examines the energetic costs of perception and cognition from an information-theoretic perspective."
            },
            {
                "title": "A holographic model of cognitive integration and quantum cognition",
                "description": "Proposes a model of cognition based on the holographic principle and quantum information theory."
            },
            {
                "title": "Decoherence and the theory of the subject",
                "description": "Explores the relationship between quantum decoherence and the emergence of classical reality and subjectivity."
            },
            {
                "title": "On the reality of cognitive illusions",
                "description": "Examines the nature of cognitive illusions from an information-theoretic perspective, challenging traditional notions of perception and reality."
            },
            {
                "title": "Quantum Darwinism as a darwinian process",
                "description": "Analyzes the concept of quantum Darwinism and its implications for the emergence of classical reality from quantum substrates."
            },
            {
                "title": "Context as information: A conceptual analysis",
                "description": "Explores the nature of context from an information-theoretic perspective, with implications for cognition and semantics."
            },
            {
                "title": "Autonomy all the way down: Systems and dynamics in quantum Bayesianism",
                "description": "Investigates the connections between quantum mechanics, Bayesian inference, and the autonomy of physical systems."
            },
            {
                "title": "The Measurement Problem in Quantum Mechanics: A Phenomenological Approach",
                "description": "Proposes a new perspective on the measurement problem in quantum mechanics, emphasizing the role of the observer and information."
            }
        ]

    def simulate_perception(self, sensory_input: Dict[str, Any]) -> Dict[str, Any]:
        """
        Simulates Fields' view of perception as active inference.
        This is a simplified, conceptual representation.
        """
        prior_beliefs = self.worldview()
        predicted_input = self._generate_prediction(prior_beliefs)
        prediction_error = self._calculate_prediction_error(sensory_input, predicted_input)
        updated_beliefs = self._update_beliefs(prior_beliefs, prediction_error)
        return updated_beliefs

    def _generate_prediction(self, beliefs: Dict[str, Any]) -> Dict[str, Any]:
        # Placeholder for prediction generation based on current beliefs
        return {}

    def _calculate_prediction_error(self, actual: Dict[str, Any], predicted: Dict[str, Any]) -> float:
        # Placeholder for calculating prediction error
        return 0.0

    def _update_beliefs(self, beliefs: Dict[str, Any], error: float) -> Dict[str, Any]:
        # Placeholder for belief update based on prediction error
        return beliefs

    def information_theoretic_semantics(self, concept: str) -> Dict[str, Any]:
        """
        Represents Fields' approach to understanding meaning through information theory.
        """
        # Placeholder implementation
        return {
            "concept": concept,
            "information_content": 0.0,
            "relational_structure": {},
            "contextual_dependencies": []
        }

    def quantum_cognitive_model(self, cognitive_state: Dict[str, Any]) -> Tuple[complex, Dict[str, Any]]:
        """
        Represents a simplified quantum model of cognition, as per Fields' theories.
        """
        # Placeholder implementation
        psi = complex(1.0, 0.0)  # Quantum state
        observables = {}  # Dictionary of observable operators
        return psi, observables

    def holographic_cognitive_integration(self, perceptual_data: Dict[str, Any]) -> Dict[str, Any]:
        """
        Models cognitive integration using a holographic approach, as suggested by Fields.
        """
        # Placeholder implementation
        integrated_representation = {}
        return integrated_representation

    def observer_dependent_reality(self, observer_state: Dict[str, Any], environment: Dict[str, Any]) -> Dict[str, Any]:
        """
        Models the observer-dependent nature of reality as described by Fields.
        """
        # Placeholder implementation
        constructed_reality = {}
        # Simulate the process of reality construction through observation
        return constructed_reality

    def information_to_matter_interface(self, information: Dict[str, Any]) -> Dict[str, Any]:
        """
        Represents Fields' ideas on how information interfaces with physical reality.
        """
        # Placeholder implementation
        physical_consequences = {}
        # Model the process by which information has physical effects
        return physical_consequences

    def semantic_network_of_reality(self, concepts: List[str]) -> Dict[str, List[str]]:
        """
        Generates a semantic network representing Fields' view of reality as a web of meaningful relationships.
        """
        # Placeholder implementation
        network = {concept: [] for concept in concepts}
        # Generate connections between concepts based on Fields' theories
        return network




        Catechism (Comprehensive Project Description):
        ## Comprehensive Project Catechism

**1. Project Essence and Vision**
- What core problem or opportunity does your project address?
- Can you succinctly articulate your project's purpose without jargon?
- What inspired or initiated this project?
- How does this initiative align with your organization's mission, values, and strategy?
- What are the primary objectives and key results (OKRs) for this project?
- How does this project advance knowledge or practice in its field?

**2. Current Landscape Analysis**
- What is the current state of the art in this field?
- Who are the key players, competitors, and thought leaders?
- What are the limitations or gaps in existing solutions?
- Are there any regulatory, legal, or ethical considerations impacting this project?
- What recent technological advancements or societal shifts make this project relevant now?
- How does your project fit into or challenge current paradigms?

**3. Innovation and Methodological Approach**
- What is novel or groundbreaking about your approach?
- How does your solution differ from and improve upon existing alternatives?
- What specific technologies, methodologies, or theoretical frameworks will you use?
- Have you conducted preliminary experiments or pilot studies? What were the results?
- How scalable and adaptable is your proposed solution?
- What interdisciplinary approaches or collaborations does your project leverage?

**4. Impact and Significance Assessment**
- Who are the primary beneficiaries or target audiences?
- What quantifiable impact do you expect in the short, medium, and long term?
- How does this project contribute to long-term goals or grand challenges in the field?
- Are there any potential unintended consequences, both positive and negative?
- How will you measure, evaluate, and communicate the project's success and impact?
- What is the potential for this project to create paradigm shifts or breakthrough innovations?

**5. Comprehensive Risk Assessment**
- What are the top risks that could derail the project?
- Are there any ethical concerns or potential controversies?
- What technical challenges or obstacles do you anticipate?
- How might market conditions, geopolitical factors, or other external variables affect the project?
- What contingency plans and risk mitigation strategies do you have?
- How will you address potential resistance or skepticism from stakeholders or the public?

**6. Resource Requirements and Allocation**
- What is the estimated total budget, and how is it justified?
- How is the budget allocated across major categories (e.g., personnel, equipment, operations)?
- What human resources are required, including specific expertise and potential new hires?
- What equipment, infrastructure, or technological investments are necessary?
- Are there any critical dependencies on external resources, partnerships, or collaborations?
- How will you ensure efficient use of resources and prevent scope creep?

**7. Timeline, Milestones, and Project Management**
- What is the projected timeline from initiation to completion, including major phases?
- What are the key milestones, deliverables, and decision points?
- How have you accounted for potential delays, setbacks, or necessary iterations?
- What is the critical path for the project, and how will you manage dependencies?
- How will you track, report, and communicate progress to stakeholders?
- What project management methodologies or tools will you use to ensure efficient execution?

**8. Evaluation Framework and Success Criteria**
- What specific metrics and key performance indicators (KPIs) will you use to measure success?
- How will you conduct ongoing evaluations and mid-project assessments?
- What constitutes a minimum viable product (MVP) or initial success threshold?
- How will you gather, analyze, and incorporate user feedback and stakeholder input?
- What are your criteria for deciding to pivot, scale, or terminate the project if necessary?
- How will you ensure objectivity and rigor in your evaluation process?

**9. Team Composition and Expertise**
- Who are the key team members, and what are their roles and responsibilities?
- What unique expertise, skills, or experience does each team member bring?
- Are there any skill gaps or areas where additional expertise is needed?
- How will you foster collaboration, communication, and knowledge sharing within the team?
- What external advisors, mentors, or subject matter experts will you consult?
- How will you promote diversity, equity, and inclusion within your team and project execution?

**10. Market Analysis and Commercialization Strategy**
- Who is your target market, user base, or beneficiary group?
- What is the potential market size and growth trajectory for your solution?
- How will you price, monetize, or sustain your product/service?
- What is your go-to-market strategy, including marketing and distribution plans?
- How will you protect your intellectual property and maintain a competitive advantage?
- What partnerships or alliances might be beneficial for market penetration or scaling?

**11. Sustainability and Scalability Planning**
- How will the project sustain itself beyond the initial funding or implementation phase?
- What is the long-term vision for the project, product, or service?
- How will you scale the solution if it proves successful?
- What potential spin-off projects, applications, or research directions do you foresee?
- How will you ensure the project's environmental sustainability and social responsibility?
- What strategies will you employ to maintain relevance and adapt to changing conditions over time?

**12. Stakeholder Engagement and Communication**
- Who are the key stakeholders, both internal and external?
- How will you engage, communicate with, and manage expectations of diverse stakeholders?
- What potential resistance or opposition might you face, and how will you address it constructively?
- How will you deliver regular updates and maintain transparency throughout the project lifecycle?
- What partnerships or collaborations are crucial for success, and how will you nurture them?
- How will you leverage stakeholder expertise and feedback to improve the project?

**13. Learning, Adaptation, and Knowledge Management**
- How will you capture, document, and share lessons learned throughout the project?
- What mechanisms do you have for rapid iteration, adaptation, and continuous improvement?
- How will you encourage innovation, creative problem-solving, and calculated risk-taking within the team?
- What benchmarking or best practices will you adopt from other industries or fields?
- How will you contribute to the broader knowledge base in your field?
- What systems will you implement for effective knowledge management and organizational learning?

**14. Ethical Considerations and Responsible Innovation**
- What ethical frameworks or guidelines will you adhere to?
- How will you address potential ethical dilemmas or conflicts?
- What measures will you take to ensure data privacy, security, and responsible use of information?
- How will you consider and mitigate potential negative societal impacts of your innovation?
- What strategies will you employ to ensure fairness, transparency, and accountability?
- How will you engage with relevant ethical review boards or oversight committees?

**15. Future Outlook and Strategic Positioning**
- How does this project position your organization or field for future developments?
- What emerging trends or technologies might impact the long-term relevance of your project?
- How will you stay ahead of the curve and anticipate future challenges or opportunities?
- What is your vision for the next generation of research or innovation building on this project?
- How will you leverage the outcomes of this project to secure future funding or support?
- What is the potential for this project to create lasting change or transformation in its domain?

**16. Grant Team and Internal Coordination**
- Who are the key members of the grant team, and what are their specific roles and responsibilities?
- What criteria will you use to include team members in the grant project?
- How will you ensure that the team has the necessary expertise and skills to achieve the project's objectives?
- What internal deadlines are associated with important milestones, and how will you manage them?
- How will you foster effective communication and collaboration within the grant team?
- What strategies will you use to ensure accountability and track progress against internal deadlines?
- How will you handle potential conflicts or challenges within the team?
- What mechanisms will you put in place to ensure continuous improvement and adaptation throughout the project lifecycle?
- How will you ensure that the grant team adheres to the project's ethical guidelines and standards?



        Grant Call (Agency Requirements):
        # Broad Agency Announcement
## Biological Technologies
### BIOLOGICAL TECHNOLOGIES OFFICE
**HR001123S0045**  
**June 22, 2023**  
**HR001123S0045, Biological Technologies**  
**2**

## TABLE OF CONTENTS
1. [PART I: OVERVIEW INFORMATION](#part-i-overview-information)  
2. [PART II: FULL TEXT OF ANNOUNCEMENT](#part-ii-full-text-of-announcement)  
   1. [Funding Opportunity Description](#funding-opportunity-description)  
   2. [Award Information](#award-information)  
      1. [General Award Information](#general-award-information)  
      2. [Fundamental Research](#fundamental-research)  
   3. [Eligibility Information](#eligibility-information)  
      1. [Eligible Applicants](#eligible-applicants)  
      2. [Organizational Conflicts of Interest](#organizational-conflicts-of-interest)  
      3. [Cost Sharing/Matching](#cost-sharing-matching)  
   4. [Application and Submission Information](#application-and-submission-information)  
      1. [Address to Request Application Package](#address-to-request-application-package)  
      2. [Content and Form of Application Submission](#content-and-form-of-application-submission)  
      3. [Funding Restrictions](#funding-restrictions)  
      4. [Other Submission Information](#other-submission-information)  
   5. [Application Review Information](#application-review-information)  
      1. [Evaluation Criteria](#evaluation-criteria)  
      2. [Review of Proposals](#review-of-proposals)  
      3. [Countering Foreign Influence Program (CFIP)](#countering-foreign-influence-program-cfip)  
   6. [Award Administration Information](#award-administration-information)  
      1. [Submission Status Notifications](#submission-status-notifications)  
      2. [Administrative and National Policy Requirements](#administrative-and-national-policy-requirements)  
      3. [Reporting](#reporting)  
      4. [Electronic Systems](#electronic-systems)  
   7. [Agency Contacts](#agency-contacts)  
   8. [Other Information](#other-information)  
      1. [University Funding](#university-funding)  
   9. [APPENDIX 1 – Volume II checklist](#appendix-1-volume-ii-checklist)  

## PART I: OVERVIEW INFORMATION
- **Federal Agency Name**: Defense Advanced Research Projects Agency (DARPA), Biological Technologies Office (BTO)
- **Funding Opportunity Title**: Biological Technologies
- **Announcement Type**: Initial Announcement
- **Funding Opportunity Number**: HR001123S0045
- **North American Industry Classification System (NAICS)**: 541714
- **Assistance Listing Number (ALN)**: 12.910 Research and Technology Development
- **Dates**:
  - **Posting Date**: June 22, 2023
  - **Proposal Abstract Due Date and Time**: Abstracts may be submitted on a rolling basis until June 20, 2024, at 4:00 PM ET.
  - **Full Proposal Due Date and Time**: Proposals may be submitted on a rolling basis until June 20, 2024, at 4:00 PM ET.
  - **BAA Closing Date**: June 20, 2024
- **Concise description of the funding opportunity**: This announcement seeks revolutionary research ideas for topics not being addressed by ongoing BTO programs or other published solicitations.
- **Anticipated individual awards**: Multiple awards are anticipated.
- **Types of instruments that may be awarded**: Procurement Contract, Grant, Cooperative Agreement, Other Transaction for Prototypes, or Other Transaction for Research
- **Agency contact**:
  - **E-Mail**: BTOBAA2023@darpa.mil
  - **Mailing Address**:
    DARPA/BTO  
    ATTN: HR001123S0045  
    675 North Randolph Street  
    Arlington, VA 22203-2114

## PART II: FULL TEXT OF ANNOUNCEMENT
### 1. Funding Opportunity Description
This publication constitutes a Broad Agency Announcement (BAA) as contemplated in Federal Acquisition Regulation (FAR) 6.102(d)(2) and 35.016 and 2 CFR § 200.203. Any resultant award negotiations will follow all pertinent law and regulation, and any negotiations and/or awards for procurement contracts will use procedures under FAR 15.4, Contract Pricing, as specified in the BAA.

BTO's mission is to develop capabilities that leverage the unique properties of biology - adaption, replication, resilience and complexity, to revolutionize how the United States defends the homeland and prepares and protects its Warfighters. Research in BTO creates biotechnological capabilities that provide tactical care and restore function to injured warfighters, increase operational resilience, develop novel functional materials, and detect and protect against threats to maintain force readiness.

BTO is interested in submissions related to the following topic areas:

#### General Topic:
- Biological technology topic areas that fit the national security scope of BTO’s mission.

#### Human Performance:
- Understanding and improving treatment of and resilience in neurological health, transformative neural processing, fatigue, cognition, and optimized human performance and teaming, including in extreme conditions.
- Discovering interventions that utilize biotechnology, biochemistry, molecular biology, microbiology, neuroscience, psychology, cognitive science, social and behavioral science, and related disciplines to advance and optimize human performance and teaming, including in extreme conditions.
- Developing and leveraging technologies to advance continuous or near-continuous monitoring of physiology to elucidate mechanisms of human readiness and resilience.
- Understanding and improving interfaces between the biological and physical world to enable seamless biohybrid systems and devices.
- Developing approaches to enhance physiological resilience and performance in extreme conditions (e.g., cold weather climates) or to reduce musculoskeletal injuries via interventions that do not require genomic modifications.
- Developing technologies for rapid assessment of psychophysiological status.

#### Materials, Sensors, Processing:
- Designing novel materials, sensors, or processes that mimic or are inspired by biological systems.
- Developing technologies to leverage biological systems and enhance the acquisition and maintenance of critical and strategic organic and inorganic materials.
- Developing sustainable and controllable technologies that integrate biological systems into the built environments.
- Creating tools to understand the underlying rules defining biomolecular and biomaterial structure/function properties in order to predict desired outcomes for novel material development.
- Understanding and leveraging complex biological systems into underlying functional rules and processes to provide models that govern interactions of biological systems from biofilms to organs or ecosystems.
- Developing new computational and experimental tools and predictive capabilities for engineering of biological systems, such as cells, tissues, organs, organisms, and complex communities, to both develop new products and functional systems, as well as to gain new insights into underlying mechanisms.
- Developing new platform technologies that integrate, automate, and miniaturize the collection, processing, and analysis of biological and chemical samples.
- Developing hybrid biological/engineered systems that integrate biological organisms, components, biologically-encoded circuitry, biogenic materials, or exploit biological phenomena to surpass capabilities of abiotic equivalents.

#### Ecosystem and Environmental:
- Testing and validating new theories, methods and computational models that identify and quantify factors and principles underlying collective and interactive behaviors of biological organisms at all scales, from individual cells, to complex ecosystems.
- Developing technologies that leverage synthetic biology, living cellular systems, ecological diversity, or properties of biology to support operations in extreme environments and experimental methodologies to evaluate potential benefits of such innovations.
- Understanding the dynamics of population and ecosystem behavior to preserve equilibrium, provide strategic opportunity, mitigate impacts, or avoid catastrophe.
- Developing and leveraging new technologies for ecosystem restoration and the stabilization of agricultural production and post-disaster recovery.
- Understanding emerging threats to global food and water supplies and developing countermeasures that could be implemented on regional or global scales.
- Developing and leveraging new insights into non-human biology across and between populations, e.g., microbes, insects, plants, marine life, and how they interact with their environment.
- Leveraging biology to provide new tactical and strategic operational advantages, concealment and camouflage approaches, and bio-inorganic capabilities.
- Developing approaches using biology, biogeochemistry or materials science to mitigate or sequester anthropogenic carbon dioxide in terrestrial, marine, and post-disaster environments.

#### Biosecurity and Biosafety:
- Developing new technologies and approaches that ensure biosafety and biosecurity of biological hardware and data, as well as the safety and security of artificial intelligence (AI) technologies that can accelerate the biological research and development process.
- Developing innovative technologies that characterize novel, engineered, and/or natural emerging pathogens to prevent their spread or understand their origin.
- Developing new technologies to treat, prevent, forecast, and detect the emergence and spread of infectious diseases that have the potential to cause significant health, economic, and social burden.

#### Biomedical and Biodefense:
- Understanding causal relationships that underlie acute and chronic disease states to support warfighter health.
- Developing new technologies for the rapid, automated, and resilient manufacturing, delivery, and distribution of critical molecules for applications in therapeutics, chemical and biological defense.
- Developing new technologies to support next-generation cellular therapeutic applications.
- Developing new platform technologies for targeted, effective, spatiotemporally controlled delivery of large and small molecules and biologics.
- Leveraging biotechnology to create new platform solutions that combat antimicrobial resistance, generate novel drug and cell-based therapeutics, and treat warfighter injury and illness.
- Developing novel diagnostic, prophylactic, and therapeutic approaches for warfighter injury that can be provided even in austere settings and extreme conditions.

In conjunction with this announcement, BTO intends to publish Special Notices (SNs) in support of targeted studies associated with the above listed topic areas. Proposal Abstracts and Full Proposals submitted in response to these SNs will be evaluated and selected in accordance with Section 5 of this solicitation.

### 2. Award Information
#### 2.1. GENERAL AWARD INFORMATION
Multiple awards are possible. The amount of resources made available under this BAA will depend on the quality of the proposals received and the availability of funds.

The Government reserves the right to select for negotiation all, some, one, or none of the proposals received in response to this solicitation and to make awards without discussions with proposers. The Government also reserves the right to conduct discussions if it is later determined to be necessary. If warranted, portions of resulting awards may be segregated into pre-priced options. Additionally, DARPA reserves the right to accept proposals in their entirety or to select only portions of proposals for award. In the event that DARPA desires to award only portions of a proposal, negotiations may be opened with that proposer. The Government reserves the right to fund proposals in phases with options for continued work, as applicable.

The Government reserves the right to request any additional, necessary documentation once it makes the award instrument determination. Such additional information may include but is not limited to Representations and Certifications (see Section 6.2.3, “Representations and Certifications”). The Government reserves the right to remove proposers from award consideration should the parties fail to reach agreement on award terms, conditions, and/or cost/price within a reasonable time, and the proposer fails to timely provide requested additional information. Proposals identified for negotiation may result in a procurement contract, cooperative agreement, or other transaction, depending upon the nature of the work proposed, the required degree of interaction between parties, whether or not the research is classified as Fundamental Research, and other factors.

Proposers looking for innovative, commercial-like contractual arrangements are encouraged to consider requesting Other Transactions. To understand the flexibility and options associated with Other Transactions, consult [DARPA Contract Management](http://www.darpa.mil/work-with-us/contractmanagement#OtherTransactions).

In accordance with 10 U.S.C. § 4022(f), the Government may award a follow-on production contract or Other Transaction (OT) for any OT awarded under this solicitation if: (1) that participant in the OT, or a recognized successor in interest to the OT, successfully completed the entire prototype project provided for in the OT, as modified; and (2) the OT provides for the award of a follow-on production contract or OT to the participant, or a recognized successor in interest to the OT.

In all cases, the Government contracting officer shall have sole discretion to select award instrument type, regardless of instrument type proposed, and to negotiate all instrument terms and conditions with selectees. DARPA will apply publication or other restrictions, as necessary, if it determines that the research resulting from the proposed effort will present a high likelihood of disclosing performance characteristics of military systems or manufacturing technologies that are unique and critical to defense. Any award resulting from such a determination will include a requirement for DARPA permission before publishing any information or results on the program. For more information on publication restrictions, see the section below on Fundamental Research.

#### 2.2. FUNDAMENTAL RESEARCH
It is DoD policy that the publication of products of fundamental research will remain unrestricted to the maximum extent possible. National Security Decision Directive (NSDD) 189 defines fundamental research as follows:

> ‘Fundamental research’ means basic and applied research in science and engineering, the results of which ordinarily are published and shared broadly within the scientific community, as distinguished from proprietary research and from industrial development, design, production, and product utilization, the results of which ordinarily are restricted for proprietary or national security reasons.

As of the date of publication of this solicitation, the Government cannot identify whether the work under this solicitation may be considered fundamental research and may award both fundamental and non-fundamental research.

University or non-profit research institution performance under this solicitation may include effort categorized as fundamental research. In addition to Government support for free and open scientific exchanges and dissemination of research results in a broad and unrestricted manner, the academic or non-profit research performer or recipient, regardless of tier, acknowledges that such research may have implications that are important to U.S. national interests and must be protected against foreign influence and exploitation. As such, the academic or non-profit research performer or recipient agrees to comply with the following requirements:

(a) The University or non-profit research institution performer or recipient must establish and maintain an internal process or procedure to address foreign talent programs, conflicts of commitment, conflicts of interest, and research integrity. The academic or non-profit research performer or recipient must also utilize due diligence to identify Foreign Components or participation by Senior/Key Personnel in Foreign Government Talent Recruitment Programs and agree to share such information with the Government upon request.
  - i. The above described information will be provided to the Government as part of the proposal response to the solicitation and will be reviewed and assessed prior to award. Generally, this information will be included in the Research and Related Senior/Key Personnel Profile (Expanded) form (SF-424) required as part the proposer’s submission through Grants.gov.
    1. Instructions regarding how to fill out the SF-424 and its biographical sketch can be found through Grants.gov.
  - ii. In accordance with USD(R&E) direction to mitigate undue foreign influence in DoD-funded science and technology, DARPA will assess all Senior/Key Personnel proposed to support DARPA grants and cooperative agreements for potential undue foreign influence risk factors relating to professional and financial activities. This will be done by evaluating information provided via the SF-424, and any accompanying or referenced documents, in order to identify and assess any associations or affiliations the Senior/Key Personnel may have with foreign strategic competitors or countries that have a history of intellectual property theft, research misconduct, or history of targeting U.S. technology for unauthorized transfer. DARPA’s evaluation takes into consideration the entirety of the Senior/Key Personnel’s SF-424, current and pending support, and biographical sketch, placing the most weight on the Senior/Key Person’s professional and financial activities over the last 4 years. The majority of foreign entities lists used to make these determinations are publicly available. The DARPA Countering Foreign Influence Program (CFIP) “Senior/Key Personnel Foreign Influence Risk Rubric” details the various risk ratings and factors. The rubric can be seen at the following link: [DARPA CFIP Rubric](https://www.darpa.mil/attachments/092021DARPACFIPRubric.pdf)
  - iii. Examples of lists that DARPA leverages to assess potential undue foreign influence factors include, but are not limited to:
    1. Executive Order 13959 “Addressing the Threat From Securities Investments That Finance Communist Chinese Military Companies”: [Executive Order 13959](https://www.govinfo.gov/content/pkg/FR-2020-11-17/pdf/2020-25459.pdf)
    2. The U.S. Department of Education’s College Foreign Gift and Contract Report: [College Foreign Gift Reporting](https://www2.ed.gov/finaid/prof/resources/foreign-gifts/index.html)
    3. The U.S. Department of Commerce, Bureau of Industry and Security, List of Parties of Concern: [List of Parties of Concern](https://www.bis.doc.gov/index.php/policy-guidance/lists-of-parties-of-concern)
    4. Georgetown University’s Center for Security and Emerging Technology (CSET) Chinese Talent Program Tracker: [Chinese Talent Program Tracker](https://chinatalenttracker.cset.tech)
    5. Director of National Intelligence (DNI) “World Wide Threat Assessment of the US Intelligence Community”: [2021 Annual Threat Assessment of the U.S. Intelligence Community](https://www.dni.gov/files/ODNI/documents/assessments/ATA-2021-Unclassified-Report.pdf)
    6. Various Defense Counterintelligence and Security Agency (DCSA) products regarding targeting of US technologies, adversary targeting of academia, and the exploitation of academic experts: [DCSA](https://www.dcsa.mil/)
(b) DARPA’s analysis and assessment of affiliations and associations of Senior/Key Personnel is compliant with Title VI of the Civil Rights Act of 1964. Information regarding race, color, or national origin is not collected and does not have bearing in DARPA’s assessment.
(c) University or non-profit research institutions with proposals selected for negotiation that have been assessed as having high or very high undue foreign influence risk, will be given an opportunity during the negotiation process to mitigate the risk. DARPA reserves the right to request any follow-up information needed to assess risk or mitigation strategies.
  - i. Upon conclusion of the negotiations, if DARPA determines, despite any proposed mitigation terms (e.g. mitigation plan, alternative research personnel), the participation of any Senior/Key Research Personnel still represents high risk to the program, or proposed mitigation affects the Government’s confidence in proposer’s capability to successfully complete the research (e.g., less qualified Senior/Key Research Personnel) the Government may determine not to award the proposed effort. Any decision not to award will be predicated upon reasonable disclosure of the pertinent facts and reasonable discussion of any possible alternatives while balancing program award timeline requirements.
Broad Agency Announcement
Biological Technologies
BIOLOGICAL TECHNOLOGIES OFFICE
HR001123S0045
June 22, 2023
HR001123S0045, Biological Technologies
2
TABLE OF CONTENTS
PART I: OVERVIEW INFORMATION ....................................................................................3
PART II: FULL TEXT OF ANNOUNCEMENT.......................................................................4
1. Funding Opportunity Description....................................................................................4
2. Award Information............................................................................................................7
2.1. General Award Information ..........................................................................................7
2.2. Fundamental Research ..................................................................................................8
3. Eligibility Information.....................................................................................................13
3.1. Eligible Applicants ......................................................................................................13
3.2. Organizational Conflicts of Interest ............................................................................14
3.3. Cost Sharing/Matching................................................................................................15
4. Application and Submission Information .....................................................................15
4.1. Address to Request Application Package....................................................................15
4.2. Content and Form of Application Submission ............................................................15
4.3. Funding Restrictions....................................................................................................32
4.4. Other Submission Information ....................................................................................32
5. Application Review Information ....................................................................................32
5.1. Evaluation Criteria ......................................................................................................32
5.2. Review of Proposals....................................................................................................33
5.2.4. Countering Foreign Influence Program (CFIP) ...................................................34
6. Award Administration Information ..............................................................................34
6.1. Submission Status Notifications..................................................................................34
6.2. Administrative and National Policy Requirements .....................................................34
6.3. Reporting .....................................................................................................................35
6.4. Electronic Systems ......................................................................................................36
7. Agency Contacts...............................................................................................................36
8. Other Information ...........................................................................................................36
8.1. University Funding......................................................................................................36
9. APPENDIX 1 – Volume II checklist ..............................................................................38
HR001123S0045, Biological Technologies
3
PART I: OVERVIEW INFORMATION
 Federal Agency Name – Defense Advanced Research Projects Agency (DARPA),
Biological Technologies Office (BTO)
 Funding Opportunity Title – Biological Technologies
 Announcement Type – Initial Announcement
 Funding Opportunity Number – HR001123S0045
 North American Industry Classification System (NAICS) – 541714
 Assistance Listing Number (ALN) – 12.910 Research and Technology
Development
 Dates
o Posting Date: June 22, 2023
o Proposal Abstract Due Date and Time: Abstracts may be submitted on a
rolling basis until June 20, 2024, at 4:00 PM ET.
o Full Proposal Due Date and Time: Proposals may be submitted on a rolling
basis until June 20, 2024, at 4:00 PM ET.
o BAA Closing Date: June 20, 2024
 Concise description of the funding opportunity – This announcement seeks
revolutionary research ideas for topics not being addressed by ongoing BTO programs or
other published solicitations.
 Anticipated individual awards – Multiple awards are anticipated.
 Types of instruments that may be awarded – Procurement Contract, Grant,
Cooperative Agreement, Other Transaction for Prototypes, or Other Transaction for
Research
 Agency contact
o E-Mail: BTOBAA2023@darpa.mil
o Mailing Address:
DARPA/BTO
ATTN: HR001123S0045
675 North Randolph Street
Arlington, VA 22203-2114
HR001123S0045, Biological Technologies
4
PART II: FULL TEXT OF ANNOUNCEMENT
1. Funding Opportunity Description
This publication constitutes a Broad Agency Announcement (BAA) as contemplated in
Federal Acquisition Regulation (FAR) 6.102(d)(2) and 35.016 and 2 CFR § 200.203. Any
resultant award negotiations will follow all pertinent law and regulation, and any negotiations
and/or awards for procurement contracts will use procedures under FAR 15.4, Contract Pricing,
as specified in the BAA.
BTO's mission is to develop capabilities that leverage the unique properties of biology -
adaption, replication, resilience and complexity, to revolutionize how the United States defends
the homeland and prepares and protects its Warfighters. Research in BTO creates
biotechnological capabilities that provide tactical care and restore function to injured warfighters,
increase operational resilience, develop novel functional materials, and detect and protect against
threats to maintain force readiness.
BTO is interested in submissions related to the following topic areas:
General Topic:
 Biological technology topic areas that fit the national security scope of BTO’s
mission.
Human Performance:
 Understanding and improving treatment of and resilience in neurological health,
transformative neural processing, fatigue, cognition, and optimized human
performance and teaming, including in extreme conditions.
 Discovering interventions that utilize biotechnology, biochemistry, molecular
biology, microbiology, neuroscience, psychology, cognitive science, social and
behavioral science, and related disciplines to advance and optimize human
performance and teaming, including in extreme conditions.
 Developing and leveraging technologies to advance continuous or near-continuous
monitoring of physiology to elucidate mechanisms of human readiness
and resilience.
 Understanding and improving interfaces between the biological and physical world to
enable seamless biohybrid systems and devices.
 Developing approaches to enhance physiological resilience and performance in
extreme conditions (e.g., cold weather climates) or to reduce musculoskeletal injuries
via interventions that do not require genomic modifications.
HR001123S0045, Biological Technologies
5
 Developing technologies for rapid assessment of psychophysiological status.
Materials, Sensors, Processing:
 Designing novel materials, sensors, or processes that mimic or are inspired by
biological systems.
 Developing technologies to leverage biological systems and enhance the acquisition
and maintenance of critical and strategic organic and inorganic materials.
 Developing sustainable and controllable technologies that integrate biological
systems into the built environments.
 Creating tools to understand the underlying rules defining biomolecular and
biomaterial structure/function properties in order to predict desired outcomes for
novel material development.
 Understanding and leveraging complex biological systems into underlying functional
rules and processes to provide models that govern interactions of biological systems
from biofilms to organs or ecosystems.
 Developing new computational and experimental tools and predictive capabilities for
engineering of biological systems, such as cells, tissues, organs, organisms, and
complex communities, to both develop new products and functional systems, as well
as to gain new insights into underlying mechanisms.
 Developing new platform technologies that integrate, automate, and miniaturize the
collection, processing, and analysis of biological and chemical samples.
 Developing hybrid biological/engineered systems that integrate biological
organisms, components, biologically-encoded circuitry, biogenic materials, or exploit
biological phenomena to surpass capabilities of abiotic equivalents.
Ecosystem and Environmental:
 Testing and validating new theories, methods and computational models that identify
and quantify factors and principles underlying collective and interactive behaviors of
biological organisms at all scales, from individual cells, to complex ecosystems.
 Developing technologies that leverage synthetic biology, living cellular systems,
ecological diversity, or properties of biology to support operations in extreme
environments and experimental methodologies to evaluate potential benefits of such
innovations.
 Understanding the dynamics of population and ecosystem behavior to preserve
equilibrium, provide strategic opportunity, mitigate impacts, or avoid catastrophe.
HR001123S0045, Biological Technologies
6
 Developing and leveraging new technologies for ecosystem restoration and the
stabilization of agricultural production and post-disaster recovery.
 Understanding emerging threats to global food and water supplies and developing
countermeasures that could be implemented on regional or global scales.
 Developing and leveraging new insights into non-human biology across and between
populations, e.g., microbes, insects, plants, marine life, and how they interact with
their environment.
 Leveraging biology to provide new tactical and strategic operational advantages,
concealment and camouflage approaches, and bio-inorganic capabilities.
 Developing approaches using biology, biogeochemistry or materials science to
mitigate or sequester anthropogenic carbon dioxide in terrestrial, marine, and postdisaster environments.
Biosecurity and Biosafety:
 Developing new technologies and approaches that ensure biosafety and biosecurity
of biological hardware and data, as well as the safety and security of artificial
intelligence (AI) technologies that can accelerate the biological research and
development process.
 Developing innovative technologies that characterize novel, engineered, and/or
natural emerging pathogens to prevent their spread or understand their origin.
 Developing new technologies to treat, prevent, forecast, and detect the emergence and
spread of infectious diseases that have the potential to cause significant health,
economic, and social burden.
Biomedical and Biodefense:
 Understanding causal relationships that underlie acute and chronic disease states to
support warfighter health.
 Developing new technologies for the rapid, automated, and resilient manufacturing,
delivery, and distribution of critical molecules for applications in therapeutics,
chemical and biological defense.
 Developing new technologies to support next-generation cellular therapeutic
applications.
 Developing new platform technologies for targeted, effective, spatiotemporally
controlled delivery of large and small molecules and biologics.
HR001123S0045, Biological Technologies
7
 Leveraging biotechnology to create new platform solutions that combat antimicrobial
resistance, generate novel drug and cell-based therapeutics, and treat warfighter injury
and illness.
 Developing novel diagnostic, prophylactic, and therapeutic approaches for warfighter
injury that can be provided even in austere settings and extreme conditions.
In conjunction with this announcement, BTO intends to publish Special Notices (SNs) in
support of targeted studies associated with the above listed topic areas. Proposal Abstracts
and Full Proposals submitted in response to these SNs will be evaluated and selected in
accordance with Section 5 of this solicitation.
2. Award Information
2.1. GENERAL AWARD INFORMATION
Multiple awards are possible. The amount of resources made available under this BAA will
depend on the quality of the proposals received and the availability of funds.
The Government reserves the right to select for negotiation all, some, one, or none of the
proposals received in response to this solicitation and to make awards without discussions with
proposers. The Government also reserves the right to conduct discussions if it is later determined
to be necessary. If warranted, portions of resulting awards may be segregated into pre-priced
options. Additionally, DARPA reserves the right to accept proposals in their entirety or to select
only portions of proposals for award. In the event that DARPA desires to award only portions of
a proposal, negotiations may be opened with that proposer. The Government reserves the right to
fund proposals in phases with options for continued work, as applicable.
The Government reserves the right to request any additional, necessary documentation once it
makes the award instrument determination. Such additional information may include but is not
limited to Representations and Certifications (see Section 6.2.3, “Representations and
Certifications”). The Government reserves the right to remove proposers from award
consideration should the parties fail to reach agreement on award terms, conditions, and/or
cost/price within a reasonable time, and the proposer fails to timely provide requested additional
information. Proposals identified for negotiation may result in a procurement contract,
cooperative agreement, or other transaction, depending upon the nature of the work proposed, the
required degree of interaction between parties, whether or not the research is classified as
Fundamental Research, and other factors.
Proposers looking for innovative, commercial-like contractual arrangements are encouraged to
consider requesting Other Transactions. To understand the flexibility and options associated with
Other Transactions, consult http://www.darpa.mil/work-with-us/contractmanagement#OtherTransactions.
In accordance with 10 U.S.C. § 4022(f), the Government may award a follow-on production
contract or Other Transaction (OT) for any OT awarded under this solicitation if: (1) that
participant in the OT, or a recognized successor in interest to the OT, successfully completed the 
HR001123S0045, Biological Technologies
8
entire prototype project provided for in the OT, as modified; and (2) the OT provides for the
award of a follow-on production contract or OT to the participant, or a recognized successor in
interest to the OT.
In all cases, the Government contracting officer shall have sole discretion to select award
instrument type, regardless of instrument type proposed, and to negotiate all instrument terms
and conditions with selectees. DARPA will apply publication or other restrictions, as necessary,
if it determines that the research resulting from the proposed effort will present a high likelihood
of disclosing performance characteristics of military systems or manufacturing technologies that
are unique and critical to defense. Any award resulting from such a determination will include a
requirement for DARPA permission before publishing any information or results on the
program. For more information on publication restrictions, see the section below on Fundamental
Research
2.2. FUNDAMENTAL RESEARCH
It is DoD policy that the publication of products of fundamental research will remain unrestricted
to the maximum extent possible. National Security Decision Directive (NSDD) 189 defines
fundamental research as follows:
‘Fundamental research’ means basic and applied research in science and engineering, the
results of which ordinarily are published and shared broadly within the scientific
community, as distinguished from proprietary research and from industrial development,
design, production, and product utilization, the results of which ordinarily are restricted
for proprietary or national security reasons.
As of the date of publication of this solicitation, the Government cannot identify whether the
work under this solicitation may be considered fundamental research and may award both
fundamental and non-fundamental research.
University or non-profit research institution performance under this solicitation may include
effort categorized as fundamental research. In addition to Government support for free and open
scientific exchanges and dissemination of research results in a broad and unrestricted manner, the
academic or non-profit research performer or recipient, regardless of tier, acknowledges that
such research may have implications that are important to U.S. national interests and must be
protected against foreign influence and exploitation. As such, the academic or non-profit
research performer or recipient agrees to comply with the following requirements:
(a) The University or non-profit research institution performer or recipient must establish
and maintain an internal process or procedure to address foreign talent programs,
conflicts of commitment, conflicts of interest, and research integrity. The academic or
non-profit research performer or recipient must also utilize due diligence to identify
Foreign Components or participation by Senior/Key Personnel in Foreign Government
Talent Recruitment Programs and agree to share such information with the Government
upon request.
i. The above described information will be provided to the Government as part of
the proposal response to the solicitation and will be reviewed and assessed prior
to award. Generally, this information will be included in the Research and Related 
HR001123S0045, Biological Technologies
9
Senior/Key Personnel Profile (Expanded) form (SF-424) required as part the
proposer’s submission through Grants.gov.
1. Instructions regarding how to fill out the SF-424 and its biographical
sketch can be found through Grants.gov.
ii. In accordance with USD(R&E) direction to mitigate undue foreign influence in
DoD-funded science and technology, DARPA will assess all Senior/Key
Personnel proposed to support DARPA grants and cooperative agreements for
potential undue foreign influence risk factors relating to professional and financial
activities. This will be done by evaluating information provided via the SF-424,
and any accompanying or referenced documents, in order to identify and assess
any associations or affiliations the Senior/Key Personnel may have with foreign
strategic competitors or countries that have a history of intellectual property theft,
research misconduct, or history of targeting U.S. technology for unauthorized
transfer. DARPA’s evaluation takes into consideration the entirety of the
Senior/Key Personnel’s SF-424, current and pending support, and biographical
sketch, placing the most weight on the Senior/Key Person’s professional and
financial activities over the last 4 years. The majority of foreign entities lists used
to make these determinations are publicly available. The DARPA Countering
Foreign Influence Program (CFIP) “Senior/Key Personnel Foreign Influence Risk
Rubric” details the various risk ratings and factors. The rubric can be seen at the
following link:
https://www.darpa.mil/attachments/092021DARPACFIPRubric.pdf
iii. Examples of lists that DARPA leverages to assess potential undue foreign
influence factors include, but are not limited to:
1. Executive Order 13959 “Addressing the Threat From Securities
Investments That Finance Communist Chinese Military Companies”:
https://www.govinfo.gov/content/pkg/FR-2020-11-17/pdf/2020-25459.pdf
2. The U.S. Department of Education’s College Foreign Gift and Contract
Report: College Foreign Gift Reporting (ed.gov)
3. The U.S. Department of Commerce, Bureau of Industry and Security, List
of Parties of Concern: https://www.bis.doc.gov/index.php/policyguidance/lists-of-parties-of-concern
4. Georgetown University’s Center for Security and Emerging Technology
(CSET) Chinese Talent Program Tracker:
https://chinatalenttracker.cset.tech
5. Director of National Intelligence (DNI) “World Wide Threat Assessment
of the US Intelligence Community”: 2021 Annual Threat Assessment of
the U.S. Intelligence Community (dni.gov)
6. Various Defense Counterintelligence and Security Agency (DCSA)
products regarding targeting of US technologies, adversary targeting of
academia, and the exploitation of academic experts: https://www.dcsa.mil/ 
HR001123S0045, Biological Technologies
10
(b) DARPA’s analysis and assessment of affiliations and associations of
Senior/Key Personnel is compliant with Title VI of the Civil Rights Act of
1964. Information regarding race, color, or national origin is not collected and
does not have bearing in DARPA’s assessment.
(c) University or non-profit research institutions with proposals selected for
negotiation that have been assessed as having high or very high undue foreign
influence risk, will be given an opportunity during the negotiation process to
mitigate the risk. DARPA reserves the right to request any follow-up
information needed to assess risk or mitigation strategies.
i. Upon conclusion of the negotiations, if DARPA determines, despite any proposed
mitigation terms (e.g. mitigation plan, alternative research personnel), the
participation of any Senior/Key Research Personnel still represents high risk to
the program, or proposed mitigation affects the Government’s confidence in
proposer’s capability to successfully complete the research (e.g., less qualified
Senior/Key Research Personnel) the Government may determine not to award the
proposed effort. Any decision not to award will be predicated upon reasonable
disclosure of the pertinent facts and reasonable discussion of any possible
alternatives while balancing program award timeline requirements.
(d) Failure of the academic or non-profit research performer or recipient to reasonably
exercise due diligence to discover or ensure that neither it nor any of its Senior/Key
Research Personnel involved in the subject award are participating in a Foreign
Government Talent Program or have a Foreign Component with an a strategic competitor
or country with a history of targeting U.S. technology for unauthorized transfer may
result in the Government exercising remedies in accordance with federal law and
regulation.
i. If, at any time, during performance of this research award, the academic or nonprofit research performer or recipient should learn that it, its Senior/Key Research
Personnel, or applicable team members or subtier performers on this award are or
are believed to be participants in a Foreign Government Talent Program or have
Foreign Components with a strategic competitor or country with a history of
targeting U.S. technology for unauthorized transfer , the performer or recipient
will notify the Government Contracting Officer or Agreements Officer within 5
business days.
1. This disclosure must include specific information as to the personnel
involved and the nature of the situation and relationship. The Government
will have 30 business days to review this information and conduct any
necessary fact-finding or discussion with the performer or recipient.
2. The Government’s timely determination and response to this disclosure
may range anywhere from acceptance, to mitigation, to termination of this
award at the Government’s discretion.
3. If the University receives no response from the Government to its
disclosure within 30 business days, it may presume that the Government
has determined the disclosure does not represent a threat. 
HR001123S0045, Biological Technologies
11
ii. The performer or recipient must flow down this provision to any subtier contracts
or agreements involving direct participation in the performance of the research.
(e) Definitions
i. Senior/Key Research Personnel
1. This definition would include the Principal Investigator or
Program/Project Director and other individuals who contribute to the
scientific development or execution of a project in a substantive,
measurable way, whether or not they receive salaries or compensation
under the award. These include individuals whose absence from the
project would be expected to impact the approved scope of the project.
2. Most often, these individuals will have a doctorate or other professional
degrees, although other individuals may be included within this definition
on occasion.
ii. Foreign Associations/Affiliations
1. Association is defined as collaboration, coordination or interrelation,
professionally or personally, with a foreign government-connected entity
where no direct monetary or non-monetary reward is involved.
2. Affiliation is defined as collaboration, coordination, or interrelation,
professionally or personally, with a foreign government-connected entity
where direct monetary or non-monetary reward is involved.
iii. Foreign Government Talent Recruitment Programs
1. In general, these programs will include any foreign-state-sponsored
attempt to acquire U.S. scientific-funded research or technology through
foreign government-run or funded recruitment programs that target
scientists, engineers, academics, researchers, and entrepreneurs of all
nationalities working and educated in the U.S.
2. Distinguishing features of a Foreign Government Talent Recruitment
Program may include:
a. Compensation, either monetary or in-kind, provided by the foreign
state to the targeted individual in exchange for the individual
transferring their knowledge and expertise to the foreign country.
b. In-kind compensation may include honorific titles, career
advancement opportunities, promised future compensation or other
types of remuneration or compensation.
c. Recruitment, in this context, refers to the foreign-state-sponsor’s
active engagement in attracting the targeted individual to join the
foreign-sponsored program and transfer their knowledge and
expertise to the foreign state. The targeted individual may be
employed and located in the U.S. or in the foreign state. 
HR001123S0045, Biological Technologies
12
d. Contracts for participation in some programs that create conflicts
of commitment and/or conflicts of interest for researchers. These
contracts include, but are not limited to, requirements to attribute
awards, patents, and projects to the foreign institution, even if
conducted under U.S. funding, to recruit or train other talent
recruitment plan members, circumventing merit-based processes,
and to replicate or transfer U.S.-funded work in another country.
e. Many, but not all, of these programs aim to incentivize the targeted
individual to physically relocate to the foreign state. Of particular
concern are those programs that allow for continued employment
at U.S. research facilities or receipt of U.S. Government research
funding while concurrently receiving compensation from the
foreign state.
3. Foreign Government Talent Recruitment Programs DO NOT include:
a. Research agreements between the University and a foreign entity,
unless that agreement includes provisions that create situations of
concern addressed elsewhere in this section,
b. Agreements for the provision of goods or services by commercial
vendors, or
c. Invitations to attend or present at conferences.
iv. Conflict of Interest
1. A situation in which an individual, or the individual’s spouse or dependent
children, has a financial interest or financial relationship that could
directly and significantly affect the design, conduct, reporting, or funding
of research.
v. Conflict of Commitment
1. A situation in which an individual accepts or incurs conflicting obligations
between or among multiple employers or other entities.
2. Common conflicts of commitment involve conflicting commitments of
time and effort, including obligations to dedicate time in excess of
institutional or funding agency policies or commitments. Other types of
conflicting obligations, including obligations to improperly share
information with, or withhold information from, an employer or funding
agency, can also threaten research security and integrity and are an
element of a broader concept of conflicts of commitment.
vi. Foreign Component
1. Performance of any significant scientific element or segment of a program
or project outside of the U.S., either by the University or by a researcher
employed by a foreign organization, whether or not U.S. government
funds are expended.
2. Activities that would meet this definition include, but are not limited to:
HR001123S0045, Biological Technologies
13
a. Involvement of human subjects or animals;
b. Extensive foreign travel by University research program or project
staff for the purpose of data collection, surveying, sampling, and
similar activities;
c. Collaborations with investigators at a foreign site anticipated to
result in co-authorship;
d. Use of facilities or instrumentation at a foreign site;
e. Receipt of financial support or resources from a foreign entity; or
f. Any activity of the University that may have an impact on U.S.
foreign policy through involvement in the affairs or environment
of a foreign country.
3. Foreign travel is not considered a Foreign Component.
vii. Strategic Competitor
1. A nation, or nation-state, that engages in diplomatic, economic or
technological rivalry with the United States where the fundamental
strategic interests of the U.S are under threat.
Proposers should indicate in their proposal whether they believe the scope of the research
included in their proposal is fundamental or not. While proposers should clearly explain the
intended results of their research, the Government shall have sole discretion to determine
whether the proposed research shall be considered fundamental and to select the award
instrument type. Appropriate language will be included in resultant awards for non-fundamental
research to prescribe publication requirements and other restrictions, as appropriate. This
language can be found at http://www.darpa.mil/work-with-us/additional-baa.
For certain research projects, it may be possible that although the research to be performed by a
potential awardee is non-fundamental research, its proposed subawardee’s effort may be
fundamental research. It is also possible that the research performed by a potential awardee is
fundamental research while its proposed subawardee’s effort may be non-fundamental research.
In all cases, it is the potential awardee’s responsibility to explain in its proposal which proposed
efforts are fundamental research and why the proposed efforts should be considered fundamental
research.
3. Eligibility Information
3.1. ELIGIBLE APPLICANTS
All responsible sources capable of satisfying the Government's needs may submit a proposal that
shall be considered by DARPA. Historically Black Colleges and Universities, Small Businesses,
Small Disadvantaged Businesses and Minority Institutions are encouraged to submit proposals
and join others in submitting proposals; however, no portion of this announcement will be set
aside for these organizations’ participation due to the impracticality of reserving discrete or
severable areas of this research for exclusive competition among these entities.
HR001123S0045, Biological Technologies
14
3.1.1. Federally Funded Research and Development Centers (FFRDCs) and Government
Entities
FFRDCs
FFRDCs are subject to applicable direct competition limitations and cannot propose to this
solicitation in any capacity unless they meet the following conditions. (1) FFRDCs must clearly
demonstrate that the proposed work is not otherwise available from the private sector. (2)
FFRDCs must provide a letter, on official letterhead from their sponsoring organization, that (a)
cites the specific authority establishing their eligibility to propose to Government solicitations
and compete with industry, and (b) certifies the FFRDC’s compliance with the associated
FFRDC sponsor agreement’s terms and conditions. These conditions are a requirement for
FFRDCs proposing to be awardees or subawardees.
Government Entities
Government Entities (e.g., Government/National laboratories, military educational institutions,
etc.) are subject to applicable direct competition limitations. Government Entities must clearly
demonstrate that the work is not otherwise available from the private sector and provide written
documentation citing the specific statutory authority and contractual authority, if relevant,
establishing their ability to propose to Government solicitations and compete with industry. This
information is required for Government Entities proposing to be awardees or subawardees.
Authority and Eligibility
At the present time, DARPA does not consider 15 U.S.C. § 3710a to be sufficient legal authority
to show eligibility. While 10 U.S.C.§ 4892 may be the appropriate statutory starting point for
some entities, specific supporting regulatory guidance, together with evidence of agency
approval, will still be required to fully establish eligibility. DARPA will consider FFRDC and
Government Entity eligibility submissions on a case-by-case basis; however, the burden to prove
eligibility for all team members rests solely with the proposer.
3.1.2. Non-U.S. Organizations
Non-U.S. organizations and/or individuals may participate to the extent that such participants
comply with any necessary nondisclosure agreements, security regulations, export control laws,
and other governing statutes applicable under the circumstances.
3.2. ORGANIZATIONAL CONFLICTS OF INTEREST
FAR 9.5 Requirements
In accordance with FAR 9.5, proposers are required to identify and disclose all facts relevant to
potential OCIs involving the proposer’s organization and any proposed team member
(subawardee, consultant). Under this Section, the proposer is responsible for providing this
disclosure with each proposal submitted to the solicitation. The disclosure must include the
proposer’s, and as applicable, proposed team member’s OCI mitigation plan. The OCI mitigation
plan must include a description of the actions the proposer has taken, or intends to take, to
prevent the existence of conflicting roles that might bias the proposer’s judgment and to prevent
the proposer from having unfair competitive advantage. The OCI mitigation plan will
specifically discuss the disclosed OCI in the context of each of the OCI limitations outlined in
FAR 9.505-1 through FAR 9.505-4.
HR001123S0045, Biological Technologies
15
Agency Supplemental OCI Policy
In addition, DARPA has a supplemental OCI policy that prohibits contractors/performers from
concurrently providing Scientific Engineering Technical Assistance (SETA), Advisory and
Assistance Services (A&AS) or similar support services and being a technical performer.
Therefore, as part of the FAR 9.5 disclosure requirement above, a proposer must affirm whether
the proposer or any proposed team member (subawardee, consultant) is providing SETA, A&AS,
or similar support to any DARPA office(s) under: (a) a current award or subaward; or (b) a past
award or subaward that ended within one calendar year prior to the proposal’s submission date.
If SETA, A&AS, or similar support is being or was provided to any DARPA office(s), the
proposal must include:
 The name of the DARPA office receiving the support;
 The prime contract number;
 Identification of proposed team member (subawardee, consultant) providing the support; and
 An OCI mitigation plan in accordance with FAR 9.5.
Government Procedures
In accordance with FAR 9.503, 9.504 and 9.506, the Government will evaluate OCI mitigation
plans to avoid, neutralize or mitigate potential OCI issues before award and to determine whether
it is in the Government’s interest to grant a waiver. The Government will only evaluate OCI
mitigation plans for proposals that are determined selectable under the solicitation evaluation
criteria and funding availability.
The Government may require proposers to provide additional information to assist the
Government in evaluating the proposer’s OCI mitigation plan.
If the Government determines that a proposer failed to fully disclose an OCI; or failed to provide
the affirmation of DARPA support as described above; or failed to reasonably provide additional
information requested by the Government to assist in evaluating the proposer’s OCI mitigation
plan, the Government may reject the proposal and withdraw it from consideration for award.
3.3. COST SHARING/MATCHING
Cost sharing is not required; however, it will be carefully considered where there is an applicable
statutory condition relating to the selected funding instrument. Cost sharing is encouraged where
there is a reasonable probability of a potential commercial application related to the proposed
research and development effort.
4. Application and Submission Information
4.1. ADDRESS TO REQUEST APPLICATION PACKAGE
This announcement, any attachments, and any references to external websites herein constitute
the total solicitation. If proposers cannot access the referenced material posted in the
announcement found at http://www.darpa.mil, contact the administrative contact listed herein.
4.2. CONTENT AND FORM OF APPLICATION SUBMISSION 
HR001123S0045, Biological Technologies
16
All submissions, including abstracts and proposals, must be written in English with type no
smaller than 12-point font. Smaller font may be used for figures, tables, and charts. The page
limitation includes all figures, tables, and charts. All pages shall be formatted for printing on 8-
1/2 by 11-inch paper. Margins must be 1-inch on all sides. Copies of all documents submitted
must be clearly labeled with the DARPA BAA number, proposer organization, and proposal
title/proposal short title.
4.2.1. Proposal Abstract Format
Proposers are strongly encouraged to submit an abstract in advance of a proposal to minimize
effort and reduce the potential expense of preparing an out of scope proposal. DARPA will
respond to abstracts providing feedback and indicating whether, after preliminary review, there
is interest within BTO for the proposed work. DARPA will attempt to reply within 14 calendar
days of receipt. Proposals may be submitted irrespective of comments or feedback received in
response to the abstract. Proposals are reviewed without regard to feedback given as a result of
abstract review. The time and date for submission of proposal abstracts are specified in Part I
above.
The abstract is a concise version of the proposal comprising a maximum of 2 pages, including
all figures, tables, and charts. All submissions must be written in English with type no smaller
than 12-point font. Smaller font may be used for figures, tables, and charts. All pages shall be
formatted for printing on 8-1/2 by 11-inch paper. Margins must be 1-inch on all sides. Copies
of all documents submitted must be clearly labeled with the DARPA BAA number, proposer
organization, and proposal abstract title.
The page limit does NOT include:
 Official transmittal letter (optional);
 Cover sheet;
 Resumes (optional); and
 Bibliography (optional).
Abstracts must include the following components:
A. Cover Sheet (does not count towards page limit): Include the administrative and
technical points of contact (name, address, phone, fax, e-mail, lead organization). Also
include the BAA number, title of the proposed project, primary subcontractors,
estimated cost, duration of the project, and the label “ABSTRACT.”
B. Goals and Impact: Clearly describe what is being proposed and what difference it
will make (qualitatively and quantitatively), including brief answers to the following
questions:
1. What is the proposed work attempting to accomplish or do?
2. How is it done today? And what are the limitations?
3. What is innovative in your approach, and how does it compare to the current
state-of-the-art (SOA)? 
HR001123S0045, Biological Technologies
17
4. What are the key technical challenges in your approach, and how do you plan to
overcome these?
5. Who will care, and what will the impact be if you are successful?
6. How much will it cost, and how long will it take?
C. Technical Plan: Outline and address all technical challenges inherent in the
approach and possible solutions for overcoming potential problems. This section should
provide appropriate specific milestones (quantitative, if possible) at intermediate stages
of the project to demonstrate progress, and a brief plan for accomplishment of the
milestones provided.
D. Management and Capabilities: Provide a brief summary of expertise of the team,
including subcontractors and key personnel. A principal investigator for the project
must be identified. Include a description of the team’s organization, including roles and
responsibilities. Describe the organizational experience in this area, existing intellectual
property required to complete the project, and any specialized facilities to be used as
part of the project. List Government-furnished materials or data assumed to be
available.
E. Cost and Schedule: Provide a cost estimate for resources over the proposed
timeline of the project, broken down by phase and major cost items (e.g., labor,
materials, etc.). Include cost estimates for each potential subcontractor (may be a rough
order of magnitude).
F. Biosketches/Curriculum Vitae/Resumes (Optional, does not count towards page
limit): Include CVs of no more than two (2) key team members, one of which must be
from/for the Principal Investigator (PI). There is no prescribed format.
G. Bibliography/References (Optional, does not count towards page limit): If
desired, include a brief list of references cited in the abstract with links to relevant
papers and reports. The references list should not exceed two (2) pages.
4.2.2. Proposal Format
All full proposals must be in the format given below. Proposals shall consist of two volumes: 1)
Volume I, Technical and Management Proposal, and 2) Volume II, Cost Proposal. All
submissions must be written in English with type no smaller than 12-point font. A smaller font
may be used for figures, tables, and charts. The page limitation includes all figures, tables, and
charts. All pages shall be formatted for printing on 8-1/2 by 11- inch paper. Margins must be 1-
inch on all sides. Copies of all documents submitted must be clearly labeled with the DARPA
BAA number, proposer organization, and proposal title/proposal short title. Volume I, Technical
and Management Proposal, may include an attached bibliography of relevant technical papers or
research notes (published and unpublished) which document the technical ideas and approach
upon which the proposal is based. Copies of not more than three (3) relevant papers may be
included with the submission. The bibliography and attached papers are not included in the page
counts given below. The submission of other supporting materials along with the proposals is
strongly discouraged and will not be considered for review. The maximum page count for 
HR001123S0045, Biological Technologies
18
Volume 1 is 25 pages. The official transmittal letter is not included in the page count. Volume I
should include the following components:
a. Volume I, Technical and Management Proposal
Section I. Administrative
A. Cover Sheet (LABELED “PROPOSAL: VOLUME I”):
1. BAA number (HR001123S0045);
2. Lead organization submitting proposal (prime contractor);
3. Type of organization, selected from among the following categories: “LARGE
BUSINESS,” “SMALL DISADVANTAGED BUSINESS,” “8A,” “VETERANOWNED SMALL BUSINESS,” “WOMAN-OWNED BUSINESS,” “OTHER SMALL
BUSINESS,” “HBCU,” “MI,” “OTHER EDUCATIONAL,” “HOSPITAL,” “OTHER
NONPROFIT,” OR “FOREIGN CONCERN OR ENTITY”;
4. Proposer’s reference number (if any);
5. Other team members (if applicable) and type of business for each;
6. Proposal title;
7. Technical point of contact (Program Manager or Principal Investigator) to include:
salutation, last name, first name, street address, city, state, zip code, telephone, fax, email;
8. Administrative point of contact (Contracting Officer or Award Officer) to include:
salutation, last name, first name, street address, city, state, zip code, telephone, fax, email;
9. Award instrument requested: cost-plus-fixed-free (CPFF), cost-contract—no fee, cost
sharing contract – no fee, or other type of procurement contract (specify), cooperative
agreement, or other transaction;
10. Place(s) of performance, including all subcontractors and consultants;
11. Period of performance;
12. Total funds requested from DARPA, total funds requested per phase and the amount of
any cost share (if any);
13. Proposal validity period; AND
14. Date proposal was submitted.
Information on award instruments is available at http://www.darpa.mil/work-with-us/contractmanagement.
B. Official Transmittal Letter.
Section II. Detailed Proposal Information
HR001123S0045, Biological Technologies
19
A. Executive Summary: Provide a synopsis of the proposed project, including answers to
the following questions:
 What is the proposed work attempting to accomplish or do?
 How is it done today, and what are the limitations?
 What is innovative in your approach?
 What are the key technical challenges in your approach, and how do you plan to
overcome these?
 Who or what will be affected, and what will be the impact if the work is successful?
 How much will it cost, and how long will it take?
B. Goals and Impact: Clearly describe what the team is trying to achieve and the
difference it will make (qualitatively and quantitatively) if successful. Describe the
innovative aspects of the project in the context of existing capabilities and approaches,
clearly delineating the uniqueness and benefits of this project in the context of the state
of the art, alternative approaches, and other projects from the past and present. Describe
how the proposed project is revolutionary and how it significantly rises above the
current state-of-the-art. Describe the deliverables associated with the proposed project
and any plans to commercialize the technology, transition it to a customer, or further
the work.
C. Technical Plan: Outline and address technical challenges inherent in the approach and
possible solutions for overcoming potential problems. This section should provide
appropriate measurable milestones (quantitative if possible) at intermediate stages of
the proposed research to demonstrate progress, and a plan for achieving the milestones.
The technical plan should demonstrate a deep understanding of the technical challenges
and present a credible (even if risky) plan to achieve the proposal’s stated goal. Discuss
mitigation of technical risk.
D. Management Plan: Provide a summary of expertise of the team, including any
subcontractors, and key personnel who will be doing the work. A Principal Investigator
(PI) for the project must be identified, along with a clear description of the team’s
organization, including an organization chart that includes, as applicable: the
programmatic relationship of team members; the unique capabilities of team members;
the task responsibilities of team members, the teaming strategy among the team
members; and key personnel with the amount of effort to be expended by each person
during each year. Provide a detailed plan for coordination, including explicit guidelines
for interaction among collaborators/subcontractors of the proposed effort. Include risk
management approaches. Describe any formal teaming agreements that are required to
execute the proposed research. 
HR001123S0045, Biological Technologies
20
E. Capabilities: Describe organizational experience in relevant subject area(s), existing
intellectual property, specialized facilities, and any Government-furnished materials or
information. Discuss any work in closely related research areas and previous
accomplishments.
F. Statement of Work (SOW): The SOW should provide a detailed task breakdown, citing
specific tasks for each Technical Area, and their connection to the milestones and
program metrics. If applicable, each phase of the proposed research should be separately
defined. The SOW must not include proprietary information.
For each task/subtask, provide:
 A detailed description of the approach to be taken to accomplish each defined
task/subtask.
 Identification of the primary organization responsible for task execution (prime
contractor, subcontractor(s), consultant(s), by name).
 A measurable milestone, i.e., a deliverable, demonstration, or other event/activity
that marks task completion. Include completion dates for all milestones. Include
quantitative metrics.
 A definition of all deliverables (e.g., data, reports, software) to be provided to the
Government in support of the proposed tasks/subtasks.
G. Schedule and Milestones: Provide a detailed schedule showing tasks (task name,
duration, work breakdown structure element as applicable, performing organization),
milestones, and the interrelationships among tasks. The task structure must be
consistent with that in the SOW. Measurable milestones should be clearly articulated
and defined in time relative to the start of the project.
Section III. Additional Information
Provide a list of technical references cited in Section II of the proposal that document
the technical ideas upon which the proposal is based. Copies of not more than three (3)
papers germane to the technical proposal and important for documenting the feasibility
of proposed approach may be included in the submission.
b. Volume II, Cost Management Proposal
Cover Sheet (LABELED “PROPOSAL: VOLUME II”):
1. BAA Number (HR001123S0045);
2. Lead Organization Submitting proposal; 
HR001123S0045, Biological Technologies
21
3. Type of organization, selected among the following categories: “LARGE BUSINESS,”
“SMALL DISADVANTAGED BUSINESS,” “8A,” “VETERAN-OWNED SMALL
BUSINESS,” “WOMAN-OWNED BUSINESS,” “OTHER SMALL BUSINESS,”
“HBCU,” “MI,” “OTHER EDUCATIONAL,” “HOSPITAL,” “OTHER
NONPROFIT,” OR “FOREIGN CONCERN OR ENTITY”;
4. Proposer’s reference number (if any);
5. Other team members (if applicable) and type of business for each;
6. Proposal title;
7. Technical point of contact (Program Manager or Principal Investigator) to include:
salutation, last name, first name, street address, city, state, zip code, telephone, fax (if
available), electronic mail (if available);
8. Administrative point of contact (Contracting Officer or Award Officer) to include:
salutation, last name, first name, street address, city, state, zip code, telephone, fax (if
available), and electronic mail (if available);
9. Award instrument requested: cost-plus-fixed-free (CPFF), cost-contract—no fee, cost
sharing contract – no fee, or other type of procurement contract (specify), GRANT,
cooperative agreement, or other transaction;
10. Place(s) of performance, including all subcontractors and consultants;
11. Period of performance;
12. Total funds requested from DARPA, total funds requested per phase (as defined in
Table 1), and the amount of any cost share (if any);
13. Name, address, and telephone number of the proposer’s cognizant Defense Contract
Management Agency (DCMA) administration office (if known);
14. Name, address, and telephone number of the proposer’s cognizant Defense Contract
Audit Agency (DCAA) audit office (if known);
15. Date proposal was prepared;
16. Unique Entity ID (https://sam.gov/content/duns-uei);
17. Taxpayer ID number (https://www.irs.gov/Individuals/InternationalTaxpayers/Taxpayer-Identification-Numbers-TIN);
18. Commercial and Government Entity (CAGE) code
(https://cage.dla.mil/Home/UsageAgree);
19. Proposal validity period
The Government requires that proposers* use the provided MS ExcelTM DARPA Standard Cost
Proposal Spreadsheet in the development of their cost proposals. A customized cost proposal
spreadsheet may be an attachment to this solicitation. If not, the spreadsheet can be found on the
DARPA website at http://www.darpa.mil/work-with-us/contract-management (under
“Resources” on the right-hand side of the webpage). All tabs and tables in the cost proposal
spreadsheet should be developed in an editable format with calculation formulas intact to allow
traceability of the cost proposal. This cost proposal spreadsheet should be used by the prime
organization and all subcontractors. In addition to using the cost proposal spreadsheet, the cost
proposal still must include all other items required in this announcement that are not covered by 
HR001123S0045, Biological Technologies
22
the editable spreadsheet. Subcontractor cost proposal spreadsheets may be submitted directly to
the Government by the proposed subcontractor via e-mail to the address in Part I of this
solicitation. Using the provided cost proposal spreadsheet will assist the Government in a
rapid analysis of your proposed costs and, if your proposal is selected for a potential
award, speed up the negotiation and award execution process.
*University proposers requesting a grant, cooperative agreement, or Other Transaction for
Research do not need to use the MS ExcelTM DARPA Standard Cost Proposal Spreadsheet.
Instead, a proposed budget and justification may be provided using the SF-424 Research &
Related Budget forms provided via https://www.grants.gov.
(1) Total program, per phase (if applicable), and per task cost broken down by major
cost items to include:
i. Direct Labor – provide an itemized breakout of all personnel, listed by
name or TBD, with labor rate (or salary), labor hours (or percent effort),
and labor category. All senior personnel must be identified by name.
ii. Materials and Supplies – itemized list which includes description of
material, quantity, unit price, and total price. If a material factor is used
based on historical purchases, provide data to justify the rate.
iii. Equipment – itemized list which includes description of equipment, unit
price, quantity, and total price. Any equipment item with a unit price over
$5,000 must include a vendor quote.
iv. Animal Use Costs – itemized list of all materials, animal purchases, and
per diem costs, associated with proposed animal use; include
documentation supporting daily rates.
v. Travel – provide an itemized list of travel costs to include purpose of
trips, departure and arrival destinations, projected airfare, rental car and
per GSA approved diem, number of travelers, number of days); provide
screenshots from travel website for proposed airfare and rental car, as
applicable; provide screenshot or web link for conference registration fee
and note if the fee includes hotel cost. Conference attendance must be
justified, explain how it is in the best interest of the project.
vi. Other Direct Costs (e.g., computer support, clean room fees) – Should
be itemized with costs or estimated costs. Backup documentation and/or a
supporting cost breakdown is required to support proposed costs with a
unit price over $5,000. An explanation of any estimating factors, including
their derivation and application, must be provided. Please include a brief
description of the proposers’ procurement method to be used.
vii. Other Direct Costs – Consultants: provide executed Consultant
Agreement that describes work scope, rate and hours.
viii. Indirect costs including, as applicable, fringe benefits, overhead, General
and Administrative (G&A) expense, and cost of money (see university vs.
company specific requirements below).
ix. Indirect costs specific to a University performer: (1) Fringe Benefit
Rate (provide current Department of Health and Human Services (DHHS)
or Office of Naval Research (ONR) negotiated rate package; if calculated
by other than a rate, provide University documentation identifying fringe 
HR001123S0045, Biological Technologies
23
costs by position or HR documentation if unique to each person); (2) F&A
Indirect Overhead Rate (provide current DHHS or ONR negotiated rate
package); (3) Tuition Remission (provide current University
documentation justifying per-student amount); and (4) Health
Insurance/Fee (provide current University documentation justifying per
student amount, if priced separately from fringe benefits with calculations
included in the EXCEL cost file).
Indirect costs specific to a Company performer: (1) Fee/Profit
(provide rationale for proposed fee/profit percentage using criteria found
in DFARS 215.404-70); and (2) Fringe Benefit/Labor OH/Material
OH/G&A Rates (provide current Forwarding Pricing Rate Proposal
(FPRP) or DCMA/DCAA Forward Pricing Rate Recommendation or
Agreement (FPRR or FPRA). If these documents are not available,
provide company historical data, preferably two years, minimum of one,
to include both pool and expense costs used to generate the rates).
(2) A summary of total program costs by phase (if applicable) and task.
(3) An itemization of Subcontracts. All subcontractor cost proposal documentation
must be prepared at the same level of detail as that required of the prime.
Subcontractor proposals should include Interdivisional Work Transfer
Agreements (IWTA) or evidence of similar arrangements (an IWTA is an
agreement between multiple divisions of the same organization). The prime
proposer is responsible for compiling and providing all subcontractor proposals
for the Procuring Contracting Officer (PCO). The proposal must show how
subcontractor costs are applied to each phase and task. If consultants are to be
used, proposer must provide consultant agreement or other document that verifies
the proposed loaded daily/hourly rate.
(4) An itemization of any information technology (IT) purchase (including a letter
stating why the proposer cannot provide the requested resources from its own
funding), as defined in FAR Part 2.101.
(5) A summary of projected funding requirements by month for the duration of the
project.
(6) A summary of tasks that have animal use or human subjects research funding.
(7) The source, nature, and amount of any industry cost-sharing. Where the effort
consists of multiple portions that could reasonably be partitioned for purposes of
funding, these should be identified as options with separate cost estimates for
each.
(8) Identification of pricing assumptions of which may require incorporation into the
resulting award instrument (e.g., use of Government Furnished
Property/Facilities/Information, access to Government Subject Matter Expert/s,
etc.).
(9) Any Forward Pricing Rate Agreement, DHHS rate agreement, other such
approved rate information, or such documentation that may assist in expediting
negotiations (if available).
(10) Proposers with a Government acceptable accounting system who are proposing a
cost-type contract must submit the DCAA document approving the cost
accounting system.
HR001123S0045, Biological Technologies
24
Per FAR 15.403-4, certified cost or pricing data shall be required if the proposer is seeking a
procurement contract award per the referenced threshold, unless the proposer requests and is
granted an exception from the requirement to submit cost or pricing data. Certified cost or pricing
data” are not required if the proposer proposes an award instrument other than a procurement
contract (e.g., a grant, cooperative agreement, or other transaction.)
Subawardee Proposals
The awardee is responsible for compiling and providing all subawardee proposals for the
Procuring Contracting Officer (PCO)/Grants Officer (GO)/Agreements Officer (AO), as
applicable. Subawardee proposals should include Interdivisional Work Transfer Agreements
(ITWA) or similar arrangements. Where the effort consists of multiple portions which could
reasonably be partitioned for purposes of funding, these should be identified as options with
separate cost estimates for each.
All proprietary subawardee proposal documentation, prepared at the same level of detail as that
required of the awardee’s proposal and which cannot be uploaded with the proposed awardee’s
proposal, shall be provided to the Government either by the awardee or by the subawardee
organization when the proposal is submitted. Subawardee proposals submitted to the
Government by the proposed subawardee should be submitted via e-mail to the address in Part I.
Other Transaction (OT) Requests
All proposers requesting an OT must include a detailed list of milestones for each phase of the
program (I, II, and III). Each milestone must include the following:
 milestone description,
 completion criteria,
 due date, and
 payment/funding schedule (to include, if cost share is proposed, awardee and
Government share amounts).
It is noted that, at a minimum, milestones should relate directly to accomplishment of program
technical metrics as defined in the BAA and/or the proposer’s proposal. Agreement type,
expenditure or fixed-price based, will be subject to negotiation by the Agreements Officer. Do
not include proprietary data.
4.2.3. Additional Proposal Information
Proprietary Markings
Proposers are responsible for clearly identifying proprietary information. Submissions containing
proprietary information must have the cover page and each page containing such information
clearly marked with a label such as “Proprietary” or “Company Proprietary.” NOTE:
“Confidential” is a classification marking used to control the dissemination of U.S. Government
National Security Information as dictated in Executive Order 13526 and should not be used to
identify proprietary business information.
HR001123S0045, Biological Technologies
25
Unclassified Submissions
DARPA anticipates that submissions received under this BAA will be unclassified. However,
should a proposer wish to submit classified information, an unclassified e-mail must be sent to
the BAA mailbox requesting submission instructions from the Technical Office Program
Security Officer (PSO). If a determination is made that the award instrument may result in access
to classified information, a Security Classification Guide (SCG) and/or DD Form 254 will be
issued by DARPA and attached as part of the award.
Controlled Unclassified Information (CUI) – if anticipated/applicable
For unclassified proposals containing controlled unclassified information (CUI), applicants will
ensure personnel and information systems processing CUI security requirements are in place.
If an unclassified submission contains CUI or the suspicion of such, as defined by Executive
Order 13556 and 32 CFR Part 2002, the information must be appropriately and conspicuously
marked CUI in accordance with DoDI 5200.48. Identification of what is CUI about this DARPA
program will be detailed in a DARPA CUI Guide and will be provided as an attachment to the
BAA or may be provided at a later date.
Unclassified submissions containing CUI may be submitted via DARPA’s BAA Website
(https://baa.darpa.mil) in accordance with Section 4.2.4 of this BAA.
Proposers submitting proposals involving the pursuit and protection of DARPA information
designated as CUI must have, or be able to acquire prior to contract award, an information
system authorized to process CUI information IAW NIST SP 800-171 and DoDI 8582.01.
Disclosure of Information and Compliance with Safeguarding Covered Defense
Information Controls
The following provisions and clause apply to all solicitations and contracts; however, the
definition of “controlled technical information” clearly exempts work considered fundamental
research and therefore, even though included in the contract, will not apply if the work is
fundamental research.
DFARS 252.204-7000, “Disclosure of Information”
DFARS 252.204-7008, “Compliance with Safeguarding Covered Defense Information Controls”
DFARS 252.204-7012, “Safeguarding Covered Defense Information and Cyber Incident
Reporting”
The full text of the above solicitation provision and contract clauses can be found at
http://www.darpa.mil/work-with-us/additional-baa#NPRPAC.
Compliance with the above requirements includes the mandate for proposers to implement the
security requirements specified by National Institute of Standards and Technology (NIST)
Special Publication (SP) 800-171, “Protecting Controlled Unclassified Information in Nonfederal
Information Systems and Organizations” (see
https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-171r2.pdf) and DoDI
8582.01 that are in effect at the time the solicitation is issued.
For awards where the work is considered fundamental research, the contractor will not have to
implement the aforementioned requirements and safeguards. However, should the nature of the 
HR001123S0045, Biological Technologies
26
work change during performance of the award, work not considered fundamental research will
be subject to these requirements.
Human Subjects Research (HSR)/Animal Use
Proposers that anticipate involving human subjects or animals in the proposed research must
comply with the approval procedures detailed at http://www.darpa.mil/work-with-us/additionalbaa, to include providing the information specified therein as required for proposal submission.
Approved Cost Accounting System Documentation
Proposers that do not have a Cost Accounting Standards (CAS) complaint accounting system
considered adequate for determining accurate costs that are negotiating a cost-type procurement
contract must complete an SF 1408. For more information on CAS compliance, see
http://www.dcaa.mil/cas.html. To facilitate this process, proposers should complete the SF 1408
found at http://www.gsa.gov/portal/forms/download/115778 and submit the completed form with
the proposal.
Small Business Subcontracting Plan
Pursuant to Section 8(d) of the Small Business Act (15 U.S.C. § 637(d)) and FAR 19.702(a)(1),
each proposer who submits a contract proposal and includes subcontractors might be required to
submit a subcontracting plan with their proposal. The plan format is outlined in FAR 19.704.
Section 508 of the Rehabilitation Act (29 U.S.C. § 749d)/FAR 39.2
All electronic and information technology acquired or created through this BAA must satisfy the
accessibility requirements of Section 508 of the Rehabilitation Act (29 U.S.C. § 749d)/FAR 39.2.
Grant Abstract
Per Section 8123 of the Department of Defense Appropriations Act, 2015 (Pub. L. 113-235), all
grant awards must be posted on a public website in a searchable format. To comply with this
requirement, proposers requesting grant awards must submit a maximum one (1) page abstract
that may be publicly posted and explains the program or project to the public. The proposer
should sign the bottom of the abstract confirming the information in the abstract is approved for
public release. Proposers are advised to provide both a signed PDF copy, as well as an editable
(e.g., Microsoft word) copy. Abstracts contained in grant proposals that are not selected for
award will not be publicly posted.
Intellectual Property
All proposers must provide a good faith representation that the proposer either owns or possesses
the appropriate licensing rights to all intellectual property that will be utilized under the proposed
effort.
For Procurement Contracts: Proposers responding to this BAA requesting procurement contracts
will need to complete the certifications at DFARS 252.227-7017. See
http://www.darpa.mil/work-with-us/additional-baa for further information. If no restrictions are
intended, the proposer should state “none.” The table below captures the requested information:
HR001123S0045, Biological Technologies
27
Technical Data
Computer
Software To be
Furnished With
Restrictions
Summary of
Intended Use in
the Conduct of
the Research
Basis for
Assertion
Asserted Rights
Category
Name of Person
Asserting
Restrictions
(LIST) (NARRATIVE) (LIST) (LIST) (LIST)
For All Non-Procurement Contracts: Proposers responding to this BAA requesting a
Cooperative Agreement, Other Transaction for Research, or Other Transaction for Prototypes
shall follow the applicable rules and regulations governing these various award instruments, but,
in all cases, should appropriately identify any potential restrictions on the Government’s use of
any Intellectual Property contemplated under the award instrument in question. This includes
both Noncommercial Items and Commercial Items. Proposers are encouraged to use a format
similar to that described in the section above. If no restrictions are intended, then the proposer
should state “NONE.”
System for Award Management (SAM) and Universal Identifier Requirements
All proposers must be registered in SAM unless exempt per FAR 4.1102. FAR 52.204-7,
“System for Award Management” and FAR 52.204-13, “System for Award Management
Maintenance” are incorporated into this solicitation. See http://www.darpa.mil/work-withus/additional-baa for further information.
International entities can register in SAM by following the instructions in this link:
https://www.fsd.gov/sys_attachment.do?sys_id=c08b64ab1b4434109ac5ddb6bc4bcbb8.
4.2.4. Submission Information
DARPA will acknowledge receipt of all submissions and assign an identifying control number
that should be used in all further correspondence regarding the submission. DARPA intends to
use electronic mail correspondence regarding HR001123S0045. Submissions may not be sent by
fax or e-mail; any so sent will be disregarded.
Submissions will not be returned. An electronic copy of each submission received will be
retained at DARPA and all other non-required copies destroyed. A certification of destruction
may be requested, provided the formal request is received by DARPA within 5 days after
notification that a proposal was not selected.
For abstract and proposal submission dates, see Part I, Overview Information. Submissions
received after these dates and times may not be reviewed.
Proposal Abstract Submission
Proposal Abstracts submitted in response to HR001123S0045 must be submitted via DARPA’s
BAA Website (https://baa.darpa.mil). Note: If an account has recently been created for the
DARPA BAA Website, this account may be reused. Accounts are typically disabled and
eventually deleted following 75-90 days of inactivity – if you are unsure when the account was
last used, it is recommended that you create a new account. If no account currently exists for the
DARPA BAA Website, visit the website to complete the two-step registration process. 
HR001123S0045, Biological Technologies
28
Submitters will need to register for an Extranet account (via the form at the URL listed above)
and wait for two separate e-mails containing a username and temporary password. After
accessing the Extranet, submitters may then create an account for the DARPA BAA website (via
the “Register your Organization” link along the left side of the homepage), view submission
instructions, and upload/finalize the abstract. Proposers using the DARPA BAA Website may
encounter heavy traffic on the submission deadline date; it is highly advised that the submission
process be started as early as possible.
All unclassified concepts submitted electronically through DARPA’s BAA Website must be
uploaded as zip files (.zip or .zipx extension). The final zip file should be no greater than 50 MB
in size. Only one zip file will be accepted per submission. Classified submissions and proposals
requesting or cooperative agreements should NOT be submitted through DARPA’s BAA
Website (https://baa.darpa.mil), though proposers will likely still need to visit
https://baa.darpa.mil to register their organization (or verify an existing registration) to ensure the
BAA office can verify and finalize their submission.
Technical support for BAA Website may be reached at BAAT_Support@darpa.mil, and is
typically available during regular business hours, (9:00 AM- 5:00 PM EST Monday – Friday).
Proposers using the DARPA BAA Website may encounter heavy traffic on the submission
deadline date; it is highly advised that the submission process be started as early as possible.
Proposal abstracts will not be accepted if submitted via Grants.gov.
Full Proposal Submission
For Procurement Contracts or Other Transactions only:
Proposers requesting procurement contracts or Other Transactions must submit proposals
through one of the following methods: (1) via DARPA’s BAA Website (https://baa.darpa.mil)
(DARPA-preferred), or (2) hard copy mailed directly to DARPA. If proposers intend to use
DARPA’s BAA Website as their means of submission, then they must submit their entire
proposal through https://baa.darpa.mil; applications cannot be submitted in part electronically
and in part as a hard-copy. Proposers using https://baa.darpa.mil do not submit hard-copy
proposals in addition to the electronic submission.
Note: If an account has recently been created for the DARPA BAA Website, this account may be
reused. Accounts are typically disabled and eventually deleted following 75-90 days of inactivity
– if you are unsure when the account was last used, it is recommended that you create a new
account. If no account currently exists for the DARPA BAA Website, visit the website to
complete the two-step registration process. Submitters will need to register for an Extranet
account (via the form at the URL listed above) and wait for two separate e-mails containing a
username and temporary password. After accessing the Extranet, submitters may then create an
account for the DARPA BAA website (via the “Register your Organization” link along the left
side of the homepage), view submission instructions, and upload/finalize the abstract. Proposers
using the DARPA BAA Website may encounter heavy traffic on the submission deadline date; it
is highly advised that the submission process be started as early as possible.
HR001123S0045, Biological Technologies
29
All unclassified concepts submitted electronically through DARPA’s BAA Website must be
uploaded as zip files (.zip or .zipx extension). The final zip file should be no greater than 50 MB
in size. Only one zip file will be accepted per submission. Classified submissions and proposals
requesting or cooperative agreements should NOT be submitted through DARPA’s BAA
Website (https://baa.darpa.mil), though proposers will likely still need to visit
https://baa.darpa.mil to register their organization (or verify an existing registration) to ensure the
BAA office can verify and finalize their submission.
Technical support for BAA Website may be reached at BAAT_Support@darpa.mil, and is
typically available during regular business hours, (9:00 AM- 5:00 PM EST Monday – Friday).
Proposers using the DARPA BAA Website may encounter heavy traffic on the submission
deadline date; it is highly advised that the submission process be started as early as possible.
For Grants or Cooperative Agreements only:
Proposers requesting grants or cooperative agreements must submit proposals through one of the
following methods: (1) electronic upload per the instructions at
https://www.grants.gov/applicants/apply-for-grants.html (DARPA-preferred); or (2) hard-copy
mailed directly to DARPA. If proposers intend to use Grants.gov as their means of submission,
then they must submit their entire proposal through Grants.gov; applications cannot be submitted
in part to Grants.gov and in part as a hard-copy. Proposers using Grants.gov do not submit hardcopy proposals in addition to the Grants.gov electronic submission.
Submissions: In addition to the volumes and corresponding attachments requested elsewhere in
this solicitation, proposers must also submit the three forms listed below.
Form 1: SF 424 Research and Related (R&R) Application for Federal Assistance, available on
the Grants.gov website at https://apply07.grants.gov/apply/forms/sample/RR_SF424_2_0-
V2.0.pdf. This form must be completed and submitted.
To evaluate compliance with Title IX of the Education Amendments of 1972 (20 U.S.C. § 1681
et.seq.), the Department of Defense (DoD) is collecting certain demographic and career
information to be able to assess the success rates of women who are proposed for key roles in
applications in science, technology, engineering or mathematics disciplines. In addition, the
National Defense Authorization Act (NDAA) for FY 2019, Section 1286, directs the Secretary of
Defense to protect intellectual property, controlled information, key personnel, and information
about critical technologies relevant to national security and limit undue influence, including
foreign talent programs by countries that desire to exploit United States’ technology within the
DoD research, science and technology, and innovation enterprise. This requirement is necessary
for all research and research-related educational activities. The DoD is using the two forms
below to collect the necessary information to satisfy these requirements. Detailed instructions for
each form are available on Grants.gov.
Form 2: The Research and Related Senior/Key Person Profile (Expanded) form, available on the
Grants.gov website at
https://apply07.grants.gov/apply/forms/sample/RR_KeyPersonExpanded_3_0-V3.0.pdf, will be 
HR001123S0045, Biological Technologies
30
used to collect the following information for all senior/key personnel, including Project
Director/Principal Investigator and Co-Project Director/Co-Principal Investigator, whether or not
the individuals' efforts under the project are funded by the DoD. The form includes 3 parts: the
main form administrative information, including the Project Role, Degree Type and Degree
Year; the biographical sketch; and the current and pending support. The biographical sketch and
current and pending support are to be provided as attachments:
 Biographical Sketch: Mandatory for Project Directors (PD) and Principal Investigators
(PI), optional, but desired, for all other Senior/Key Personnel. The biographical sketch
should include information pertaining to the researchers:
o Education and Training.
o Research and Professional Experience.
o Collaborations and Affiliations (for conflict of interest).
o Publications and Synergistic Activities.
 Current and Pending Support: Mandatory for all Senior/Key Personnel including the
PD/PI. This attachment should include the following information:
o A list of all current projects the individual is working on, in addition to any future
support the individual has applied to receive, regardless of the source.
o Title and objectives of the other research projects.
o The percentage per year to be devoted to the other projects.
o The total amount of support the individual is receiving in connection to each of
the other research projects or will receive if other proposals are awarded.
o Name and address of the agencies and/or other parties supporting the other
research projects
o Period of performance for the other research projects.
Additional senior/key persons can be added by selecting the “Next Person” button at the bottom
of the form. Note that, although applications without this information completed may pass
Grants.gov edit checks, if DARPA receives an application without the required information,
DARPA may determine that the application is incomplete and may cause your submission to be
rejected and eliminated from further review and consideration under the solicitation. DARPA
reserves the right to request further details from the applicant before making a final
determination on funding the effort.
Form 3: Research and Related Personal Data, available on the Grants.gov website at
https://apply07.grants.gov/apply/forms/sample/RR_PersonalData_1_2-V1.2.pdf. Each applicant
must complete the name field of this form, however, provision of the demographic information is
voluntary. Regardless of whether the demographic fields are completed or not, this form must be
submitted with at least the applicant’s name completed.
Grants.gov Submissions: Grants.gov requires proposers to complete a one-time registration
process before a proposal can be electronically submitted. First-time registration can take 
HR001123S0045, Biological Technologies
31
between three business days and four weeks. For more information about registering for
Grants.gov, see http://www.darpa.mil/work-with-us/additional-baa.
For Other Transaction for Research only:
Proposers requesting an Other Transaction (OT) for Research awarded under 10 U.S.C.§ 4021
must include the completed form indicated below. This requirement only applies only to those
who expect to receive an OT for Research as their ultimate award instrument.
The National Defense Authorization Act (NDAA) for FY 2019, Section 1286, directs the
Secretary of Defense to protect intellectual property, controlled information, key personnel, and
information about critical technologies relevant to national security and limit undue influence,
including foreign talent programs by countries that desire to exploit United States’ technology
within the DoD research, science and technology, and innovation enterprise. This requirement is
necessary for all research and research-related educational activities. The DoD is using the form
below to collect the necessary information to satisfy these requirements.
The Research and Related Senior/Key Person Profile (Expanded) form, available on the
Grants.gov website at
https://apply07.grants.gov/apply/forms/sample/RR_KeyPersonExpanded_3_0-V3.0.pdf, will be
used to collect the following information for all senior/key personnel, including Project
Director/Principal Investigator and Co-Project Director/Co-Principal Investigator, whether or not
the individuals' efforts under the project are funded by the DoD. The form includes 3 parts: the
main form administrative information, including the Project Role, Degree Type and Degree
Year; the biographical sketch; and the current and pending support. The biographical sketch and
current and pending support are to be provided as attachments:
 Biographical Sketch: Mandatory for Project Directors (PD) and Principal Investigators
(PI), optional, but desired, for all other Senior/Key Personnel. The biographical sketch
should include information pertaining to the researchers:
o Education and Training.
o Research and Professional Experience.
o Collaborations and Affiliations (for conflict of interest).
o Publications and Synergistic Activities.
 Current and Pending Support: Mandatory for all Senior/Key Personnel including the
PD/PI. This attachment should include the following information:
o A list of all current projects the individual is working on, in addition to any future
support the individual has applied to receive, regardless of the source.
o Title and objectives of the other research projects.
o The percentage per year to be devoted to the other projects.
o The total amount of support the individual is receiving in connection to each of
the other research projects or will receive if other proposals are awarded.
o Name and address of the agencies and/or other parties supporting the other
research projects 
HR001123S0045, Biological Technologies
32
o Period of performance for the other research projects.
Additional senior/key persons can be added by selecting the “Next Person” button at the bottom
of the form. Note that, although applications without this information completed may pass
Grants.gov edit checks, if DARPA receives an application without the required information,
DARPA may determine that the application is incomplete and may cause your submission to be
rejected and eliminated from further review and consideration under the solicitation. DARPA
reserves the right to request further details from the applicant before making a final
determination on funding the effort.
Failure to comply with the submission procedures may result in the submission not being
evaluated. DARPA will acknowledge receipt of complete submissions via email and assign
control numbers that should be used in all further correspondence regarding proposals.
4.3. FUNDING RESTRICTIONS
Not applicable.
4.4. OTHER SUBMISSION INFORMATION
DARPA will post a consolidated Frequently Asked Questions (FAQ) document. To access the
posting go to http://www.darpa.mil/work-with-us/opportunities. A link to the FAQ will appear
under the HR001123S0045 summary. Submit your question(s) via e-mail to
BTOBAA2023@darpa.mil.
5. Application Review Information
5.1. EVALUATION CRITERIA
Proposals will be evaluated using the following criteria, listed in descending order of importance:
5.1.1 Overall Scientific and Technical Merit; 5.1.2 Potential Contribution and Relevance to the
DARPA Mission; 5.1.3 Cost Realism.
5.1.1. Overall Scientific and Technical Merit
The proposed technical approach is innovative, feasible, achievable, and complete.
The proposed technical team has the expertise and experience to accomplish the proposed tasks.
Task descriptions and associated technical elements provided are complete and in a logical
sequence with all proposed deliverables clearly defined such that a final outcome that achieves
the goal can be expected as a result of award. The proposal identifies major technical risks, and
planned mitigation efforts are clearly defined and feasible. The timeline for achieving major
milestones is aggressive but rationally supported with a clear description of the requirements and
risks. The proposer's prior experience in similar efforts must clearly demonstrate an ability to
deliver products that meet the proposed technical performance within the proposed budget and
schedule. The proposed team has the expertise to manage the cost and schedule.
5.1.2. Potential Contribution and Relevance to the DARPA Mission
The potential contributions of the proposed effort are relevant to the national technology base.
Specifically, DARPA’s mission is to make pivotal early technology investments that create or
prevent strategic surprise for U.S. National Security.
HR001123S0045, Biological Technologies
33
5.1.3. Cost Realism
The proposed costs are realistic for the technical and management approach and accurately
reflect the technical goals and objectives of the solicitation. The proposed costs are consistent
with the proposer's Statement of Work and reflect a sufficient understanding of the costs and
level of effort needed to successfully accomplish the proposed technical approach. The costs for
the prime proposer and proposed subawardees are substantiated by the details provided in the
proposal (e.g., the type and number of labor hours proposed per task, the types and quantities of
materials, equipment and fabrication costs, travel and any other applicable costs and the basis for
the estimates).
It is expected that the effort will leverage all available relevant prior research in order to obtain
the maximum benefit from the available funding. For efforts with a likelihood of commercial
application, appropriate direct cost sharing may be a positive factor in the evaluation. DARPA
recognizes that undue emphasis on cost may motivate proposers to offer low-risk ideas with
minimum uncertainty and to staff the effort with junior personnel in order to be in a more
competitive posture. DARPA discourages such cost strategies.
5.2. REVIEW OF PROPOSALS
5.2.1. Review Process
It is the policy of DARPA to ensure impartial, equitable, comprehensive proposal evaluations
based on the evaluation criteria listed in Section 5.1. and to select the source (or sources) whose
offer meets the Government's technical, policy, and programmatic goals.
DARPA will conduct a scientific/technical review of each conforming proposal. Conforming
proposals comply with all requirements detailed in this solicitation; proposals that fail to do so
may be deemed non-conforming and may be removed from consideration. Proposals will not be
evaluated against each other since they are not submitted in accordance with a common work
statement. DARPA’s intent is to review proposals as soon as possible after they arrive; however,
proposals may be reviewed periodically for administrative reasons.
Award(s) will be made to proposers whose proposals are determined to be the most
advantageous to the Government, consistent with instructions and evaluation criteria specified
in the BAA herein, and availability of funding.
5.2.2. Handling of Source Selection Information
DARPA policy is to treat all submissions as source selection information (see FAR 2.101 and
3.104) and to disclose their contents only for the purpose of evaluation. Restrictive notices
notwithstanding, during the evaluation process, submissions may be handled by support
contractors for administrative purposes and/or to assist with technical evaluation. All DARPA
support contractors performing this role are expressly prohibited from performing DARPAsponsored technical research and are bound by appropriate nondisclosure agreements.
Subject to the restrictions set forth in FAR 37.203(d), input on technical aspects of the proposals
may be solicited by DARPA from non-Government consultants/experts who are strictly bound
by the appropriate non-disclosure requirements. 
HR001123S0045, Biological Technologies
34
5.2.3. Federal Awardee Performance and Integrity Information (FAPIIS)
Per 41 U.S.C. § 2313, as implemented by FAR 9.103 and 2 CFR § 200.205, prior to making an
award above the simplified acquisition threshold, DARPA is required to review and consider any
information available through the designated integrity and performance system (currently
FAPIIS). Awardees have the opportunity to comment on any information about themselves
entered in the database, and DARPA will consider any comments, along with other information
in FAPIIS or other systems, prior to making an award.
5.2.4. Countering Foreign Influence Program (CFIP)
DARPA’s CFIP is an adaptive risk management security program designed to help protect the
critical technology and performer intellectual property associated with DARPA’s research
projects by identifying the possible vectors of undue foreign influence. The CFIP team will
create risk assessments of all proposed Senior/Key Personnel selected for negotiation of a
fundamental research grant or cooperative agreement award. The CFIP risk assessment process
will be conducted separately from the DARPA scientific review process and adjudicated prior to
final award.
6. Award Administration Information
6.1. SUBMISSION STATUS NOTIFICATIONS
Proposal Abstracts and Full Proposals submitted in response to HR001123S0045 will be
evaluated following the submission deadlines listed in Part I. DARPA will respond as described
below. These official notifications will be sent via e-mail to the Technical Point of Contact
(POC) and/or Administrative POC identified on the submission coversheet.
6.1.1. Proposal Abstracts
DARPA will respond to abstracts with a statement as to whether DARPA is interested in the
idea. If DARPA does not recommend the proposer submit a full proposal, DARPA will provide
feedback to the proposer regarding the rationale for this decision. Regardless of DARPA’s
response to an abstract, proposers may submit a full proposal. DARPA will review all
conforming full proposals using the published evaluation criteria and without regard to any
comments resulting from the review of an abstract.
6.1.2. Full Proposals
As soon as the evaluation of a proposal is complete, the proposer will be notified that (1) the
proposal has been selected for funding pending award negotiations, in whole or in part, or (2) the
proposal has not been selected.
6.2. ADMINISTRATIVE AND NATIONAL POLICY REQUIREMENTS
6.2.1. Meeting and Travel Requirements
There will be a program kickoff meeting in the Arlington, VA vicinity and all key participants
are required to attend. Performers should also anticipate regular program-wide PI meetings and
periodic site visits at the Program Manager’s discretion to the Arlington, VA vicinity. Proposers
shall include within the content of their proposal details and costs of any travel or meetings they 
HR001123S0045, Biological Technologies
35
deem to be necessary throughout the course of the effort, to include periodic status reviews by
the Government.
6.2.1. Solicitation Provisions and Award Clauses, Terms and Conditions
Solicitation clauses in the FAR and DFARS relevant to procurement contracts and FAR and
DFARS clauses that may be included in any resultant procurement contracts are incorporated
herein and can be found at http://www.darpa.mil/work-with-us/additional-baa.
6.2.2. Controlled Unclassified Information (CUI) and Controlled Technical Information
(CTI) on Non-DoD Information Systems
Further information on Controlled Unclassified Information identification, marking, protecting,
and control, to include processing on Non-DoD Information Systems, is incorporated herein and
can be found at http://www.darpa.mil/work-with-us/additional-baa.
6.2.3. Representations and Certifications
In accordance with FAR 4.1102 and 4.1201, proposers requesting a procurement contract must
complete electronic annual representations and certifications at https://www.sam.gov/.
In addition, all proposers are required to submit for all award instrument types supplementary
DARPA-specific representations and certifications at the time of proposal submission. See
http://www.darpa.mil/work-with-us/reps-certs for further information on required representation
and certification depending on your requested award instrument.
A small business joint venture offeror must submit, with its offer, the representation required in
paragraph (c) of FAR solicitation provision 52.212-3, Offeror Representations and
Certifications-Commercial Products and Commercial Services, and paragraph (c) of FAR
solicitation provision 52.219-1, Small Business Program Representations, in accordance with
52.204-8(d) and 52.212-3(b) for the following categories: (A) Small business; (B) Servicedisabled veteran-owned small business; (C) Women-owned small business (WOSB) under the
WOSB Program; (D) Economically disadvantaged women-owned small business under the
WOSB Program; or (E) Historically underutilized business zone small business.
6.2.4. Terms and Conditions
For terms and conditions specific to grants and/or cooperative agreements, see the DoD General
Research Terms and Conditions (latest version) at http://www.onr.navy.mil/ContractsGrants/submit-proposal/grants-proposal/grants-terms-conditions and the supplemental DARPAspecific terms and conditions at http://www.darpa.mil/work-with-us/contractmanagement#GrantsCooperativeAgreements.
6.3. REPORTING
The number and types of reports will be specified in the award document, but will include as a
minimum monthly financial status reports, 6-week technical status reports, and quarterly
technical status reports. The reports shall be prepared and submitted in accordance with the
procedures contained in the award document and mutually agreed on before award. Reports and
briefing material will also be required as appropriate to document progress in accomplishing
program metrics. A Final Report that summarizes the project and tasks will be required at the
conclusion of the performance period for the award, notwithstanding the fact that the research
may be continued under a follow-on vehicle. 
HR001123S0045, Biological Technologies
36
6.4. ELECTRONIC SYSTEMS
6.4.1. Wide Area Work Flow (WAWF)
Performers will be required to submit invoices for payment directly to https://wawf.eb.mil,
unless an exception applies. Performers must register in WAWF prior to any award under this
BAA.
6.4.2. I-EDISON
The award document for each proposal selected for funding will contain a mandatory
requirement for patent reports and notifications to be submitted electronically through i-Edison
(http://public.era.nih.gov/iedison).
7. Agency Contacts
Administrative, technical or contractual questions should be sent via e-mail to the mailbox listed
below.
The BAA Coordinator for this effort may be reached at:
BTOBAA2023@darpa.mil
DARPA/BTO
ATTN: HR001123S0045
675 North Randolph Street
Arlington, VA 22203-2114
For information concerning agency level protests see http://www.darpa.mil/work-withus/additional-baa#NPRPAC.
8. Other Information
8.1. UNIVERSITY FUNDING
In order to ensure that U.S. scientific and engineering students will be able to continue to make
strategic technological advances, DARPA is committed to supporting the work and study of
Ph.D. students and post-doctoral researchers that began work under a DARPA-funded program
awarded through an assistance instrument. Stable and predictable federal funding enables these
students to continue their scientific and engineering careers.
To that end, should a DARPA funded program awarded through a grant or cooperative
agreement with a university or a Research Other Transaction pursuant to 10 U.S.C. § 4021 where
the university is a participant end (due to termination or down-select) before the planned
program completion, DARPA may continue to fund, for no more than two semesters (or
equivalent), the documented costs to employ or sponsor Ph.D. students and/or post-doctoral
researchers. Should such a circumstance arise, the following will take place:
1) The Government will provide appropriate notification to the University participant by the
Agreements Office or through the prime performer.
HR001123S0045, Biological Technologies
37
2) The University must make reasonable efforts to find alternative research or employment
opportunities for these students and researchers.
3) Before any costs will be paid, the University must submit documentation describing their
due diligence efforts in finding alternative arrangements that is certified by a University
official.
4) In addition to this documentation, the affected students and researchers must submit
statements of work describing what research activities they will pursue during the period
of funding and the final deliverable they will submit when the funding is complete.
5) In determining these costs, DARPA will rely on information from the University's
original proposal unless specific circumstances warrant requesting updated proposals. In
no circumstances will this funding be provided when the program is ended because of
suspected or actual fraud or negligence.
DARPA Down-Select Definition:
DARPA often structures programs in phases or options that include specific objectives and a
designated period of performance. This may result in potentially issuing multiple awards to
maximize the number of innovative approaches. This approach allows the Government to
monitor progress and enables programmatic decision points based, at a minimum, against stated
evaluation criteria, metrics, funding availability, and program goals and objectives. As a result,
select performers may advance via award of a subsequent phase or through exercise of a planned
option period. 
HR001123S0045, Biological Technologies
38
9. APPENDIX 1 – Volume II checklist
Volume II, Cost Proposal
Checklist and Sample Templates
The following checklist and sample templates are provided to assist the proposer in
developing a complete cost volume. Full instructions appear in Section 4.2.2 of
HR001123S0045. This worksheet must be included with the coversheet of the Cost
Proposal.
1. Are all items from Section 4.2.2 (Volume II, Cost Proposal) of HR001123S0045 included on
your Cost Proposal cover sheet?
○ YES ○ NO Appears on Page(s) [Type text]
If reply is “No”, please explain:
2. Does your Cost Proposal include (1) a summary cost buildup by Phase, (2) a summary cost
buildup by Year, and (3) a detailed cost buildup of for each Phase that breaks out each task
and shows the cost per month?
○ YES ○ NO Appears on Page(s) [Type text]
If reply is “No”, please explain:
3. Does your cost proposal (detailed cost buildup #3 above in item 2) show a breakdown of the
major cost items listed below:
Direct Labor (Labor Categories, Hours, Rates)
f○ YES ○ NO Appears on Page(s) [Type text]
 Indirect Costs/Rates (i.e., overhead charges, fringe benefits, G&A)
○ YES ○ NO Appears on Page(s) [Type text]
Materials and/or Equipment
○ YES ○ NO Appears on Page(s) [Type text]
Subcontracts/Consultants
○ YES ○ NO Appears on Page(s) [Type text]
Other Direct Costs
○ YES ○ NO Appears on Page(s) [Type text]
Travel
○ YES ○ NO Appears on Page(s) [Type text]
If reply is “No”, please explain: 
HR001123S0045, Biological Technologies
39
4. Have you provided documentation for proposed costs related to travel, to include purpose of
trips, departure and arrival destinations and sample airfare?
○ YES ○ NO Appears on Page(s) [Type text]
If reply is “No”, please explain:
5. Does your cost proposal include a complete itemized list of all material and equipment items
to be purchased (a priced bill-of-materials (BOM))?
○ YES ○ NO Appears on Page(s) [Type text]
If reply is “No”, please explain:
6. Does your cost proposal include vendor quotes or written engineering estimates (basis of
estimate) for all material and equipment with a unit price exceeding $5000?
○ YES ○ NO Appears on Page(s) [Type text]
If reply is “No”, please explain:
7. Does your cost proposal include a clear justification for the cost of labor (written labor basisof-estimate (BOE)) providing rationale for the labor categories and hours proposed for each
task?
○ YES ○ NO Appears on Page(s) [Type text]
If reply is “No”, please explain:
8. Do you have subcontractors/consultants? If YES, continue to question 9. If NO, skip to
question 13.
○ YES ○ NO Appears on Page(s) [Type text]
9. Does your cost proposal include copies of all subcontractor/consultant technical (to include
Statement of Work) and cost proposals?
○ YES ○ NO Appears on Page(s) [Type text]
 If reply is “No”, please explain:
10. Do all subcontract proposals include the required summary buildup, detailed cost
buildup, and supporting documentation (SOW, Bill-of-Materials, Basis-of-Estimate, Vendor
Quotes, etc.)?
○ YES ○ NO Appears on Page(s) [Type text]
 If reply is “No”, please explain: 
HR001123S0045, Biological Technologies
40
11. Does your cost proposal include copies of consultant agreements, if available?
○ YES ○ NO Appears on Page(s) [Type text]
 If reply is “No”, please explain:
12. If requesting a FAR-based contract, does your cost proposal include a tech/cost analysis
for all proposed subcontractors?
○ YES ○ NO Appears on Page(s) [Type text]
 If reply is “No”, please explain:
13. Have all team members (prime and subcontractors) who are considered a Federally
Funded Research & Development Center (FFRDC), included documentation that clearly
demonstrates work is not otherwise available from the private sector AND provided a letter
on letterhead from the sponsoring organization citing the specific authority establishing their
eligibility to propose to government solicitations and compete with industry, and compliance
with the associated FFRDC sponsor agreement and terms and conditions.
○ YES ○ NO Appears on Page(s) [Type text]
 If reply is “No”, please explain:
14. Does your proposal include a response regarding Organizational Conflicts of Interest?
○ YES ○ NO Appears on Page(s) [Type text]
If reply is “No”, please explain:
15. Does your proposal include a completed Data Rights Assertions table/certification?
○ YES ○ NO Appears on Page(s) [Type text]
If reply is “No”, please explain: 

        Instructions:
        1. Carefully analyze the entity's content to understand their worldview, methodology, and unique perspective.
        2. Thoroughly review the grant call to identify all requirements, priorities, and evaluation criteria.
        3. For each question in the catechism:
           a. Provide a comprehensive answer that directly addresses the question.
           b. Incorporate relevant aspects of the entity's expertise and viewpoint.
           c. Align the response with the grant call requirements and agency objectives.
           d. Use specific language, terminology, and concepts from the entity's content to maintain authenticity.
        4. Ensure that the proposal:
           a. Demonstrates a deep understanding of the grant agency's goals and priorities.
           b. Highlights the unique value proposition of the entity in relation to the grant objectives.
           c. Presents quantifiable outcomes and measurable impacts wherever possible.
           d. Addresses potential challenges and provides mitigation strategies.
           e. Maintains a cohesive narrative throughout, connecting the entity's capabilities to the project goals and agency requirements.

        Your proposal should be well-structured, data-driven, and persuasive, showcasing the innovative potential of the project while remaining true to the entity's perspective and the grant agency's expectations.
        