  <script>

/* =====================================================
    GOOGLE TAG MANAGER
===================================================== */
(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
})(window,document,'script','dataLayer','GTM-P8MJZV8C');


const translations = {
    en: {

        // ========================================
// HOMEPAGE
// ========================================

// --- Hero ---
'home.hero.eyebrow': 'Strategy That Ships',
'home.hero.title.line1': 'The Operating System for',
'home.hero.title.highlight': 'Digital Transformation',
'home.hero.subtitle': 'We build governed, scalable, and sustainable systems that bridge the gap between strategy and execution. Decision infrastructure that makes your organization smarter, faster, and more accountable.',
'home.hero.cta.primary': 'Book Discovery Call',
'home.hero.cta.secondary': 'Download Capability Brief',
'home.hero.trust.title': 'Trusted by institutional organizations',
'home.hero.trust.item1': 'Financial Services',
'home.hero.trust.item2': 'Healthcare',
'home.hero.trust.item3': 'Enterprise',
'home.hero.trust.item4': 'Government',

// --- Client Fit Section ---
'home.clientFit.title': 'Built for Organizations That Demand More',
'home.clientFit.subtitle': 'We work with institutional clients who need reliable, governed, and measurable AI and automation solutions.',

'home.clientFit.card1.title': 'Institutional Operations',
'home.clientFit.card1.desc': 'Organizations with complex, high-stakes processes requiring precision and control.',

'home.clientFit.card2.title': 'Compliance-First Environments',
'home.clientFit.card2.desc': 'Teams operating under strict regulatory requirements and audit obligations.',

'home.clientFit.card3.title': 'Data-Intensive Workflows',
'home.clientFit.card3.desc': 'Operations generating significant data that can be leveraged for automation.',

'home.clientFit.card4.title': 'Scaling Challenges',
'home.clientFit.card4.desc': 'Growing organizations where manual processes create bottlenecks.',

'home.clientFit.card5.title': 'Measurable Outcomes Required',
'home.clientFit.card5.desc': 'Leaders accountable for demonstrable ROI and operational improvements.',

// --- Capabilities Section ---
'home.capabilities.title': 'Our Integrated Service Model',
'home.capabilities.subtitle': 'Built on our Core/Grid + Modular Cells architecture, every solution is both scalable and governed - from living systems architecture to institutional-grade sustainment.',

// Capability 1
'home.capabilities.card1.title': 'Governed Delivery Model',
'home.capabilities.card1.problem.label': 'Problem:',
'home.capabilities.card1.problem': 'Fragmented teams and compliance gaps',
'home.capabilities.card1.solution.label': 'Solution:',
'home.capabilities.card1.solution': 'Unified delivery framework with clear decision ownership',
'home.capabilities.card1.outcome.label': 'Outcome:',
'home.capabilities.card1.outcome': 'Strategic objectives met with institutional-grade execution',

// Capability 2
'home.capabilities.card2.title': 'Living Systems Architecture',
'home.capabilities.card2.problem.label': 'Problem:',
'home.capabilities.card2.problem': 'Disconnected data, decisions, and execution',
'home.capabilities.card2.solution.label': 'Solution:',
'home.capabilities.card2.solution': 'Intelligence layer that observes, learns, and adapts',
'home.capabilities.card2.outcome.label': 'Outcome:',
'home.capabilities.card2.outcome': 'Sustainable systems that compound value over time',

// Capability 3
'home.capabilities.card3.title': 'Scalable Platform Engineering',
'home.capabilities.card3.problem.label': 'Problem:',
'home.capabilities.card3.problem': 'Slow deployment and fragmented tech stack',
'home.capabilities.card3.solution.label': 'Solution:',
'home.capabilities.card3.solution': 'Full-stack development, AI/ML, DevOps, and QA services',
'home.capabilities.card3.outcome.label': 'Outcome:',
'home.capabilities.card3.outcome': 'Fast deployment sustained across time zones with governance',

// Capability 4
'home.capabilities.card4.title': 'Modular Cell Development',
'home.capabilities.card4.problem.label': 'Problem:',
'home.capabilities.card4.problem': 'Scaling sacrifices control and compliance',
'home.capabilities.card4.solution.label': 'Solution:',
'home.capabilities.card4.solution': 'Domain-specific execution units inheriting governance from Core/Grid',
'home.capabilities.card4.outcome.label': 'Outcome:',
'home.capabilities.card4.outcome': 'Scale with autonomy and speed without sacrificing control',

// Capability 5
'home.capabilities.card5.title': 'Institutional-Grade Sustainment',
'home.capabilities.card5.problem.label': 'Problem:',
'home.capabilities.card5.problem': 'Post-launch instability and drift',
'home.capabilities.card5.solution.label': 'Solution:',
'home.capabilities.card5.solution': 'Ongoing operational support and system management',
'home.capabilities.card5.outcome.label': 'Outcome:',
'home.capabilities.card5.outcome': 'Systems remain stable, compliant, and continue compounding value',

'home.capabilities.cta': 'View All Capabilities',

// --- Process Section ---
'home.process.title': 'How We Work',
'home.process.subtitle': 'A structured, governed approach that delivers predictable outcomes with full operational visibility.',

'home.process.step1.title': 'Discover',
'home.process.step1.desc': 'We assess your current operations, constraints, and objectives. No generic assessments — specific analysis of your systems, data, and processes.',
'home.process.step1.tag1': 'Operations audit',
'home.process.step1.tag2': 'Data landscape review',
'home.process.step1.tag3': 'Opportunity prioritization',

'home.process.step2.title': 'Design',
'home.process.step2.desc': 'Architecture and solution design aligned with your security, compliance, and operational requirements. Clear specifications before any build begins.',
'home.process.step2.tag1': 'Solution architecture',
'home.process.step2.tag2': 'Integration specifications',
'home.process.step2.tag3': 'Governance framework',

'home.process.step3.title': 'Build',
'home.process.step3.desc': 'Iterative development with continuous stakeholder visibility. No black boxes — you see progress and can course-correct throughout.',
'home.process.step3.tag1': 'Working system components',
'home.process.step3.tag2': 'Documentation',
'home.process.step3.tag3': 'Training materials',

'home.process.step4.title': 'Operate',
'home.process.step4.desc': "Ongoing system management, monitoring, and optimization. We don't just deliver and disappear — we ensure sustained performance.",
'home.process.step4.tag1': 'System monitoring',
'home.process.step4.tag2': 'Performance optimization',
'home.process.step4.tag3': 'Continuous improvement',

'home.process.cta': 'Learn More About Our Process',

// --- Proof Section ---
'home.proof.title': 'Measurable Impact',
'home.proof.subtitle': 'Real outcomes from real implementations. We measure success in operational improvements, not project completion.',

'home.proof.metric1.label': 'Reduction in processing time',
'home.proof.metric1.context': 'Average across automation projects',

'home.proof.metric2.label': 'Accuracy rate',
'home.proof.metric2.context': 'Compared to 94% manual baseline',

'home.proof.metric3.label': 'Throughput improvement',
'home.proof.metric3.context': 'Without additional headcount',

'home.proof.metric4.label': 'Typical ROI timeline',
'home.proof.metric4.context': 'Time to positive return',

// --- Case Studies ---
'home.caseStudies.card1.tag': 'Process Automation',
'home.caseStudies.card1.title': 'Replacing Admin Work With Automation',
'home.caseStudies.card1.desc': 'A real Go High Level setup showing how automation replaced manual coordination and administrative overhead - without hiring more staff.',
'home.caseStudies.card1.metric1': '60%+ admin tasks automated',
'home.caseStudies.card1.metric2': '↓45% manual coordination',
'home.caseStudies.card1.metric3': '↑35% operational speed',
'home.caseStudies.card1.metric4': '0 new admin hires',

'home.caseStudies.card2.tag': 'UI / UX Design',
'home.caseStudies.card2.title': 'UX Redesign to Increase Engagement',
'home.caseStudies.card2.desc': 'Transformed passive visitors into active users through behavior-driven UX improvements - increasing engagement without additional traffic spend.',
'home.caseStudies.card2.metric1': '↓42% bounce rate',
'home.caseStudies.card2.metric2': '↑65% session duration',
'home.caseStudies.card2.metric3': '↑78% CTA interactions',
'home.caseStudies.card2.metric4': '4–5 actions per visit',

'home.caseStudies.card3.tag': 'Financial Services',
'home.caseStudies.card3.title': 'Automated Compliance Reporting',
'home.caseStudies.card3.desc': 'Transformed a 40-hour weekly manual process into a real-time automated system with built-in audit trails.',
'home.caseStudies.card3.metric1': '92% time reduction',
'home.caseStudies.card3.metric2': 'Zero compliance gaps',
'home.caseStudies.card3.metric3': 'Real-time visibility',

'home.caseStudies.cta': 'View All Case Studies',

// --- Final CTA ---
'home.finalCta.title': 'Interested in Working Together?',
'home.finalCta.desc': 'Fill in your details and our team will reach out shortly to continue the conversation. From there, we’ll explore how our solutions could align with your organization’s needs and priorities.',
'home.finalCta.emailLabel': 'Prefer email?',
'home.finalCta.emailText': 'Contact us at support@synexumlabs.com',
'home.finalCta.formTitle': 'Start the Conversation',
'home.finalCta.note': 'We respond within one business day',



        //HEADER

        'nav.capabilities': 'Capabilities',
        'nav.caseStudies': 'Case Studies',
        'nav.howWeWork': 'How We Work',
        'nav.insights': 'Insights',
        'nav.about': 'About',

        'nav.capabilities.governed': 'Governed Delivery Model',
        'nav.capabilities.governed.desc': 'Unified delivery governance',

        'nav.capabilities.living': 'Living System Architecture',
        'nav.capabilities.living.desc': 'Adaptive connected intelligence',

        'nav.capabilities.scalable': 'Scalable Platform Engineering',
        'nav.capabilities.scalable.desc': 'Full-stack AI platforms',

        'nav.capabilities.modular': 'Modular Cell Development',
        'nav.capabilities.modular.desc': 'Autonomous governed units',

        'nav.capabilities.viewAll': 'View All Capabilities →',

        'nav.cta.discovery': 'Book Discovery Call',

        'nav.capabilities.mobile': 'CAPABILITIES',

        'nav.language': 'Language',

        // SYNEXUM ABOUT PAGE

        // --- Hero ---
        'about.hero.title': 'The Bridge Between Strategy and Execution',
        'about.hero.desc':
            'Synexum Labs was born from a shared realization: organizations fail at digital transformation not from a lack of strategy, but from an inability to execute across fragmented teams, systems, and compliance landscapes. The problem is structural - the gap between strategic vision and operational reality.',

        // --- Who We Are ---
        'about.story.title': 'Our Story',

        'about.story.p1':
            'We recognized that this gap exists because the market lacks a unified approach. Organizations need both strategic clarity and institutional governance on one side, combined with execution capacity, speed, and scalability on the other. Neither alone is sufficient. What\'s needed is a bridge: a unified operating model that makes strategy executable and execution governed.',

        'about.story.p2':
            'Synexum Labs is that bridge. We are the unified operating model where strategic direction becomes an executable system, and engineering horsepower becomes a controlled, institutional-grade delivery engine.',

        'about.story.p3':
            'Synexum Labs is that bridge - where strategic direction becomes an executable system, and engineering horsepower becomes a controlled, institutional-grade delivery engine. Our core concept is that digital transformation is not software - it\'s decision infrastructure. We build "living systems" that observe, decide, trigger action, and learn from outcomes, all while staying governed.',

        'about.story.p4':
            'Our core concept is that digital transformation is not software - it\'s decision infrastructure. We build "living systems" that observe what\'s happening, decide what matters, trigger action, and learn from outcomes, all while staying governed. This is the foundation of our approach: strategic clarity unified with scalable execution through the Synexum operating system.',

        // --- Mission ---
        'about.mission.title': 'Our Mission',

        'about.mission.p1':
            'We solve the scaling paradox: how to grow execution capacity without losing governance, accountability, or institutional coherence. Our unified operating model enables organizations to build, scale, and sustain complex digital systems with institutional-grade credibility and speed.',

        'about.mission.p2':
            'Together with Coigne Capital, we offer a seamless bridge - from Coigne\'s trusted strategic vision to Synexum\'s robust technical delivery. This partnership ensures clients thrive both structurally and digitally, with every solution measured by its impact on operational performance.',

        // --- Values ---
        'about.values.precision.title': 'Precision',
        'about.values.precision.desc':
            'We measure success in outcomes, not activity. Every engagement is structured around measurable improvements.',

        'about.values.transparency.title': 'Transparency',
        'about.values.transparency.desc':
            'No black boxes. You have full visibility into our process, progress, and the systems we build.',

        'about.values.governance.title': 'Governance First',
        'about.values.governance.desc':
            'Security, compliance, and control are foundational—not afterthoughts bolted on at the end.',

        // --- Leadership ---
        'about.leadership.title': 'Leadership Team',
        'about.leadership.subtitle':
            'Experienced operators who have built and led technology organizations at scale in regulated industries.',

        'about.leader.sergio.name': 'Sergio Paier',
        'about.leader.sergio.role': 'Managing Partner',
        'about.leader.sergio.bio':
            '15+ years advising founders, families, and globally active businesses on cross-border wealth, capital structuring, and governance frameworks across Canada–U.S.–LATAM.',

        'about.leader.amit.name': 'Amit Kumar',
        'about.leader.amit.role': 'Managing Partner',
        'about.leader.amit.bio':
            '13+ years leading digital transformation, scalable platforms, and AI-driven product delivery across media and SaaS organizations.',

        'about.leader.sourabh.name': 'Sourabh Purwar',
        'about.leader.sourabh.role': 'Managing Partner',
        'about.leader.sourabh.bio':
            '10+ years leading enterprise UX strategy and product design for global organizations, including Deloitte and Oracle NetSuite.',

        // --- Standards ---
        'about.standards.title': 'Our Standards',
        'about.standards.desc':
            'We operate to institutional standards because our clients demand it—and because it\'s the right way to build systems that matter.',

        'about.standards.soc': 'SOC 2 Type II compliant processes',
        'about.standards.gdpr': 'GDPR and CCPA data handling',
        'about.standards.security': 'Enterprise security certifications',
        'about.standards.monitoring': 'Continuous security monitoring',
        'about.standards.audit': 'Regular third-party audits',
        'about.standards.governance': 'Documented governance frameworks',

        // --- Coigne ---
        'about.coigne.title': 'Part of Coigne Capital',
        'about.coigne.desc':
            'Synexum Labs is a portfolio company of Coigne Capital, an investment firm focused on building category-defining technology and services companies. This relationship provides us with the resources, network, and long-term perspective to invest in client success.',
        'about.coigne.link': 'Learn more about Coigne Capital',

        // --- CTA ---
        'about.cta.title': 'Let\'s Discuss Your Operations',
        'about.cta.desc':
            'Schedule a discovery call to explore how Synexum Labs can help transform your operations with intelligent automation.',
        'about.cta.button': 'Book Discovery Call',

        // SYNEXUM CAPABILITIES PAGE (EN)

// --- Hero ---
'cap.hero.title': 'Build & Manage Your Institutional Operating System',
'cap.hero.desc': 'Our integrated suite of services is built on our Core/Grid + Modular Cells architecture, ensuring that every solution is both scalable and governed.',

// --- Governed Delivery Model ---
'cap.governed.title': 'Governed Delivery Model',
'cap.governed.desc': 'We implement and manage a unified delivery framework that ensures your strategic objectives are met with institutional-grade execution. This includes establishing clear decision ownership, managing cross-border compliance, and integrating fragmented tooling into a coherent system.',

'cap.governed.highlight1': 'Decision ownership',
'cap.governed.highlight2': 'Cross-border compliance',
'cap.governed.highlight3': 'Tooling integration',
'cap.governed.highlight4': 'Governance frameworks',

// --- Living Systems Architecture ---
'cap.living.title': 'Living Systems Architecture',
'cap.living.desc': 'We design and build the intelligence layer that connects your data, decisions, and execution. Not just apps - sustainable systems that observe, learn, and adapt to your operational environment.',

'cap.living.highlight1': 'Observe & decide',
'cap.living.highlight2': 'Trigger & learn',
'cap.living.highlight3': 'AI integration',
'cap.living.highlight4': 'Governance controls',

// --- Scalable Platform Engineering ---
'cap.scalable.title': 'Scalable Platform Engineering',
'cap.scalable.desc': 'Full-stack development, AI/ML integration, DevOps, and QA services. Our global execution capacity ensures fast deployment and sustained delivery across time zones within our governance framework.',

'cap.scalable.highlight1': 'Full-stack development',
'cap.scalable.highlight2': 'AI/ML integration',
'cap.scalable.highlight3': 'DevOps & QA',
'cap.scalable.highlight4': 'Global capacity',

// --- Modular Cell Development ---
'cap.modular.title': 'Modular Cell Development',
'cap.modular.desc': 'Domain-specific execution units ("Cells") for Finance, Operations, Analytics, and more. Each Cell operates with autonomy and speed but inherits governance from the Core/Grid.',

'cap.modular.highlight1': 'Core/Grid architecture',
'cap.modular.highlight2': 'Domain cells',
'cap.modular.highlight3': 'Governance inheritance',
'cap.modular.highlight4': 'Scalable control',

// --- Institutional-Grade Sustainment ---
'cap.sustain.title': 'Institutional-Grade Sustainment',
'cap.sustain.desc': 'Our engagement does not end at launch. We provide ongoing operational support to ensure your systems remain stable, compliant, and continue to compound value over time.',

'cap.sustain.highlight1': '24/7 monitoring',
'cap.sustain.highlight2': 'Proactive maintenance',
'cap.sustain.highlight3': 'Compliance sustainment',
'cap.sustain.highlight4': 'Continuous improvement',

// --- CTA ---
'cap.cta.title': 'Ready to Transform Your Operations?',
'cap.cta.desc': 'Let\'s discuss how our capabilities align with your objectives. We\'ll help you identify the highest-impact opportunities.',
'cap.cta.primary': 'Book Discovery Call',
'cap.cta.secondary': 'View Case Studies',

// SYNEXUM CONTACT PAGE (EN)

// --- Hero ---
'contact.hero.title': 'Let\'s Start a Conversation',
'contact.hero.desc': 'Schedule a discovery call to discuss your organization\'s needs and explore how we can help you achieve your digital transformation goals.',

// --- Booking Column ---
'contact.booking.title': 'Book a Discovery Call',
'contact.booking.intro': 'A 30-minute video call to understand your challenges and explore how intelligent automation can deliver measurable improvements for your organization.',

'contact.booking.detail1.title': '30 Minutes',
'contact.booking.detail1.desc': 'Focused discovery session',

'contact.booking.detail2.title': 'Video Conference',
'contact.booking.detail2.desc': 'Google Meet or Zoom',

'contact.booking.detail3.title': 'Flexible Scheduling',
'contact.booking.detail3.desc': 'Pick a time that works for you',

'contact.booking.button': 'Schedule Your Discovery Call',
'contact.booking.note': 'No sales pitch — a structured conversation about your operations',

// --- What to Expect ---
'contact.expect.title': 'What to Expect',
'contact.expect.item1': 'We\'ll discuss your current challenges and operational goals',
'contact.expect.item2': 'Explore potential AI and automation opportunities',
'contact.expect.item3': 'Outline recommended next steps and engagement options',

// --- Contact Info ---
'contact.info.title': 'Get in Touch',
'contact.info.intro': 'Prefer to reach out directly? We\'re here to help.',

'contact.info.email': 'Email Us',
'contact.info.phone': 'Call Us',
'contact.info.address.title': 'Office Location',

'contact.response': 'We typically respond within one business day',

// --- Coigne ---
'contact.coigne.title': 'Part of Coigne Capital',
'contact.coigne.link': 'Learn more about Coigne Capital',

// --- Case Studies Hero ---
'casestudies.hero.title': 'Case Studies',
'casestudies.hero.desc': 'Real outcomes from real implementations. See how we\'ve helped institutional organizations transform their operations with measurable results.',

// --- Featured Section ---
'casestudies.featured.title': 'Featured Projects',

'casestudies.featured.project1.title': 'UX Redesign to Increase Engagement',
'casestudies.featured.project1.client': 'Digital Platform Company',
'casestudies.featured.project1.summary': 'Transformed passive visitors into active users through strategic UX improvements without increasing traffic spend.',
'casestudies.featured.project1.metric1.value': '↓42%',
'casestudies.featured.project1.metric1.label': 'Bounce Rate',
'casestudies.featured.project1.metric2.value': '↑65%',
'casestudies.featured.project1.metric2.label': 'Session Time',
'casestudies.featured.project1.metric3.value': '↑78%',
'casestudies.featured.project1.metric3.label': 'CTA Clicks',

'casestudies.featured.project2.title': 'Automated Compliance Reporting',
'casestudies.featured.project2.client': 'Regional Financial Services Firm',
'casestudies.featured.project2.summary': 'Transformed a 40-hour weekly manual process into a real-time automated system with built-in audit trails.',
'casestudies.featured.project2.metric1.value': '92%',
'casestudies.featured.project2.metric1.label': 'Time Reduction',
'casestudies.featured.project2.metric2.value': '99.8%',
'casestudies.featured.project2.metric2.label': 'Accuracy',
'casestudies.featured.project2.metric3.value': '4 mo',
'casestudies.featured.project2.metric3.label': 'ROI Timeline',

// --- All Case Studies Section ---
'casestudies.all.title': 'All Case Studies',

'casestudies.all.study1.industry': 'Local Services',
'casestudies.all.study1.title': 'Automating Lead Follow-Ups for a Plumbing Business',
'casestudies.all.study1.client': 'Regional Plumbing Services Company',
'casestudies.all.study1.metric.value': '80%',
'casestudies.all.study1.metric.label': 'Faster Response Time',

'casestudies.all.study2.industry': 'Healthcare',
'casestudies.all.study2.title': 'Build & Deployment Automation for a Healthcare Payer Suite',
'casestudies.all.study2.client': 'Cloud-Based Healthcare Payer Platform',
'casestudies.all.study2.metric.value': '55%↑',
'casestudies.all.study2.metric.label': 'Release Speed',

'casestudies.all.study3.industry': 'Digital Platform',
'casestudies.all.study3.title': 'How We Deliver High-Performance Web Platforms',
'casestudies.all.study3.client': 'High-Traffic Digital Services Company',
'casestudies.all.study3.metric.value': '50%',
'casestudies.all.study3.metric.label': 'Faster Page Loads',

'casestudies.all.study4.industry': 'Process Automation',
'casestudies.all.study4.title': 'Replacing Admin Work With Automation',
'casestudies.all.study4.client': 'Digital Services Business',
'casestudies.all.study4.metric.value': '60%+',
'casestudies.all.study4.metric.label': 'Admin Tasks Automated',

'casestudies.all.study5.industry': 'Digital Platform',
'casestudies.all.study5.title': 'UX Redesign to Increase Engagement',
'casestudies.all.study5.client': 'Digital Platform Company',
'casestudies.all.study5.metric.value': '↑78%',
'casestudies.all.study5.metric.label': 'CTA Clicks',

'casestudies.all.study6.industry': 'Financial Services',
'casestudies.all.study6.title': 'Automated Compliance Reporting',
'casestudies.all.study6.client': 'Regional Financial Services Firm',
'casestudies.all.study6.metric.value': '92%',
'casestudies.all.study6.metric.label': 'Time Reduction',

// --- CTA Section ---
'casestudies.cta.title': 'Ready to See Similar Results?',
'casestudies.cta.desc': 'Every organization is different. Let\'s discuss your specific challenges and explore how we can deliver measurable improvements.',
'casestudies.cta.button': 'Schedule a Discovery Call',

// --- Footer Brand ---
'footer.tagline': 'Digital Transformations • Software • AI • Automation',
'footer.taglineSmall': 'Synexum Labs is a sub-brand of Coigne Capital Inc.',
'footer.newsletter.title': 'Subscribe to Insights',

// --- Footer Columns ---
'footer.capabilities.title': 'Capabilities',
'footer.capabilities.link1': 'Governed Delivery Model',
'footer.capabilities.link2': 'Living System Architecture',
'footer.capabilities.link3': 'Scalable Platform Engineering',
'footer.capabilities.link4': 'Modular Cell Development',
'footer.capabilities.link5': 'Institutional-Grade Sustainment',

'footer.company.title': 'Company',
'footer.company.link1': 'About',
'footer.company.link2': 'Case Studies',
'footer.company.link3': 'Insights',
'footer.company.link4': 'Contact',

'footer.resources.title': 'Resources',
'footer.resources.link1': 'Capability Brief',

// --- Footer Bottom ---
'footer.copyright': '© Coigne Capital Inc. — Synexum Labs',
'footer.legal.privacy': 'Privacy Policy',
'footer.legal.terms': 'Terms of Service',
'footer.legal.disclaimer': 'Legal Disclaimer',
'footer.legal.coigne': 'A Coigne Capital company',



// --- Hero ---
'hww.hero.title': 'How We Work',
'hww.hero.description': 'A structured, governed approach that delivers predictable outcomes with full operational visibility. No surprises, no black boxes — just measurable results.',

// --- Principles ---
'hww.principles.title': 'Our Guiding Principles',
'hww.principles.description': 'Every engagement is guided by these core principles that ensure successful outcomes for institutional organizations.',

'hww.principle1.title': 'Governance First',
'hww.principle1.desc': 'Security, compliance, and audit requirements are built into every engagement from day one — not bolted on afterward.',

'hww.principle2.title': 'Full Transparency',
'hww.principle2.desc': 'You have complete visibility into progress, decisions, and deliverables. No black boxes, no surprises.',

'hww.principle3.title': 'Stakeholder Alignment',
'hww.principle3.desc': 'We work with your teams, not around them. Knowledge transfer and capability building are part of every project.',

'hww.principle4.title': 'Measurable Outcomes',
'hww.principle4.desc': 'Every initiative is tied to specific, measurable business outcomes. We define success metrics upfront and track them throughout.',

// --- Framework ---
'hww.framework.title': 'Our Delivery Framework',
'hww.framework.description': 'A proven four-phase methodology that ensures successful delivery while maintaining governance and control throughout.',

// Step 1
'hww.step1.title': 'Discover',
'hww.step1.timeline': 'Weeks 1-2',
'hww.step1.desc': 'We assess your current operations, constraints, and objectives. Specific analysis of your systems, data, and processes to identify the highest-impact opportunities.',
'hww.step1.deliverables.title': 'Deliverables',
'hww.step1.outcomes.title': 'Outcomes',
'hww.step1.deliverable1': 'Operations audit',
'hww.step1.deliverable2': 'Data landscape review',
'hww.step1.deliverable3': 'Opportunity prioritization',
'hww.step1.deliverable4': 'Stakeholder interviews',
'hww.step1.outcome1': 'Clear understanding of current state',
'hww.step1.outcome2': 'Prioritized initiative roadmap',
'hww.step1.outcome3': 'Risk and dependency mapping',

// Step 2
'hww.step2.title': 'Design',
'hww.step2.timeline': 'Weeks 3-4',
'hww.step2.desc': 'Architecture and solution design aligned with your security, compliance, and operational requirements. Clear specifications before build begins.',
'hww.step2.deliverables.title': 'Deliverables',
'hww.step2.outcomes.title': 'Outcomes',
'hww.step2.deliverable1': 'Solution architecture',
'hww.step2.deliverable2': 'Integration specifications',
'hww.step2.deliverable3': 'Governance framework',
'hww.step2.deliverable4': 'Security review',
'hww.step2.outcome1': 'Approved technical design',
'hww.step2.outcome2': 'Clear scope and milestones',
'hww.step2.outcome3': 'Risk mitigation plan',

// Step 3
'hww.step3.title': 'Build',
'hww.step3.timeline': 'Weeks 5-10',
'hww.step3.desc': 'Iterative development with continuous stakeholder visibility. Built-in testing and validation at every stage.',
'hww.step3.deliverables.title': 'Deliverables',
'hww.step3.outcomes.title': 'Outcomes',
'hww.step3.deliverable1': 'Working system components',
'hww.step3.deliverable2': 'Documentation',
'hww.step3.deliverable3': 'Training materials',
'hww.step3.deliverable4': 'Test results',
'hww.step3.outcome1': 'Functional system ready for deployment',
'hww.step3.outcome2': 'Trained team members',
'hww.step3.outcome3': 'Complete documentation',

// Step 4
'hww.step4.title': 'Operate',
'hww.step4.timeline': 'Ongoing',
'hww.step4.desc': 'Ongoing system management, monitoring, and optimization to ensure sustained performance and continuous improvement.',
'hww.step4.deliverables.title': 'Deliverables',
'hww.step4.outcomes.title': 'Outcomes',
'hww.step4.deliverable1': 'System monitoring',
'hww.step4.deliverable2': 'Performance optimization',
'hww.step4.deliverable3': 'Continuous improvement',
'hww.step4.deliverable4': 'Regular reporting',
'hww.step4.outcome1': 'Reliable system performance',
'hww.step4.outcome2': 'Measurable business outcomes',
'hww.step4.outcome3': 'Evolving capabilities',

// --- CTA ---
'hww.cta.title': 'Ready to Get Started?',
'hww.cta.description': 'Let\'s discuss your objectives and explore how our methodology can deliver measurable outcomes for your organization.',
'hww.cta.primary': 'Book Discovery Call',
'hww.cta.secondary': 'View Case Studies',

// ========================================
// Capabilities — Governed Delivery Model
// ========================================

// --- Hero ---
'capabilities.gdm.hero.title': 'Governed Delivery Model',
'capabilities.gdm.hero.description': 'A unified delivery framework that ensures your strategic objectives are met with institutional-grade execution.',

// --- Overview ---
'capabilities.gdm.overview.title': 'Overview',
'capabilities.gdm.overview.description': 'We implement and manage a unified delivery framework that bridges the gap between strategic vision and operational reality. This includes establishing clear decision ownership, managing cross-border compliance, and integrating fragmented tooling into a coherent system. Our governed delivery model ensures that every initiative maintains institutional credibility while moving with the speed your business demands.',

// --- What We Deliver ---
'capabilities.gdm.deliverables.title': 'What We Deliver',

'capabilities.gdm.deliverables.decision.title': 'Decision Ownership Framework',
'capabilities.gdm.deliverables.decision.desc': 'Clear accountability structures that define who owns what decisions, with escalation paths and governance checkpoints.',

'capabilities.gdm.deliverables.compliance.title': 'Cross-Border Compliance Management',
'capabilities.gdm.deliverables.compliance.desc': 'Frameworks for managing regulatory requirements across jurisdictions while maintaining delivery velocity.',

'capabilities.gdm.deliverables.tooling.title': 'Tooling Integration & Consolidation',
'capabilities.gdm.deliverables.tooling.desc': 'Integration of fragmented tools into a coherent, governed ecosystem that enhances visibility and control.',

'capabilities.gdm.deliverables.playbooks.title': 'Execution Playbooks',
'capabilities.gdm.deliverables.playbooks.desc': 'Standardized processes and playbooks that ensure consistent, high-quality delivery across all initiatives.',

'capabilities.gdm.deliverables.dashboard.title': 'Governance Dashboard',
'capabilities.gdm.deliverables.dashboard.desc': 'Real-time visibility into delivery status, compliance metrics, and decision audit trails.',

'capabilities.gdm.deliverables.risk.title': 'Risk Management Protocols',
'capabilities.gdm.deliverables.risk.desc': 'Proactive identification and mitigation of delivery risks with clear escalation procedures.',

// --- Integrations ---
'capabilities.gdm.integrations.title': 'Typical Integrations',
'capabilities.gdm.integrations.intro': 'We work with your existing technology stack and integrate seamlessly with industry-standard platforms.',

// --- Example Deliverables ---
'capabilities.gdm.examples.title': 'Example Deliverables',
'capabilities.gdm.examples.item1': 'Delivery governance framework documentation',
'capabilities.gdm.examples.item2': 'Decision rights matrix and RACI charts',
'capabilities.gdm.examples.item3': 'Compliance tracking and reporting dashboards',
'capabilities.gdm.examples.item4': 'Integrated tooling architecture specifications',
'capabilities.gdm.examples.item5': 'Stakeholder communication protocols',
'capabilities.gdm.examples.item6': 'Quality gates and approval workflows',


// ========================================
// INSIGHTS PAGE
// ========================================

// --- Hero ---
'insights.hero.title': 'Insights',
'insights.hero.description': 'Perspectives on AI, automation, and operational excellence for institutional organizations. Practical frameworks, not hype.',

// --- Featured Article ---
'insights.featured.badge': 'Featured',
'insights.featured.category': 'UI/UX Design',
'insights.featured.title': 'User-Centric UI/UX Design Techniques to Increase Engagement & Retention',
'insights.featured.excerpt': 'High-performing digital products don’t just function well — they create clarity, confidence, and emotional connection. Here’s how user-centered UI/UX design drives sustained engagement and long-term retention.',
'insights.featured.date': 'February 2, 2026',

// --- Section Title ---
'insights.latest.title': 'Latest Articles',

// --- Article 1 ---
'insights.article1.category': 'Web Architecture & SEO',
'insights.article1.title': 'The Connection Between Web Architecture, SEO & Digital Growth',
'insights.article1.excerpt': 'Web architecture is the technical foundation of SEO and long-term digital growth. Learn how structure, performance, and scalability influence search visibility, user experience, and business outcomes.',
'insights.article1.date': 'February 06, 2026',

// --- Article 2 ---
'insights.article2.category': 'IT Services & Advisory',
'insights.article2.title': 'How to Evaluate & Choose the Right Web Development Partner for Long-Term Success',
'insights.article2.excerpt': 'Choosing the right web development partner is a strategic decision. This guide explains how to evaluate partners beyond short-term delivery and select one that supports long-term growth, scalability, and business outcomes.',
'insights.article2.date': 'February 05, 2026',

// --- Article 3 ---
'insights.article3.category': 'IT Services & Advisory',
'insights.article3.title': 'Designing CI/CD Pipelines for High-Velocity Engineering Teams',
'insights.article3.excerpt': 'High-velocity engineering teams rely on modern CI/CD pipelines to deliver software rapidly without sacrificing quality, security, or operational reliability at scale.',
'insights.article3.date': 'February 04, 2026',

// --- Article 4 ---
'insights.article4.category': 'IT Services & Advisory',
'insights.article4.title': 'Modern IT Foundations: The Prerequisite for Scalable AI',
'insights.article4.excerpt': 'Scalable AI is not achieved through models alone. It requires modern IT foundations built for data integrity, governance, security, and operational reliability.',
'insights.article4.date': 'February 03, 2026',

// --- Article 5 ---
'insights.article5.category': 'UI/UX Design',
'insights.article5.title': 'User-Centric UI/UX Design Techniques to Increase Engagement & Retention',
'insights.article5.excerpt': 'High-performing digital products don’t just function well — they create clarity, confidence, and emotional connection.',
'insights.article5.date': 'February 02, 2026',

// --- Article 6 ---
'insights.article6.category': 'AI Strategy',
'insights.article6.title': 'AI Readiness for Institutional Operations: A Practical Framework',
'insights.article6.excerpt': 'Most AI initiatives fail not because of technology limitations, but because organizations lack the foundational elements for successful adoption.',
'insights.article6.date': 'January 15, 2026',



// ========================================
// CASE STUDY
// Automating Fund Administration
// ========================================

// --- Hero ---
'caseStudy.fundAdmin.meta.tag1': 'Process Automation',
'caseStudy.fundAdmin.meta.tag2': 'System Integration',
'caseStudy.fundAdmin.meta.tag3': 'Alternative Asset Manager',
'caseStudy.fundAdmin.title': 'Automating Fund Administration for a $12B Alternative Asset Manager',
'caseStudy.fundAdmin.subtitle': 'How we reduced quarterly close time by 60% and eliminated manual reconciliation errors through intelligent workflow automation.',

// --- Metrics Bar ---
'caseStudy.fundAdmin.metrics.item1.value': '60%',
'caseStudy.fundAdmin.metrics.item1.label': 'Reduction in Close Time',
'caseStudy.fundAdmin.metrics.item2.value': '100%',
'caseStudy.fundAdmin.metrics.item2.label': 'Error Elimination',
'caseStudy.fundAdmin.metrics.item3.value': '$1.2M',
'caseStudy.fundAdmin.metrics.item3.label': 'Annual Savings',
'caseStudy.fundAdmin.metrics.item4.value': '14 Weeks',
'caseStudy.fundAdmin.metrics.item4.label': 'Time to Value',

// --- Context ---
'caseStudy.fundAdmin.context.label': 'The Context',
'caseStudy.fundAdmin.context.title': 'A Growing Fund With Growing Pains',
'caseStudy.fundAdmin.context.p1': "A mid-market alternative asset manager with $12B AUM was experiencing significant operational strain. Their fund administration processes—built on spreadsheets and manual workflows over a decade—couldn't keep pace with their growth trajectory.",
'caseStudy.fundAdmin.context.p2': 'With plans to launch three new fund vehicles within 18 months, leadership recognized that scaling their existing processes would require proportional headcount increases and introduce unacceptable risk levels.',

// --- Challenge ---
'caseStudy.fundAdmin.challenge.label': 'The Challenge',
'caseStudy.fundAdmin.challenge.title': 'Manual Processes at Institutional Scale',
'caseStudy.fundAdmin.challenge.intro': 'The fund administration team faced multiple interconnected challenges that compounded each quarter:',

'caseStudy.fundAdmin.challenge.item1': 'Data fragmentation: Investor data lived across 7 different systems with no single source of truth, leading to reconciliation nightmares.',
'caseStudy.fundAdmin.challenge.item2': 'Manual capital calls: Each capital call required 40+ hours of manual data preparation, validation, and distribution.',
'caseStudy.fundAdmin.challenge.item3': 'Error-prone reporting: Quarterly investor statements averaged 3-5 errors per cycle, damaging LP relationships and requiring extensive remediation.',
'caseStudy.fundAdmin.challenge.item4': 'Audit exposure: Lack of process documentation and audit trails created compliance risk and extended audit cycles by 30%.',

// --- Approach ---
'caseStudy.fundAdmin.approach.label': 'Our Approach',
'caseStudy.fundAdmin.approach.title': 'Phased Automation With Built-In Governance',
'caseStudy.fundAdmin.approach.intro': 'We designed a 14-week engagement structured around quick wins and sustainable change—not a multi-year transformation that would lose momentum.',

// Phase 1
'caseStudy.fundAdmin.phase1.title': 'Discovery & Process Mapping',
'caseStudy.fundAdmin.phase1.duration': 'Weeks 1-2',
'caseStudy.fundAdmin.phase1.desc': 'Deep-dive into existing workflows, system landscape, and pain points. We interviewed 12 stakeholders and documented 47 discrete process steps across the fund administration lifecycle.',
'caseStudy.fundAdmin.phase1.deliverables.title': 'Deliverables',
'caseStudy.fundAdmin.phase1.deliverables.item1': 'Current-state process maps',
'caseStudy.fundAdmin.phase1.deliverables.item2': 'System integration audit',
'caseStudy.fundAdmin.phase1.deliverables.item3': 'Automation opportunity matrix',
'caseStudy.fundAdmin.phase1.deliverables.item4': 'Risk assessment',

// Phase 2
'caseStudy.fundAdmin.phase2.title': 'Data Architecture & Integration',
'caseStudy.fundAdmin.phase2.duration': 'Weeks 3-6',
'caseStudy.fundAdmin.phase2.desc': 'Built a unified data layer connecting all 7 source systems. Implemented real-time sync with conflict resolution and established the single source of truth the team desperately needed.',
'caseStudy.fundAdmin.phase2.deliverables.title': 'Deliverables',
'caseStudy.fundAdmin.phase2.deliverables.item1': 'Integration architecture',
'caseStudy.fundAdmin.phase2.deliverables.item2': 'Data validation rules',
'caseStudy.fundAdmin.phase2.deliverables.item3': 'Sync monitoring dashboard',
'caseStudy.fundAdmin.phase2.deliverables.item4': 'Rollback procedures',

// Phase 3
'caseStudy.fundAdmin.phase3.title': 'Workflow Automation',
'caseStudy.fundAdmin.phase3.duration': 'Weeks 7-11',
'caseStudy.fundAdmin.phase3.desc': 'Deployed intelligent automation for capital calls, distributions, and investor reporting. Built in human-in-the-loop checkpoints for high-value decisions while automating routine validations.',
'caseStudy.fundAdmin.phase3.deliverables.title': 'Deliverables',
'caseStudy.fundAdmin.phase3.deliverables.item1': 'Automated capital call engine',
'caseStudy.fundAdmin.phase3.deliverables.item2': 'Distribution calculator',
'caseStudy.fundAdmin.phase3.deliverables.item3': 'Statement generator',
'caseStudy.fundAdmin.phase3.deliverables.item4': 'Exception handling workflows',

// Phase 4
'caseStudy.fundAdmin.phase4.title': 'Governance & Handoff',
'caseStudy.fundAdmin.phase4.duration': 'Weeks 12-14',
'caseStudy.fundAdmin.phase4.desc': 'Established operational runbooks, trained internal teams, and implemented monitoring dashboards. Ensured the client could maintain and extend the solution independently.',
'caseStudy.fundAdmin.phase4.deliverables.title': 'Deliverables',
'caseStudy.fundAdmin.phase4.deliverables.item1': 'Operations runbook',
'caseStudy.fundAdmin.phase4.deliverables.item2': 'Team training sessions',
'caseStudy.fundAdmin.phase4.deliverables.item3': 'KPI dashboards',
'caseStudy.fundAdmin.phase4.deliverables.item4': 'Escalation procedures',

// --- Results ---
'caseStudy.fundAdmin.results.label': 'The Results',
'caseStudy.fundAdmin.results.title': 'Measurable Impact, Sustained Value',

'caseStudy.fundAdmin.results.item1.before': '12 days',
'caseStudy.fundAdmin.results.item1.after': '5 days',
'caseStudy.fundAdmin.results.item1.label': 'Quarterly close time reduced by 60%',

'caseStudy.fundAdmin.results.item2.before': '3-5 errors',
'caseStudy.fundAdmin.results.item2.after': '0 errors',
'caseStudy.fundAdmin.results.item2.label': 'Zero statement errors for 4 consecutive quarters',

'caseStudy.fundAdmin.results.item3.before': '40+ hours',
'caseStudy.fundAdmin.results.item3.after': '4 hours',
'caseStudy.fundAdmin.results.item3.label': 'Capital call preparation time reduced 90%',

'caseStudy.fundAdmin.results.item4.before': '6 FTEs',
'caseStudy.fundAdmin.results.item4.after': '2 FTEs',
'caseStudy.fundAdmin.results.item4.label': 'Team refocused on strategic investor relations',

// --- Testimonial ---
'caseStudy.fundAdmin.testimonial.quote': "Synexum didn't just automate our processes—they helped us reimagine how fund administration should work. The team we freed up is now focused on LP relationships instead of spreadsheet reconciliation.",
'caseStudy.fundAdmin.testimonial.authorName': 'Chief Operating Officer',
'caseStudy.fundAdmin.testimonial.authorTitle': 'Alternative Asset Manager',

// --- CTA ---
'caseStudy.fundAdmin.cta.title': 'Facing Similar Challenges?',
'caseStudy.fundAdmin.cta.desc': "Let's discuss how intelligent automation can transform your operational workflows and free your team to focus on what matters most.",
'caseStudy.fundAdmin.cta.primary': 'Schedule a Consultation',
'caseStudy.fundAdmin.cta.secondary': 'View More Case Studies',

// PAGE: case Study
//uxRedesignIncreaseEngagement
// LANGUAGE: en

// --- Hero ---
'caseStudy.uxRedesignIncreaseEngagement.hero.imageAlt': 'Insurance protection background',
'caseStudy.uxRedesignIncreaseEngagement.hero.tag1': 'UI/UX Design',
'caseStudy.uxRedesignIncreaseEngagement.hero.tag2': 'Data & Analytics',
'caseStudy.uxRedesignIncreaseEngagement.hero.tag3': 'Digital Platform Company',
'caseStudy.uxRedesignIncreaseEngagement.hero.title': 'UX Redesign to Increase Engagement',
'caseStudy.uxRedesignIncreaseEngagement.hero.subtitle': 'Transformed passive visitors into active users through strategic UX improvements, turning browsers into engaged users without additional traffic spend.',

// --- Metrics Bar ---
'caseStudy.uxRedesignIncreaseEngagement.metrics.item1.value': '42%↓',
'caseStudy.uxRedesignIncreaseEngagement.metrics.item1.label': 'Bounce Rate',
'caseStudy.uxRedesignIncreaseEngagement.metrics.item2.value': '65%↑',
'caseStudy.uxRedesignIncreaseEngagement.metrics.item2.label': 'Session Duration',
'caseStudy.uxRedesignIncreaseEngagement.metrics.item3.value': '78%↑',
'caseStudy.uxRedesignIncreaseEngagement.metrics.item3.label': 'CTA Interactions',
'caseStudy.uxRedesignIncreaseEngagement.metrics.item4.value': '4–5',
'caseStudy.uxRedesignIncreaseEngagement.metrics.item4.label': 'User Actions per Visit',

// --- Context ---
'caseStudy.uxRedesignIncreaseEngagement.context.sectionLabel': 'The Context',
'caseStudy.uxRedesignIncreaseEngagement.context.heading': 'Traffic Was Strong. Engagement Was Not.',
'caseStudy.uxRedesignIncreaseEngagement.context.paragraph1': 'The platform attracted a steady stream of visitors through search, paid campaigns, and referrals. Awareness was not the issue — engagement was.',
'caseStudy.uxRedesignIncreaseEngagement.context.paragraph2': 'Users arrived but quickly left. Sessions were short, interaction was minimal, and very few visitors signed up, explored tools, or converted. The business wasn’t struggling with traffic — it was struggling to turn visitors into active users.',

// --- Challenge ---
'caseStudy.uxRedesignIncreaseEngagement.challenge.sectionLabel': 'The Challenge',
'caseStudy.uxRedesignIncreaseEngagement.challenge.heading': 'High Drop-Off and Low Interaction',
'caseStudy.uxRedesignIncreaseEngagement.challenge.intro': 'Despite strong acquisition, user behavior revealed multiple UX barriers preventing deeper engagement:',
'caseStudy.uxRedesignIncreaseEngagement.challenge.item1.title': 'Immediate exits:',
'caseStudy.uxRedesignIncreaseEngagement.challenge.item1.description': 'Many users left key pages within seconds without interacting.',
'caseStudy.uxRedesignIncreaseEngagement.challenge.item2.title': 'Low scroll depth:',
'caseStudy.uxRedesignIncreaseEngagement.challenge.item2.description': 'Important content and features were rarely seen.',
'caseStudy.uxRedesignIncreaseEngagement.challenge.item3.title': 'Confusing pathways:',
'caseStudy.uxRedesignIncreaseEngagement.challenge.item3.description': 'Navigation and content structure made it unclear what to do next.',
'caseStudy.uxRedesignIncreaseEngagement.challenge.item4.title': 'Weak visual hierarchy:',
'caseStudy.uxRedesignIncreaseEngagement.challenge.item4.description': 'Key actions didn’t stand out, leading to inaction.',
'caseStudy.uxRedesignIncreaseEngagement.challenge.item5.title': 'Unclear CTAs:',
'caseStudy.uxRedesignIncreaseEngagement.challenge.item5.description': 'Calls to action were either missing or poorly positioned.',

// --- Approach ---
'caseStudy.uxRedesignIncreaseEngagement.approach.sectionLabel': 'Our Approach',
'caseStudy.uxRedesignIncreaseEngagement.approach.heading': 'Behavior-Driven UX Redesign',

'caseStudy.uxRedesignIncreaseEngagement.approach.phase1.number': '1',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase1.title': 'User Behavior Analysis',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase1.duration': 'Weeks 1–2',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase1.description': 'Analyzed heatmaps, scroll tracking, and user flows to identify friction points, drop-off zones, and unclear intent signals.',

'caseStudy.uxRedesignIncreaseEngagement.approach.phase2.number': '2',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase2.title': 'Navigation & Information Architecture',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase2.duration': 'Weeks 3–4',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase2.description': 'Simplified navigation, grouped related features, and clarified primary and secondary pathways so users always knew what to do next.',

'caseStudy.uxRedesignIncreaseEngagement.approach.phase3.number': '3',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase3.title': 'Visual Hierarchy & CTA Optimization',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase3.duration': 'Weeks 5–7',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase3.description': 'Used contrast, spacing, and layout prioritization to highlight key actions and reduce cognitive load.',

'caseStudy.uxRedesignIncreaseEngagement.approach.phase4.number': '4',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase4.title': 'Micro-Interactions & Feedback',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase4.duration': 'Weeks 8–10',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase4.description': 'Introduced hover states, progress indicators, and responsive feedback to make the experience feel dynamic and human.',

'caseStudy.uxRedesignIncreaseEngagement.approach.phase5.number': '5',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase5.title': 'Testing & Measurement',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase5.duration': 'Weeks 11–12',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase5.description': 'Continuously monitored engagement metrics and refined flows through data-driven iteration.',

// --- Results ---
'caseStudy.uxRedesignIncreaseEngagement.results.sectionLabel': 'The Results',
'caseStudy.uxRedesignIncreaseEngagement.results.heading': 'From Passive Browsing to Active Engagement',

'caseStudy.uxRedesignIncreaseEngagement.results.card1.before': 'High',
'caseStudy.uxRedesignIncreaseEngagement.results.card1.arrow': '→',
'caseStudy.uxRedesignIncreaseEngagement.results.card1.after': '↓42%',
'caseStudy.uxRedesignIncreaseEngagement.results.card1.label': 'Bounce rate significantly reduced',

'caseStudy.uxRedesignIncreaseEngagement.results.card2.before': 'Low',
'caseStudy.uxRedesignIncreaseEngagement.results.card2.arrow': '→',
'caseStudy.uxRedesignIncreaseEngagement.results.card2.after': '↑65%',
'caseStudy.uxRedesignIncreaseEngagement.results.card2.label': 'Session duration increased',

'caseStudy.uxRedesignIncreaseEngagement.results.card3.before': 'Minimal',
'caseStudy.uxRedesignIncreaseEngagement.results.card3.arrow': '→',
'caseStudy.uxRedesignIncreaseEngagement.results.card3.after': '↑78%',
'caseStudy.uxRedesignIncreaseEngagement.results.card3.label': 'CTA interactions surged',

'caseStudy.uxRedesignIncreaseEngagement.results.card4.before': '1–2',
'caseStudy.uxRedesignIncreaseEngagement.results.card4.arrow': '→',
'caseStudy.uxRedesignIncreaseEngagement.results.card4.after': '4–5',
'caseStudy.uxRedesignIncreaseEngagement.results.card4.label': 'User actions per visit doubled',

// --- Testimonial ---
'caseStudy.uxRedesignIncreaseEngagement.testimonial.quote': 'Our users now explore, interact, and complete actions instead of leaving after a few seconds. The redesign completely changed how people engage with our platform.',
'caseStudy.uxRedesignIncreaseEngagement.testimonial.authorName': 'Head of Product',
'caseStudy.uxRedesignIncreaseEngagement.testimonial.authorTitle': 'Digital Platform Company',

// --- CTA ---
'caseStudy.uxRedesignIncreaseEngagement.cta.heading': 'Want to Increase Engagement Without More Traffic?',
'caseStudy.uxRedesignIncreaseEngagement.cta.description': 'We help digital platforms turn passive visitors into active users through research-driven UX design.',
'caseStudy.uxRedesignIncreaseEngagement.cta.primaryButton': 'Schedule a Consultation',
'caseStudy.uxRedesignIncreaseEngagement.cta.secondaryButton': 'View More Case Studies',

// ========================================
// INSIGHTS ARTICLE
// AI Readiness
// ========================================

// --- Hero ---
'insights.aiReadiness.hero.category': 'AI Strategy',
'insights.aiReadiness.hero.date': 'January 15, 2026',
'insights.aiReadiness.hero.title': 'AI Readiness for Institutional Operations: A Practical Framework',
'insights.aiReadiness.hero.excerpt': 'Most AI initiatives fail not because of technology limitations, but because organizations lack the foundational elements for successful adoption. Here\'s how to assess and build true AI readiness.',

// --- Body Intro ---
'insights.aiReadiness.body.intro.p1': 'The AI hype cycle has peaked, but the real work is just beginning. After years of experimentation, institutional organizations are moving from proof-of-concept to production—and discovering that technology is rarely the bottleneck. The organizations succeeding with AI share something in common: they invested in readiness before rushing to implementation.',

// --- Section: Why Initiatives Fail ---
'insights.aiReadiness.body.fail.title': 'Why Most AI Initiatives Fail',
'insights.aiReadiness.body.fail.p1': 'According to recent industry research, approximately 85% of AI projects never make it to production. The reasons are remarkably consistent across industries and organization sizes:',
'insights.aiReadiness.body.fail.item1.title': 'Data quality issues:',
'insights.aiReadiness.body.fail.item1.desc': 'AI systems are only as good as the data they\'re trained on. Fragmented, inconsistent, or incomplete data creates models that can\'t be trusted for critical decisions.',
'insights.aiReadiness.body.fail.item2.title': 'Unclear ownership:',
'insights.aiReadiness.body.fail.item2.desc': 'When AI initiatives live between IT and business units, accountability gaps emerge. Projects stall waiting for decisions no one feels empowered to make.',
'insights.aiReadiness.body.fail.item3.title': 'Integration complexity:',
'insights.aiReadiness.body.fail.item3.desc': 'Standalone AI tools that don\'t connect to existing workflows create friction. Users revert to familiar processes rather than adopt new ones.',
'insights.aiReadiness.body.fail.item4.title': 'Governance gaps:',
'insights.aiReadiness.body.fail.item4.desc': 'Without clear policies for AI use, organizations face compliance risks and inconsistent outcomes across teams.',

// --- Quote ---
'insights.aiReadiness.body.quote': 'The organizations that succeed with AI treat it as an operational capability, not a technology project. They build the foundation first, then scale what works.',

// --- Section: Four Pillars ---
'insights.aiReadiness.body.pillars.title': 'The Four Pillars of AI Readiness',
'insights.aiReadiness.body.pillars.p1': 'True AI readiness isn\'t a checklist—it\'s a continuous capability that evolves with your organization. We\'ve developed a framework based on work with dozens of institutional clients that focuses on four interconnected pillars:',

// --- Pillar 1 ---
'insights.aiReadiness.body.data.title': '1. Data Foundation',
'insights.aiReadiness.body.data.p1': 'Before any AI initiative, organizations need clarity on their data landscape. This means understanding not just what data exists, but its quality, accessibility, and governance. Key questions include:',
'insights.aiReadiness.body.data.q1': 'Where does critical operational data live, and who owns it?',
'insights.aiReadiness.body.data.q2': 'What data quality issues exist, and how material are they?',
'insights.aiReadiness.body.data.q3': 'Can data be accessed programmatically, or is manual extraction required?',
'insights.aiReadiness.body.data.q4': 'What privacy and compliance constraints apply to different data sets?',

// --- Callout ---
'insights.aiReadiness.body.callout.title': 'Quick Assessment: Data Foundation',
'insights.aiReadiness.body.callout.item1': 'Can you produce a complete inventory of operational data sources in 24 hours?',
'insights.aiReadiness.body.callout.item2': 'Do you have documented data quality metrics for critical systems?',
'insights.aiReadiness.body.callout.item3': 'Is there a single owner accountable for enterprise data governance?',

// --- Pillar 2 ---
'insights.aiReadiness.body.process.title': '2. Process Clarity',
'insights.aiReadiness.body.process.p1': 'AI augments human workflows—it doesn\'t replace them wholesale. Organizations need documented, standardized processes before they can effectively automate or enhance them. Without process clarity, AI implementations create new variations rather than consistent improvements.',
'insights.aiReadiness.body.process.p2': 'The most successful AI initiatives target processes that are:',
'insights.aiReadiness.body.process.item1': 'Well-documented with clear inputs and outputs',
'insights.aiReadiness.body.process.item2': 'Executed frequently enough to generate training data',
'insights.aiReadiness.body.process.item3': 'Valuable enough to justify investment in automation',
'insights.aiReadiness.body.process.item4': 'Stable enough that the AI won\'t need constant retraining',

// --- Pillar 3 ---
'insights.aiReadiness.body.alignment.title': '3. Organizational Alignment',
'insights.aiReadiness.body.alignment.p1': 'AI initiatives that live in IT silos rarely succeed. Sustainable AI adoption requires alignment across technology, operations, risk, and business leadership. This means establishing:',
'insights.aiReadiness.body.alignment.item1.title': 'Executive sponsorship:',
'insights.aiReadiness.body.alignment.item1.desc': 'A senior leader accountable for AI outcomes, not just activities',
'insights.aiReadiness.body.alignment.item2.title': 'Cross-functional governance:',
'insights.aiReadiness.body.alignment.item2.desc': 'Decision-making structures that include all stakeholders',
'insights.aiReadiness.body.alignment.item3.title': 'Skills development:',
'insights.aiReadiness.body.alignment.item3.desc': 'Training programs that build AI literacy across the organization',
'insights.aiReadiness.body.alignment.item4.title': 'Change management:',
'insights.aiReadiness.body.alignment.item4.desc': 'Proactive communication about how AI will affect roles and workflows',

// --- Pillar 4 ---
'insights.aiReadiness.body.infrastructure.title': '4. Technical Infrastructure',
'insights.aiReadiness.body.infrastructure.p1': 'Finally, organizations need the technical foundation to develop, deploy, and monitor AI systems. This doesn\'t mean buying the latest tools—it means having infrastructure that supports experimentation, integration, and governance.',

// --- Key Takeaways ---
'insights.aiReadiness.body.takeaways.title': 'Key Takeaways',
'insights.aiReadiness.body.takeaways.item1': '85% of AI projects fail—usually due to foundational gaps, not technology limitations',
'insights.aiReadiness.body.takeaways.item2': 'AI readiness requires investment across data, process, organization, and infrastructure',
'insights.aiReadiness.body.takeaways.item3': 'Start with an honest assessment of current capabilities before selecting AI use cases',
'insights.aiReadiness.body.takeaways.item4': 'Treat AI as an operational capability that evolves, not a one-time project',

// --- Getting Started ---
'insights.aiReadiness.body.gettingStarted.title': 'Getting Started: The Readiness Assessment',
'insights.aiReadiness.body.gettingStarted.p1': 'For organizations beginning their AI journey—or resetting after failed initiatives—we recommend starting with a structured readiness assessment. This isn\'t about scoring yourself against an arbitrary benchmark. It\'s about identifying the specific gaps that will derail your AI initiatives if left unaddressed.',
'insights.aiReadiness.body.gettingStarted.p2': 'A comprehensive assessment typically takes 2–3 weeks and produces a prioritized roadmap for building AI readiness. The output isn\'t a technology recommendation—it\'s an honest view of organizational capabilities and a practical path forward.',
'insights.aiReadiness.body.gettingStarted.p3': 'The organizations that invest in readiness before rushing to implementation consistently achieve better outcomes: faster time to value, higher adoption rates, and sustainable results that compound over time.',

// --- Sidebar ---
'insights.aiReadiness.sidebar.tocTitle': 'In This Article',
'insights.aiReadiness.sidebar.shareTitle': 'Share This Article',
'insights.aiReadiness.sidebar.copyFeedback': 'Link copied!',
'insights.aiReadiness.sidebar.share.linkedin': 'Share on LinkedIn',
'insights.aiReadiness.sidebar.share.twitter': 'Share on Twitter',
'insights.aiReadiness.sidebar.share.facebook': 'Share on Facebook',
'insights.aiReadiness.sidebar.share.copy': 'Copy link',

// ========================================
// LEGAL PAGE
// Privacy Policy
// ========================================

// --- Header ---
'legal.privacy.hero.title': 'Privacy Policy',
'legal.privacy.hero.lastUpdated': 'Last updated: January 28, 2026',

// --- Effective Entity ---
'legal.privacy.entity.title': 'Effective Entity',
'legal.privacy.entity.description': 'This Privacy Policy applies to Synexum Labs, operated by Coigne Capital Inc.',
'legal.privacy.entity.companyName': 'Coigne Capital Inc.',
'legal.privacy.entity.address': '555 Bd Dr.-Frederik-Philips, Saint-Laurent, Quebec, Canada',
'legal.privacy.entity.emailLabel': 'Email:',
'legal.privacy.entity.email': 'support@synexumlabs.com',
'legal.privacy.entity.phoneLabel': 'Phone:',
'legal.privacy.entity.phone': '+1 (514) 351-5101',

// --- Information We Collect ---
'legal.privacy.collection.title': 'Information We Collect',
'legal.privacy.collection.item1': 'Contact information (name, email, phone)',
'legal.privacy.collection.item2': 'Scheduling and booking information',
'legal.privacy.collection.item3': 'Newsletter subscriptions',
'legal.privacy.collection.item4': 'Website analytics and cookies',
'legal.privacy.collection.item5': 'Client business data during project delivery (including code, credentials, and system access, where required)',

// --- Purpose of Collection ---
'legal.privacy.purpose.title': 'Purpose of Collection',
'legal.privacy.purpose.intro': 'Information is collected to:',
'legal.privacy.purpose.item1': 'Respond to inquiries',
'legal.privacy.purpose.item2': 'Deliver contracted services',
'legal.privacy.purpose.item3': 'Provide project updates and communications',
'legal.privacy.purpose.item4': 'Improve services and website functionality',
'legal.privacy.purpose.item5': 'Comply with legal and contractual obligations',

// --- Data Storage & Transfers ---
'legal.privacy.storage.title': 'Data Storage & Transfers',
'legal.privacy.storage.p1': 'Data may be stored and processed in Canada and the United States, including on Amazon Web Services (AWS) infrastructure.',
'legal.privacy.storage.p2': 'Personal information may be transferred outside of Canada. Appropriate safeguards are implemented in accordance with applicable privacy laws.',

// --- Data Retention ---
'legal.privacy.retention.title': 'Data Retention',
'legal.privacy.retention.p1': 'Personal and business data is retained only for as long as necessary to fulfill contractual, legal, or operational requirements.',

// --- Your Rights ---
'legal.privacy.rights.title': 'Your Rights',
'legal.privacy.rights.intro': 'You may request:',
'legal.privacy.rights.item1': 'Access to your personal data',
'legal.privacy.rights.item2': 'Correction or deletion of your data',
'legal.privacy.rights.item3': 'Withdrawal of consent',
'legal.privacy.rights.item4': 'Opt-out of marketing communications',
'legal.privacy.rights.contactText': 'Requests may be submitted to:',
'legal.privacy.rights.email': 'support@synexumlabs.com',

// --- Privacy Officer ---
'legal.privacy.officer.title': 'Privacy Officer',
'legal.privacy.officer.intro': 'Privacy inquiries and requests should be directed to:',
'legal.privacy.officer.name': 'Privacy Officer – Coigne Capital Inc.',
'legal.privacy.officer.emailLabel': 'Email:',
'legal.privacy.officer.email': 'support@synexumlabs.com',

// --- Electronic Communications ---
'legal.privacy.communications.title': 'Electronic Communications',
'legal.privacy.communications.p1': 'Synexum Labs and Coigne Capital Inc. may send electronic communications including marketing messages, newsletters, and project updates.',
'legal.privacy.communications.p2': 'All communications comply with Canada\'s Anti-Spam Legislation (CASL) and applicable U.S. regulations. Each message includes identification of the sender and an unsubscribe mechanism.',
'legal.privacy.communications.p3': 'You may withdraw consent at any time using the unsubscribe link or by contacting us directly.',

// ========================================
// LEGAL PAGE
// Terms of Service
// ========================================

// --- Header ---
'legal.terms.hero.title': 'Terms of Service',
'legal.terms.hero.lastUpdated': 'Last updated: January 28, 2026',

// --- Governing Entity ---
'legal.terms.entity.title': 'Governing Entity',
'legal.terms.entity.p1': 'All services provided under the Synexum Labs brand are offered by Coigne Capital Inc., incorporated in Quebec, Canada.',

// --- Scope of Services ---
'legal.terms.scope.title': 'Scope of Services',
'legal.terms.scope.intro': 'Services include, but are not limited to:',
'legal.terms.scope.item1': 'Custom software development',
'legal.terms.scope.item2': 'Web and cloud applications',
'legal.terms.scope.item3': 'Automation and workflow systems',
'legal.terms.scope.item4': 'Artificial intelligence integration',
'legal.terms.scope.item5': 'Data analytics and dashboards',
'legal.terms.scope.item6': 'Infrastructure and DevOps support',
'legal.terms.scope.item7': 'Digital and technical advisory services',

// --- No Guarantees ---
'legal.terms.noGuarantees.title': 'No Guarantees',
'legal.terms.noGuarantees.p1': 'Synexum Labs does not guarantee outcomes, uptime, performance metrics, system availability, or commercial results. Service level agreements (SLAs), where applicable, are provided exclusively by written contract.',

// --- Hosting & Infrastructure ---
'legal.terms.infrastructure.title': 'Hosting & Infrastructure',
'legal.terms.infrastructure.p1': 'Development work may be hosted temporarily on infrastructure located in the United States during development phases or performed directly within client-provided environments, as agreed contractually.',

// --- Intellectual Property ---
'legal.terms.ip.title': 'Intellectual Property',
'legal.terms.ip.p1': 'Ownership of deliverables, code, and intellectual property is governed exclusively by the applicable written agreement. In the absence of a written agreement, all intellectual property remains the property of Coigne Capital Inc.',

// --- Limitation of Liability ---
'legal.terms.liability.title': 'Limitation of Liability',
'legal.terms.liability.p1': 'To the maximum extent permitted by law, Coigne Capital Inc. and its affiliates shall not be liable for indirect, incidental, consequential, special, or punitive damages.',

// --- Dispute Resolution ---
'legal.terms.dispute.title': 'Dispute Resolution',
'legal.terms.dispute.p1': 'Any dispute shall be resolved first through good-faith mediation, then binding arbitration. Governing law shall be the laws of the Province of Quebec and the federal laws of Canada applicable therein, unless otherwise agreed in writing.',

// --- Contact Information ---
'legal.terms.contact.title': 'Contact Information',
'legal.terms.contact.intro': 'If you have questions about these Terms of Service, please contact us:',
'legal.terms.contact.company': 'Coigne Capital Inc.',
'legal.terms.contact.address': '555 Bd Dr.-Frederik-Philips, Saint-Laurent, Quebec, Canada',
'legal.terms.contact.emailLabel': 'Email:',
'legal.terms.contact.email': 'info@synexumlabs.com',
'legal.terms.contact.phoneLabel': 'Phone:',
'legal.terms.contact.phone': '+1 (514) 351-5101',
'legal.terms.contact.generalInquiries': 'General Inquiries:',
'legal.terms.contact.contactForm': 'Contact Form',

// ========================================
// LEGAL PAGE
// Legal Disclaimer
// ========================================

// --- Header ---
'legal.disclaimer.hero.title': 'Legal Disclaimer',
'legal.disclaimer.hero.lastUpdated': 'Last updated: January 28, 2026',

// --- Relationship Disclosure ---
'legal.disclaimer.relationship.title': 'Relationship Disclosure',
'legal.disclaimer.relationship.p1': 'Synexum Labs is a technology and digital transformation sub-brand of Coigne Capital Inc., a corporation incorporated under the laws of Canada and registered in the Province of Quebec.',
'legal.disclaimer.relationship.p2': 'Synexum Labs operates as a dedicated digital transformation, software development, and automation division within the Coigne Capital ecosystem. Services delivered under the Synexum Labs brand are contracted through Coigne Capital Inc., unless otherwise expressly stated in writing.',
'legal.disclaimer.relationship.p3': 'Synexum Labs operates pursuant to a formal commercial and strategic development agreement between Coigne Capital Inc. and Happy People AI, under which Happy People AI acts as a strategic technology collaborator and development partner.',
'legal.disclaimer.relationship.p4': 'Synexum Labs\' development and delivery model is decentralized and includes team members and collaborators located in Canada, the United States, India, and select Latin American jurisdictions.',
'legal.disclaimer.relationship.p5': 'Each entity within this ecosystem operates independently. Nothing on this website shall be construed as creating a partnership, joint venture, fiduciary relationship, or agency relationship beyond what is expressly defined in written agreements.',

// --- Professional & Regulatory Disclaimer ---
'legal.disclaimer.professional.title': 'Professional & Regulatory Disclaimer',
'legal.disclaimer.professional.p1': 'Synexum Labs is the digital transformation and technology delivery arm of Coigne Capital Inc. Services include custom software development, web applications, automation systems, AI integration, data analytics, infrastructure support, and digital advisory services.',
'legal.disclaimer.professional.p2': 'Neither Synexum Labs nor Coigne Capital Inc. is a registered investment advisor, broker, dealer, or securities intermediary. No content on this website constitutes legal advice, tax advice, accounting advice, investment advice, or a solicitation for regulated financial products or services.',
'legal.disclaimer.professional.p3': 'Technology services may support businesses operating in regulated or mission-critical sectors; however, regulatory compliance, legal interpretation, and operational risk remain the sole responsibility of the client.',
'legal.disclaimer.professional.caps': 'NO WARRANTIES—EXPRESS OR IMPLIED—ARE PROVIDED, INCLUDING BUT NOT LIMITED TO WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, ACCURACY, OR UNINTERRUPTED AVAILABILITY.',

// --- Contact Information ---
'legal.disclaimer.contact.title': 'Contact Information',
'legal.disclaimer.contact.intro': 'For questions about this Legal Disclaimer, please contact us:',
'legal.disclaimer.contact.company': 'Coigne Capital Inc.',
'legal.disclaimer.contact.address': '555 Bd Dr.-Frederik-Philips, Saint-Laurent, Quebec, Canada',
'legal.disclaimer.contact.emailLabel': 'Email:',
'legal.disclaimer.contact.email': 'info@synexumlabs.com',
'legal.disclaimer.contact.phoneLabel': 'Phone:',
'legal.disclaimer.contact.phone': '+1 (514) 351-5101',



// ========================================
// CAPABILITY BRIEF PAGE
// Synexum Labs – Capability Brief
// ========================================

// --- Meta ---
'capabilityBrief.meta.title': 'Synexum Labs – Capability Brief',

// --- Top Bar ---
'capabilityBrief.top.back': '← Back to Website',
'capabilityBrief.top.print': 'Print / Save as PDF',
'capabilityBrief.top.download': 'Download PDF',

// --- Header ---
'capabilityBrief.header.title': 'Capability Brief',
'capabilityBrief.header.subtitle': 'Intelligent Systems for Institutional Operations',
'capabilityBrief.header.logoAlt': 'Synexum Labs Logo',
'capabilityBrief.header.logoAria': 'Synexum Labs - Home',

// --- Executive Summary ---
'capabilityBrief.executive.title': 'Executive Summary',
'capabilityBrief.executive.p1': 'Synexum Labs designs, builds, and operates intelligent AI and automation systems that reduce cycle time, improve control, and deliver measurable outcomes for institutional organizations.',

// --- Core Capabilities ---
'capabilityBrief.capabilities.title': 'Core Capabilities',

'capabilityBrief.capabilities.governed.title': 'Governed Delivery Model',
'capabilityBrief.capabilities.governed.desc': 'Institutional-grade execution with clear ownership, compliance control, and integrated tooling.',

'capabilityBrief.capabilities.architecture.title': 'Living Systems Architecture',
'capabilityBrief.capabilities.architecture.desc': 'Adaptive systems that connect data, decisions, and execution under governance.',

'capabilityBrief.capabilities.platform.title': 'Scalable Platform Engineering',
'capabilityBrief.capabilities.platform.desc': 'Full-stack and AI-enabled engineering delivered through a governed global model.',

'capabilityBrief.capabilities.modular.title': 'Modular Cell Development',
'capabilityBrief.capabilities.modular.desc': 'Autonomous domain units operating within a centralized governance framework.',

'capabilityBrief.capabilities.sustainment.title': 'Institutional-Grade Sustainment',
'capabilityBrief.capabilities.sustainment.desc': 'Ongoing monitoring, compliance support, and continuous operational improvement.',

// --- Methodology ---
'capabilityBrief.methodology.title': 'Our Methodology',

'capabilityBrief.methodology.step1': 'Discover',
'capabilityBrief.methodology.step2': 'Design',
'capabilityBrief.methodology.step3': 'Build',
'capabilityBrief.methodology.step4': 'Operate',

// --- Proven Results ---
'capabilityBrief.results.title': 'Proven Results',

'capabilityBrief.results.item1.value': '92%',
'capabilityBrief.results.item1.label': 'Time Reduction',

'capabilityBrief.results.item2.value': '99.8%',
'capabilityBrief.results.item2.label': 'Accuracy',

'capabilityBrief.results.item3.value': '4 mo',
'capabilityBrief.results.item3.label': 'ROI Timeline',

// --- Industries ---
'capabilityBrief.industries.title': 'Industries We Serve',
'capabilityBrief.industries.item1': 'Financial Services',
'capabilityBrief.industries.item2': 'Healthcare',
'capabilityBrief.industries.item3': 'Enterprise',
'capabilityBrief.industries.item4': 'Government',

// --- Get Started ---
'capabilityBrief.cta.title': 'Get Started',
'capabilityBrief.cta.p1': 'Schedule a discovery call to explore how Synexum Labs can help transform your operations.',
'capabilityBrief.cta.websiteLabel': 'Website:',
'capabilityBrief.cta.website': 'synexumlabs.com',
'capabilityBrief.cta.emailLabel': 'Email:',
'capabilityBrief.cta.email': 'support@synexumlabs.com',

// --- Footer ---
'capabilityBrief.footer.copyright': '© Coigne Capital Inc. — Synexum Labs',
'capabilityBrief.footer.confidential': 'Confidential – Intended for prospective clients only.',


// ========================================
// CAPABILITIES PAGE
// Living Systems Architecture
// ========================================

// --- Hero ---
'capabilities.livingSystems.hero.title': 'Living Systems Architecture',
'capabilities.livingSystems.hero.subtitle': 'The intelligence layer that connects your data, decisions, and execution - systems that observe, learn, and adapt.',
'capabilities.livingSystems.hero.bgAlt': 'Insurance protection background',

// --- Overview ---
'capabilities.livingSystems.overview.title': 'Overview',
'capabilities.livingSystems.overview.p1': "We design and build the intelligence layer that connects your data, decisions, and execution. This is not just about building apps; it's about creating a sustainable system that observes what's happening, decides what matters, triggers action, and learns from outcomes - all while staying governed. These 'living systems' form the decision infrastructure that makes your organization smarter, faster, and more accountable.",

// --- What We Deliver ---
'capabilities.livingSystems.deliver.title': 'What We Deliver',

'capabilities.livingSystems.deliver.observe.title': 'Observe Layer',
'capabilities.livingSystems.deliver.observe.desc': 'Data collection and sensing infrastructure that captures operational signals across your organization in real-time.',

'capabilities.livingSystems.deliver.decide.title': 'Decide Layer',
'capabilities.livingSystems.deliver.decide.desc': 'AI-powered decision engines that evaluate conditions, apply business rules, and determine optimal actions.',

'capabilities.livingSystems.deliver.trigger.title': 'Trigger Layer',
'capabilities.livingSystems.deliver.trigger.desc': 'Execution orchestration that initiates workflows, notifications, and automated responses based on decisions.',

'capabilities.livingSystems.deliver.learn.title': 'Learn Layer',
'capabilities.livingSystems.deliver.learn.desc': 'Feedback loops and machine learning components that continuously improve system performance over time.',

'capabilities.livingSystems.deliver.governance.title': 'Governance Controls',
'capabilities.livingSystems.deliver.governance.desc': 'Built-in audit trails, explainability, and human-in-the-loop checkpoints for critical decisions.',

'capabilities.livingSystems.deliver.integration.title': 'Integration Architecture',
'capabilities.livingSystems.deliver.integration.desc': 'Connective tissue that links living systems to your existing technology ecosystem.',

// --- Integrations ---
'capabilities.livingSystems.integrations.title': 'Typical Integrations',
'capabilities.livingSystems.integrations.intro': 'We work with your existing technology stack and integrate seamlessly with industry-standard platforms.',

'capabilities.livingSystems.integrations.azure': 'Azure AI',
'capabilities.livingSystems.integrations.aws': 'AWS SageMaker',
'capabilities.livingSystems.integrations.google': 'Google Cloud AI',
'capabilities.livingSystems.integrations.openai': 'OpenAI',
'capabilities.livingSystems.integrations.anthropic': 'Anthropic',
'capabilities.livingSystems.integrations.databricks': 'Databricks',
'capabilities.livingSystems.integrations.snowflake': 'Snowflake',
'capabilities.livingSystems.integrations.kafka': 'Apache Kafka',
'capabilities.livingSystems.integrations.kubernetes': 'Kubernetes',
'capabilities.livingSystems.integrations.custom': 'Custom ML Pipelines',

// --- Example Deliverables ---
'capabilities.livingSystems.examples.title': 'Example Deliverables',

'capabilities.livingSystems.examples.item1': 'Living systems architecture blueprint',
'capabilities.livingSystems.examples.item2': 'Observe-Decide-Trigger-Learn (ODTL) workflow designs',
'capabilities.livingSystems.examples.item3': 'AI model specifications and training plans',
'capabilities.livingSystems.examples.item4': 'Integration architecture documentation',
'capabilities.livingSystems.examples.item5': 'Governance and explainability frameworks',
'capabilities.livingSystems.examples.item6': 'Performance monitoring dashboards',


// ========================================
// CAPABILITIES PAGE
// Scalable Platform Engineering
// ========================================

// --- Hero ---
'capabilities.platformEngineering.hero.title': 'Scalable Platform Engineering',
'capabilities.platformEngineering.hero.subtitle': 'Full-stack development, AI/ML integration, DevOps, and QA services with global execution capacity.',
'capabilities.platformEngineering.hero.bgAlt': 'Insurance protection background',

// --- Overview ---
'capabilities.platformEngineering.overview.title': 'Overview',
'capabilities.platformEngineering.overview.p1': 'We provide full-stack development, AI/ML integration, DevOps, and QA services. Our global execution capacity ensures that we can deploy fast and sustain delivery across time zones, all within the governance framework of the Synexum model. Whether you need to build new applications, modernize legacy systems, or scale your engineering capacity, we deliver with institutional-grade quality and speed.',

// --- What We Deliver ---
'capabilities.platformEngineering.deliver.title': 'What We Deliver',

'capabilities.platformEngineering.deliver.fullstack.title': 'Full-Stack Development',
'capabilities.platformEngineering.deliver.fullstack.desc': 'End-to-end application development across web, mobile, and enterprise platforms using modern technology stacks.',

'capabilities.platformEngineering.deliver.aiml.title': 'AI/ML Integration',
'capabilities.platformEngineering.deliver.aiml.desc': 'Integration of artificial intelligence and machine learning capabilities into your applications and workflows.',

'capabilities.platformEngineering.deliver.devops.title': 'DevOps & Cloud Infrastructure',
'capabilities.platformEngineering.deliver.devops.desc': 'CI/CD pipelines, infrastructure as code, and cloud architecture for reliable, scalable deployments.',

'capabilities.platformEngineering.deliver.qa.title': 'Quality Assurance',
'capabilities.platformEngineering.deliver.qa.desc': 'Comprehensive testing strategies including automated testing, performance testing, and security assessments.',

'capabilities.platformEngineering.deliver.api.title': 'API Development',
'capabilities.platformEngineering.deliver.api.desc': 'RESTful and GraphQL API design and implementation for seamless system integration.',

'capabilities.platformEngineering.deliver.legacy.title': 'Legacy Modernization',
'capabilities.platformEngineering.deliver.legacy.desc': 'Strategic migration and modernization of legacy systems while maintaining business continuity.',

// --- Integrations ---
'capabilities.platformEngineering.integrations.title': 'Typical Integrations',
'capabilities.platformEngineering.integrations.intro': 'We work with your existing technology stack and integrate seamlessly with industry-standard platforms.',

'capabilities.platformEngineering.integrations.aws': 'AWS',
'capabilities.platformEngineering.integrations.azure': 'Azure',
'capabilities.platformEngineering.integrations.google': 'Google Cloud',
'capabilities.platformEngineering.integrations.kubernetes': 'Kubernetes',
'capabilities.platformEngineering.integrations.docker': 'Docker',
'capabilities.platformEngineering.integrations.terraform': 'Terraform',
'capabilities.platformEngineering.integrations.github': 'GitHub Actions',
'capabilities.platformEngineering.integrations.jenkins': 'Jenkins',
'capabilities.platformEngineering.integrations.react': 'React',
'capabilities.platformEngineering.integrations.node': 'Node.js',
'capabilities.platformEngineering.integrations.python': 'Python',
'capabilities.platformEngineering.integrations.dotnet': '.NET',

// --- Example Deliverables ---
'capabilities.platformEngineering.examples.title': 'Example Deliverables',

'capabilities.platformEngineering.examples.item1': 'Production-ready applications and microservices',
'capabilities.platformEngineering.examples.item2': 'CI/CD pipeline configurations',
'capabilities.platformEngineering.examples.item3': 'Cloud infrastructure architecture',
'capabilities.platformEngineering.examples.item4': 'API documentation and specifications',
'capabilities.platformEngineering.examples.item5': 'Automated test suites',
'capabilities.platformEngineering.examples.item6': 'Performance optimization reports',


// ========================================
// CAPABILITIES PAGE
// Modular Cell Development
// ========================================

// --- Hero ---
'capabilities.modularCell.hero.title': 'Modular Cell Development',
'capabilities.modularCell.hero.subtitle': 'Domain-specific execution units that operate with autonomy and speed while inheriting governance from the Core/Grid.',
'capabilities.modularCell.hero.bgAlt': 'Insurance protection background',

// --- Overview ---
'capabilities.modularCell.overview.title': 'Overview',
'capabilities.modularCell.overview.p1': "We build domain-specific execution units ('Cells') for functions like Finance, Operations, and Analytics. Each Cell operates with autonomy and speed but inherits its governance and compliance standards from the central 'Core/Grid,' allowing you to scale without sacrificing control. This architecture solves the scaling paradox: how to grow execution capacity without losing governance, accountability, or institutional coherence.",

// --- What We Deliver ---
'capabilities.modularCell.deliver.title': 'What We Deliver',

'capabilities.modularCell.deliver.core.title': 'Core/Grid Architecture',
'capabilities.modularCell.deliver.core.desc': 'Central governance layer that defines standards, policies, and compliance requirements inherited by all Cells.',

'capabilities.modularCell.deliver.cells.title': 'Domain-Specific Cells',
'capabilities.modularCell.deliver.cells.desc': 'Autonomous execution units tailored to specific functions like Finance, Operations, HR, or Analytics.',

'capabilities.modularCell.deliver.inheritance.title': 'Cell Governance Inheritance',
'capabilities.modularCell.deliver.inheritance.desc': 'Mechanisms that ensure each Cell automatically inherits and enforces governance standards from the Core/Grid.',

'capabilities.modularCell.deliver.communication.title': 'Inter-Cell Communication',
'capabilities.modularCell.deliver.communication.desc': 'Secure, governed interfaces for data and workflow exchange between Cells.',

'capabilities.modularCell.deliver.monitoring.title': 'Cell Performance Monitoring',
'capabilities.modularCell.deliver.monitoring.desc': 'Dashboards and metrics that track Cell performance, compliance, and operational health.',

'capabilities.modularCell.deliver.scaling.title': 'Scaling Playbooks',
'capabilities.modularCell.deliver.scaling.desc': 'Documented processes for spinning up new Cells or expanding existing ones while maintaining governance.',

// --- Integrations ---
'capabilities.modularCell.integrations.title': 'Typical Integrations',
'capabilities.modularCell.integrations.intro': 'We work with your existing technology stack and integrate seamlessly with industry-standard platforms.',

'capabilities.modularCell.integrations.kubernetes': 'Kubernetes',
'capabilities.modularCell.integrations.docker': 'Docker',
'capabilities.modularCell.integrations.kafka': 'Apache Kafka',
'capabilities.modularCell.integrations.rabbitmq': 'RabbitMQ',
'capabilities.modularCell.integrations.terraform': 'Terraform',
'capabilities.modularCell.integrations.consul': 'Consul',
'capabilities.modularCell.integrations.vault': 'Vault',
'capabilities.modularCell.integrations.prometheus': 'Prometheus',
'capabilities.modularCell.integrations.grafana': 'Grafana',
'capabilities.modularCell.integrations.custom': 'Custom Orchestration',

// --- Example Deliverables ---
'capabilities.modularCell.examples.title': 'Example Deliverables',

'capabilities.modularCell.examples.item1': 'Core/Grid architecture specifications',
'capabilities.modularCell.examples.item2': 'Cell blueprints for each domain',
'capabilities.modularCell.examples.item3': 'Governance inheritance documentation',
'capabilities.modularCell.examples.item4': 'Inter-Cell API contracts',
'capabilities.modularCell.examples.item5': 'Monitoring and alerting configurations',
'capabilities.modularCell.examples.item6': 'Cell scaling and deployment runbooks',

// ========================================
// CAPABILITIES PAGE
// Institutional-Grade Sustainment
// ========================================

// --- Hero ---
'capabilities.sustainment.hero.title': 'Institutional-Grade Sustainment',
'capabilities.sustainment.hero.subtitle': 'Ongoing operational support that ensures your systems remain stable, compliant, and continue to compound value over time.',
'capabilities.sustainment.hero.bgAlt': 'Insurance protection background',

// --- Overview ---
'capabilities.sustainment.overview.title': 'Overview',
'capabilities.sustainment.overview.p1': "Our engagement doesn't end at launch. We provide ongoing operational support to ensure that your systems remain stable, compliant, and continue to compound value over time. We manage the system so you can focus on your business. This institutional-grade sustainment ensures that your digital investments don't decay but instead continuously improve and adapt to changing business needs.",

// --- What We Deliver ---
'capabilities.sustainment.deliver.title': 'What We Deliver',

'capabilities.sustainment.deliver.monitoring.title': '24/7 Operations Monitoring',
'capabilities.sustainment.deliver.monitoring.desc': 'Round-the-clock monitoring of system health, performance, and security with immediate incident response.',

'capabilities.sustainment.deliver.maintenance.title': 'Proactive Maintenance',
'capabilities.sustainment.deliver.maintenance.desc': 'Scheduled updates, patches, and optimizations that prevent issues before they impact operations.',

'capabilities.sustainment.deliver.compliance.title': 'Compliance Sustainment',
'capabilities.sustainment.deliver.compliance.desc': 'Continuous compliance monitoring and adaptation to evolving regulatory requirements.',

'capabilities.sustainment.deliver.performance.title': 'Performance Optimization',
'capabilities.sustainment.deliver.performance.desc': 'Ongoing tuning and enhancement to ensure systems continue to meet performance targets.',

'capabilities.sustainment.deliver.capacity.title': 'Capacity Management',
'capabilities.sustainment.deliver.capacity.desc': 'Proactive scaling and resource management to handle growth and demand fluctuations.',

'capabilities.sustainment.deliver.improvement.title': 'Continuous Improvement',
'capabilities.sustainment.deliver.improvement.desc': 'Regular reviews and enhancements that evolve your systems based on operational learnings.',

// --- Integrations ---
'capabilities.sustainment.integrations.title': 'Typical Integrations',
'capabilities.sustainment.integrations.intro': 'We integrate within your existing technology ecosystem and align with enterprise-grade platforms and delivery toolchains.',

'capabilities.sustainment.integrations.pagerduty': 'PagerDuty',
'capabilities.sustainment.integrations.datadog': 'Datadog',
'capabilities.sustainment.integrations.newrelic': 'New Relic',
'capabilities.sustainment.integrations.splunk': 'Splunk',
'capabilities.sustainment.integrations.servicenow': 'ServiceNow',
'capabilities.sustainment.integrations.jira': 'Jira Service Management',
'capabilities.sustainment.integrations.cloudwatch': 'AWS CloudWatch',
'capabilities.sustainment.integrations.azuremonitor': 'Azure Monitor',
'capabilities.sustainment.integrations.prometheus': 'Prometheus',
'capabilities.sustainment.integrations.grafana': 'Grafana',

// --- Example Deliverables ---
'capabilities.sustainment.examples.title': 'Example Deliverables',

'capabilities.sustainment.examples.item1': 'Service level agreements (SLAs)',
'capabilities.sustainment.examples.item2': 'Monitoring and alerting configurations',
'capabilities.sustainment.examples.item3': 'Incident response playbooks',
'capabilities.sustainment.examples.item4': 'Monthly operations reports',
'capabilities.sustainment.examples.item5': 'Compliance audit documentation',
'capabilities.sustainment.examples.item6': 'Continuous improvement roadmaps',

// ========================================
// CASE STUDIES PAGE
// Replacing Admin Work With Automation
// ========================================

// --- Hero ---
'caseStudies.adminAutomation.hero.title': 'Replacing Admin Work With Automation: A Real Setup Breakdown from Go High Level',
'caseStudies.adminAutomation.hero.subtitle': 'A real setup breakdown from Go High Level showing how automation replaced tedious administrative work without hiring more people.',
'caseStudies.adminAutomation.hero.tag1': 'Process Automation',
'caseStudies.adminAutomation.hero.tag2': 'Operations',
'caseStudies.adminAutomation.hero.tag3': 'Digital Services Business',
'caseStudies.adminAutomation.hero.bgAlt': 'Insurance protection background',

// --- Metrics Bar ---
'caseStudies.adminAutomation.metrics.item1.value': '60%+',
'caseStudies.adminAutomation.metrics.item1.label': 'Admin Tasks Automated',

'caseStudies.adminAutomation.metrics.item2.value': '45%↓',
'caseStudies.adminAutomation.metrics.item2.label': 'Manual Coordination',

'caseStudies.adminAutomation.metrics.item3.value': '35%↑',
'caseStudies.adminAutomation.metrics.item3.label': 'Operational Speed',

'caseStudies.adminAutomation.metrics.item4.value': '0',
'caseStudies.adminAutomation.metrics.item4.label': 'New Admin Hires',

// --- Context ---
'caseStudies.adminAutomation.context.label': 'The Context',
'caseStudies.adminAutomation.context.title': 'Admin work was slowing down growth.',
'caseStudies.adminAutomation.context.p1': "The business wasn't going down.",
'caseStudies.adminAutomation.context.p2': 'In reality, demand stayed the same.',
'caseStudies.adminAutomation.context.p3': 'Leads were coming in, clients were being helped, and money was coming in. But behind the scenes, the team was swamped with administrative tasks that had silently become a barrier to progress.',
'caseStudies.adminAutomation.context.p4': 'Manual tasks were a big part of daily operations:',

'caseStudies.adminAutomation.context.list1': 'Adding and updating leads',
'caseStudies.adminAutomation.context.list2': 'Follow-ups and reminders',
'caseStudies.adminAutomation.context.list3': 'Making appointments work together',
'caseStudies.adminAutomation.context.list4': 'Keeping track of status across spreadsheets',
'caseStudies.adminAutomation.context.list5': 'Internal transfers through email and WhatsApp',

'caseStudies.adminAutomation.context.p5': 'None of this effort brought in money directly, but it did take a lot of time, attention, and energy.',
'caseStudies.adminAutomation.context.p6': 'This case study shows how Go High Level used automation to replace tedious administrative tasks, making the business leaner, faster, and more scalable without hiring more people.',

// --- Challenge ---
'caseStudies.adminAutomation.challenge.label': 'The Challenge',
'caseStudies.adminAutomation.challenge.title': "People Doing Things That Aren't Human",
'caseStudies.adminAutomation.challenge.p1': 'People were needed to do jobs that systems should have done. Some of the main problems were:',

'caseStudies.adminAutomation.challenge.list1': 'Staff members spending hours entering data',
'caseStudies.adminAutomation.challenge.list2': 'Follow-ups that were missed because of manual tracking',
'caseStudies.adminAutomation.challenge.list3': 'Different people on the team use different processes',
'caseStudies.adminAutomation.challenge.list4': 'Handoffs and clearances that take too long',
'caseStudies.adminAutomation.challenge.list5': "No way to see what's going on in real time",

'caseStudies.adminAutomation.challenge.p2': "As the volume went up, the admin's workload expanded in a straight line. Having more customers meant more communications, more coordination, and more chances to make mistakes. The business was getting bigger, but it wasn't getting more efficient.",

// --- Approach ---
'caseStudies.adminAutomation.approach.label': 'Our Approach',
'caseStudies.adminAutomation.approach.title': "Why Hiring More Admin Staff Wasn’t the Answer",
'caseStudies.adminAutomation.approach.p1': 'Hiring more admin staff would have increased cost, complexity, and dependency without fixing the real issue. The problem wasn’t capacity — it was process design, and automation addressed the root cause by removing manual coordination entirely.',

// Phase 1
'caseStudies.adminAutomation.approach.phase1.title': 'Mapping Out Admin Tasks',
'caseStudies.adminAutomation.approach.phase1.duration': 'Weeks 1–2',
'caseStudies.adminAutomation.approach.phase1.desc': 'Before starting any work, Go High Level did a complete operational audit to understand where time and effort were being spent.',
'caseStudies.adminAutomation.approach.phase1.p1': 'We made a map of:',
'caseStudies.adminAutomation.approach.phase1.list1': 'Daily, weekly, and monthly chores for the admin',
'caseStudies.adminAutomation.approach.phase1.list2': 'How long each task takes',
'caseStudies.adminAutomation.approach.phase1.list3': 'Tasks that depend on each other',
'caseStudies.adminAutomation.approach.phase1.list4': 'Points where mistakes or delays happened',
'caseStudies.adminAutomation.approach.phase1.p2': 'This showed that more than 60% of the time spent on admin duties was spent on jobs that had clear guidelines and followed the same patterns, making them ideal candidates for automation.',

// Phase 2
'caseStudies.adminAutomation.approach.phase2.title': 'One System of Record',
'caseStudies.adminAutomation.approach.phase2.duration': 'Weeks 3–4',
'caseStudies.adminAutomation.approach.phase2.desc': 'One major issue was the excessive number of tools being used, which created duplication, confusion, and manual reconciliation.',
'caseStudies.adminAutomation.approach.phase2.p1': 'Go High Level put all of its operating data into one system of record. All leads, tasks, client updates, and status changes went to one place, eliminating the need for cross-checking and follow-ups.',

// Phase 3
'caseStudies.adminAutomation.approach.phase3.title': 'Automating Core Admin Workflows',
'caseStudies.adminAutomation.approach.phase3.duration': 'Weeks 5–7',
'caseStudies.adminAutomation.approach.phase3.desc': 'Once the data was in one place, Go High Level automated the most important administrative tasks, allowing the system to create, assign, and track work without manual intervention.',

// Phase 4
'caseStudies.adminAutomation.approach.phase4.title': 'Human Intervention Based on Exceptions',
'caseStudies.adminAutomation.approach.phase4.duration': 'Weeks 8–10',
'caseStudies.adminAutomation.approach.phase4.desc': 'Automation handled the “happy path,” and people were only notified when an exception occurred - such as a missed deadline, stalled lead, or situation requiring judgment.',

// Phase 5
'caseStudies.adminAutomation.approach.phase5.title': 'Reporting, Accountability, and Visibility',
'caseStudies.adminAutomation.approach.phase5.duration': 'Weeks 11–12',
'caseStudies.adminAutomation.approach.phase5.desc': 'Live dashboards replaced manual tracking and reporting, giving leadership real-time visibility into task progress, bottlenecks, and overall operational health without asking for updates.',

// --- Results ---
'caseStudies.adminAutomation.results.label': 'The Results',
'caseStudies.adminAutomation.results.title': 'From Manual Admin to Automated Operations',

'caseStudies.adminAutomation.results.card1.before': 'High',
'caseStudies.adminAutomation.results.card1.after': '60%+↓',
'caseStudies.adminAutomation.results.card1.label': 'Admin workload significantly reduced',

'caseStudies.adminAutomation.results.card2.before': 'Slow',
'caseStudies.adminAutomation.results.card2.after': '35%↑',
'caseStudies.adminAutomation.results.card2.label': 'Faster task completion',

'caseStudies.adminAutomation.results.card3.before': 'Frequent',
'caseStudies.adminAutomation.results.card3.after': '45%↓',
'caseStudies.adminAutomation.results.card3.label': 'Errors and missed follow-ups reduced',

'caseStudies.adminAutomation.results.card4.before': 'Manual',
'caseStudies.adminAutomation.results.card4.after': 'Automated',
'caseStudies.adminAutomation.results.card4.label': 'Lead handling and internal coordination',

// --- Testimonial ---
'caseStudies.adminAutomation.testimonial.quote': 'Our users now explore, interact, and complete actions instead of leaving after a few seconds. The redesign completely changed how people engage with our platform.',
'caseStudies.adminAutomation.testimonial.author': 'Head of Product',
'caseStudies.adminAutomation.testimonial.title': 'Digital Platform Company',

// --- CTA ---
'caseStudies.adminAutomation.cta.title': 'Want to Increase Engagement Without More Traffic?',
'caseStudies.adminAutomation.cta.subtitle': 'We help digital platforms turn passive visitors into active users through research-driven UX design.',
'caseStudies.adminAutomation.cta.primary': 'Schedule a Consultation',
'caseStudies.adminAutomation.cta.secondary': 'View More Case Studies',

// ========================================
// INSIGHTS PAGE
// Designing CI/CD Pipelines
// ========================================

// --- Hero ---
'insights.cicd.hero.category': 'IT Services & Advisory',
'insights.cicd.hero.date': 'February 04, 2026',
'insights.cicd.hero.title': 'Designing CI/CD Pipelines for High-Velocity Engineering Teams',
'insights.cicd.hero.excerpt': 'High-velocity engineering teams require more than speed alone. Well-designed CI/CD pipelines enable rapid software delivery while preserving quality, security, and operational reliability at scale.',
'insights.cicd.hero.bgAlt': 'Insurance protection background',

// --- Body Intro ---
'insights.cicd.body.p1': "In today's digital world, when there is a lot of competition, being quick is not an option; it's a must. Good-speed engineering teams need to be able to quickly add new features, repair defects, and keep the quality excellent, even when there are a lot of them. This is where setting up CI/CD pipelines is highly important for both rapid software delivery and long-term engineering speed.",

'insights.cicd.body.p2': 'A modern CI/CD pipeline enables teams to deploy changes quickly and safely without compromising security, stability, or developer confidence. As organizations adopt Agile and DevOps operating models, manual deployments, inconsistent environments, and slow feedback loops become operational risks. Purpose-built CI/CD pipelines address these challenges by enforcing standardization, automating quality controls, and ensuring consistency across environments.',

// --- Section 1 ---
'insights.cicd.section1.title': '1. Why CI/CD is Important for Engineering Teams That Work Quickly',
'insights.cicd.section1.p1': 'Engineers that work quickly are in charge of sites where the code changes all the time. Without a good CI/CD system, these changes can quickly make builds and deployments fail and slow down development.',
'insights.cicd.section1.p2': 'CI/CD pipelines now automatically build, test, and send out codes. This way, teams can focus on building new features instead of worrying about when to release them. When set up correctly, CI/CD pipelines serve as a safety net. They find problems early and make sure that goods are delivered on time and quickly.',

// --- Section 2 ---
'insights.cicd.section2.title': '2. The Main Ideas Underpinning Fast Software Delivery Pipelines',
'insights.cicd.section2.p1': 'To make fast software delivery pipelines work, CI/CD design needs to put speed and reliability first. The best pipelines do a fantastic job because they follow a few fundamental rules:',
'insights.cicd.section2.p2': "To start, make sure that everything functions on its own. Doing things by hand could make each step take longer. Whether you're modifying code or putting it into production, automation streamlines the process and ensures consistency every time.",
'insights.cicd.section2.p3': 'Testing should start early and go on all the time. You should perform unit tests, integration tests, and security checks as soon as you can. Finding problems sooner keeps the release cycle from slowing down later.',
'insights.cicd.section2.p4': '"Parallel execution" means running tests and builds at the same time. It speeds things up a lot, which helps teams keep up with quick release cycles.',

// --- Section 3 ---
'insights.cicd.section3.title': '3. Creating DevOps Pipelines That Can Scale Effectively Is Essential',
'insights.cicd.section3.p1': 'The Agile DevOps pipeline should change as the team does. As companies grow, their pipelines must be able to manage more services, contributors, and environments without failing.',
'insights.cicd.section3.p2': 'Scalable CI/CD systems share modular pipelines, reusable templates, and pipeline-as-code methods. This approach ensures uniformity across all projects, enabling teams to complete them swiftly.',
'insights.cicd.section3.p3': 'Cloud-native CI/CD solutions and containerized environments are also excellent for making things flexible and able to change.',
'insights.cicd.section3.p4': 'It is just as important to be able to see things. Teams can always make their delivery process better by keeping track of how well their pipelines are performing, how often they break, and how often they are used.',

// --- Section 4 ---
'insights.cicd.section4.title': '4. Helping With Quick Release Cycles While Keeping Quality High',
'insights.cicd.section4.p1': "Just because deployments happen rapidly doesn't mean they're awful. In their CI/CD pipelines, high-performing teams employ guardrails to establish the right balance between speed and quality.",
'insights.cicd.section4.p2': "Automated quality checks, approval processes for key jobs, and rollback mechanisms make sure that being speedy doesn't equal being less trustworthy.",
'insights.cicd.section4.p3': 'There should also be security integrated into the pipeline. Two examples of DevSecOps solutions that help teams ship faster and stay safe include automatic vulnerability identification and dependency checks.',

// --- Key Takeaways ---
'insights.cicd.takeaways.title': 'Key Takeaways',
'insights.cicd.takeaways.item1': 'CI/CD pipelines are foundational to sustained engineering velocity',
'insights.cicd.takeaways.item2': 'Automation, testing, and parallel execution enable rapid feedback loops',
'insights.cicd.takeaways.item3': 'Scalable pipeline design supports growth without operational friction',
'insights.cicd.takeaways.item4': 'Embedded quality and security guardrails protect reliability at speed',

// --- Conclusion ---
'insights.cicd.conclusion.title': 'Conclusion',
'insights.cicd.conclusion.p1': "When you build CI/CD pipelines for engineering teams that work swiftly, it's not just about automation. It's also about making them think they can get things done swiftly.",
'insights.cicd.conclusion.p2': 'Companies that want to speed up engineering in the long run should focus on fast software delivery pipelines, scalable agile DevOps pipelines, and quick release cycles with strict quality standards.',
'insights.cicd.conclusion.p3': 'A well-planned CI/CD pipeline is a strategic asset that helps teams come up with new ideas faster, react to change, and deliver users the same value every time.',

// --- Sidebar ---
'insights.cicd.sidebar.title': 'In This Article',
'insights.cicd.sidebar.item1': '1. Why CI/CD Matters',
'insights.cicd.sidebar.item2': '2. Core Principles',
'insights.cicd.sidebar.item3': '3. Scalable DevOps Pipelines',
'insights.cicd.sidebar.item4': '4. Quality & Security Guardrails',
'insights.cicd.sidebar.item5': '5. Conclusion',

// --- Share ---
'insights.cicd.share.title': 'Share This Article',
'insights.cicd.share.copied': 'Link copied!',

// ========================================
// CASE STUDY PAGE
// Build & Deployment Automation
// ========================================

// --- Hero ---
'caseStudies.buildDeploy.hero.tag1': 'Process Automation',
'caseStudies.buildDeploy.hero.tag2': 'Governance & Security',
'caseStudies.buildDeploy.hero.industry': 'Healthcare Payer Platform',
'caseStudies.buildDeploy.hero.title': 'Build & Deployment Automation for a Cloud-Based Healthcare Payer Suite',
'caseStudies.buildDeploy.hero.subtitle': 'A real delivery breakdown showing how compliance-aware automation improved release speed, operational stability, and confidence - without compromising regulatory control.',
'caseStudies.buildDeploy.hero.bgAlt': 'Insurance protection background',

// --- Metrics ---
'caseStudies.buildDeploy.metrics.item1.value': '55%↑',
'caseStudies.buildDeploy.metrics.item1.label': 'Faster Release Cycles',
'caseStudies.buildDeploy.metrics.item2.value': '50%↓',
'caseStudies.buildDeploy.metrics.item2.label': 'Deployment Errors',
'caseStudies.buildDeploy.metrics.item3.value': '40%↑',
'caseStudies.buildDeploy.metrics.item3.label': 'Operational Stability',
'caseStudies.buildDeploy.metrics.item4.value': '100%',
'caseStudies.buildDeploy.metrics.item4.label': 'Compliance-Aware Automation',

// --- Context ---
'caseStudies.buildDeploy.context.label': 'The Context',
'caseStudies.buildDeploy.context.title': 'Manual delivery was slowing a mission-critical platform',
'caseStudies.buildDeploy.context.p1': "Manual builds were making it harder to come up with new ideas. The healthcare payer suite was stable and reliable, but it was under a lot of stress because it was growing. The platform couldn't keep up with the new payer needs, regulatory changes, and feature updates that were coming in faster than it could release them.",
'caseStudies.buildDeploy.context.p2': 'There was still a lot of need. Clients needed the system to handle claims, keep track of policies, and make reports. But the processes for building and deploying were very manual, slow, and full of risks behind the scenes.',
'caseStudies.buildDeploy.context.p3': 'More than one team had to plan the releases. Deployment windows were short because of the risk of production. It took days instead of hours to make small changes to the settings. The system worked fine, but the delivery speed was off.',
'caseStudies.buildDeploy.context.p4': 'This case study shows how we automated the building and deployment of a cloud-based healthcare payer suite. This made it possible to release new versions more quickly while still keeping security, stability, and compliance.',

// --- Challenge ---
'caseStudies.buildDeploy.challenge.label': 'The Challenge',
'caseStudies.buildDeploy.challenge.title': 'Manual processes created delivery risk, not reliability',
'caseStudies.buildDeploy.challenge.p1': "The main problem wasn't the infrastructure or the engineering skills; it was how builds and deployments were done.",
'caseStudies.buildDeploy.challenge.p2': 'Here are some of the biggest problems:',
'caseStudies.buildDeploy.challenge.item1': 'How to build and deploy by hand in different situations',
'caseStudies.buildDeploy.challenge.item2': 'A lot of dependence on release engineers',
'caseStudies.buildDeploy.challenge.item3': 'Different ways to mix staging and production',
'caseStudies.buildDeploy.challenge.item4': 'Not a lot of ability to go back',
'caseStudies.buildDeploy.challenge.item5': 'Fear of deployments because they could cause downtime and problems with compliance',
'caseStudies.buildDeploy.challenge.item6': 'Not all services have the same release pipeline.',
'caseStudies.buildDeploy.challenge.p3': 'It was harder to make each new version as the platform grew. More features meant more planning, more checks, and more risk. Even though demand went up, speed went down.',

// --- Approach ---
'caseStudies.buildDeploy.approach.label': 'Our Approach',
'caseStudies.buildDeploy.approach.title': 'Automation built for control, not chaos',

// Phase 1
'caseStudies.buildDeploy.approach.phase1.number': '1',
'caseStudies.buildDeploy.approach.phase1.title': 'Checking the Build and Deployment Workflows',
'caseStudies.buildDeploy.approach.phase1.duration': 'Weeks 1–2',
'caseStudies.buildDeploy.approach.phase1.p1': 'We made a map of the whole release process, from committing code to putting it into production. There was a record of every manual step, permission barrier, and dependency.',
'caseStudies.buildDeploy.approach.phase1.p2': 'The audit found that more than 65% of the deployment work was repetitive and based on rules. This made it perfect for automation without breaking the rules.',

// Phase 2
'caseStudies.buildDeploy.approach.phase2.number': '2',
'caseStudies.buildDeploy.approach.phase2.title': 'Set up the same build pipelines for all services ',
'caseStudies.buildDeploy.approach.phase2.duration': 'Weeks 3–4',
'caseStudies.buildDeploy.approach.phase2.p1': 'We made standard, reusable build pipelines for every part of the healthcare payer suite.',
'caseStudies.buildDeploy.approach.phase2.p2': 'Some of the most important changes were:',
'caseStudies.buildDeploy.approach.phase2.item1': 'Consistent settings for building',
'caseStudies.buildDeploy.approach.phase2.item2': 'Equal settings for development, staging, and production',
'caseStudies.buildDeploy.approach.phase2.item3': 'Automatically versioning artifacts',
'caseStudies.buildDeploy.approach.phase2.item4': 'Safe handling of secrets',
'caseStudies.buildDeploy.approach.phase2.p3': 'This fixed problems that had caused deployments to fail in the past.',

// Phase 3
'caseStudies.buildDeploy.approach.phase3.number': '3',
'caseStudies.buildDeploy.approach.phase3.title': 'Automated Deployment with Compliance Guardrails',
'caseStudies.buildDeploy.approach.phase3.duration': 'Weeks 5–7',
'caseStudies.buildDeploy.approach.phase3.p1': 'We kept healthcare rules in mind when automating deployment. Automated pipelines made sure of the following:',
'caseStudies.buildDeploy.approach.phase3.item1': "Checks to make sure it's valid before deployment",
'caseStudies.buildDeploy.approach.phase3.item2': 'Approvals that are specific to the environment',
'caseStudies.buildDeploy.approach.phase3.item3': 'Auditing logs for every release',
'caseStudies.buildDeploy.approach.phase3.item4': 'Planned ways to launch',
'caseStudies.buildDeploy.approach.phase3.p2': 'Every deployment took the same safe path, which made things go faster and be less dangerous.',

// Phase 4
'caseStudies.buildDeploy.approach.phase4.number': '4',
'caseStudies.buildDeploy.approach.phase4.title': 'Monitoring, Rollbacks, and Release Visibility',
'caseStudies.buildDeploy.approach.phase4.duration': 'Weeks 8–10',
'caseStudies.buildDeploy.approach.phase4.p1': 'Instead of tracking status by hand, real-time deployment dashboards did the job. Right away, teams might see:',
'caseStudies.buildDeploy.approach.phase4.item1': 'Progress on deployment',
'caseStudies.buildDeploy.approach.phase4.item2': 'Things that can go wrong',
'caseStudies.buildDeploy.approach.phase4.item3': 'Ready to go back',
'caseStudies.buildDeploy.approach.phase4.item4': 'The health of the environment',
'caseStudies.buildDeploy.approach.phase4.p2': 'Automated rollback procedures made sure that problems could be fixed safely without causing long periods of downtime.',

// --- Results ---
'caseStudies.buildDeploy.results.label': 'The Results',
'caseStudies.buildDeploy.results.title': 'From manual releases to predictable, compliant delivery',
'caseStudies.buildDeploy.results.card1.before': 'Slow',
'caseStudies.buildDeploy.results.card1.after': '55% Faster',
'caseStudies.buildDeploy.results.card1.label': 'Release cycles',
'caseStudies.buildDeploy.results.card2.before': 'Error-Prone',
'caseStudies.buildDeploy.results.card2.after': '50%↓',
'caseStudies.buildDeploy.results.card2.label': 'Deployment failures',
'caseStudies.buildDeploy.results.card3.before': 'Fragile',
'caseStudies.buildDeploy.results.card3.after': 'Stable',
'caseStudies.buildDeploy.results.card3.label': 'Operational reliability',
'caseStudies.buildDeploy.results.card4.before': 'Manual',
'caseStudies.buildDeploy.results.card4.after': 'Governed',
'caseStudies.buildDeploy.results.card4.label': 'Compliance-ready releases',

// --- Testimonial ---
'caseStudies.buildDeploy.testimonial.quote': 'Our users now explore, interact, and complete actions instead of leaving after a few seconds. The redesign completely changed how people engage with our platform.',
'caseStudies.buildDeploy.testimonial.authorName': 'Head of Product',
'caseStudies.buildDeploy.testimonial.authorTitle': 'Digital Platform Company',

// --- CTA ---
'caseStudies.buildDeploy.cta.title': 'Want to Increase Engagement Without More Traffic?',
'caseStudies.buildDeploy.cta.subtitle': 'We help digital platforms turn passive visitors into active users through research-driven UX design.',
'caseStudies.buildDeploy.cta.primary': 'Schedule a Consultation',
'caseStudies.buildDeploy.cta.secondary': 'View More Case Studies',


// ========================================
// INSIGHT PAGE
// How to Evaluate & Choose the Right Web
// ========================================

// --- Hero ---
'insights.webPartner.hero.category': 'IT Services & Advisory',
'insights.webPartner.hero.date': 'February 05, 2026',
'insights.webPartner.hero.title': 'How to Evaluate & Choose the Right Web Development Partner for Long-Term Success',
'insights.webPartner.hero.excerpt': 'Choosing the right web development partner is a strategic decision. This guide explains how to evaluate partners beyond short-term delivery and select one that supports long-term growth, scalability, and business outcomes.',
'insights.webPartner.hero.bgAlt': 'Insurance protection background',

// --- Body Intro ---
'insights.webPartner.body.p1': 'In today\'s digital world, a website or app serves more than just an online presence. It helps your business expand, spreads the word about your brand, and is a long-term asset. No matter if you\'re a startup growing quickly, a company that has been around for a while and is going through a digital transformation, or a major company that wants to make things better for customers, it\'s very crucial to choose the correct web development partner.',
'insights.webPartner.body.p2': 'There are many agencies, development companies, and freelancers to choose from, which can make it hard to choose the ideal partner. This lesson teaches you how to pick web development partners carefully, putting long-term value ahead of quick delivery.',

// --- Section 1 ---
'insights.webPartner.section1.title': '1. Why it\'s important to pick the right web development partner',
'insights.webPartner.section1.p1': 'Engineers A web development connection isn\'t just a one-time thing; it could last for years. The right partner will help you make digital tools that help you reach your business goals, finish projects on time and on budget, and grow your platforms as your firm grows. They help get your digital infrastructure ready for things like AI improvements, faster speeds, or new integrations in the future.',
'insights.webPartner.section1.p2': 'More than 85% of digital projects fail because the technology doesn\'t work with the partner or the partner isn\'t right, according to a study. A powerful growth partner is like a teammate. They provide you advice, help you deal with problems, and support your plan as you go.',

// --- Section 2 ---
'insights.webPartner.section2.title': '2. Set the needs and goals for your project',
'insights.webPartner.section2.p1': 'Before you talk to potential partners, you need to be clear. First, you need to know what issue you\'re trying to solve, who you\'re trying to reach, how much money you have to spend, how long you have to do it, and what success metrics are most important to you, like SEO performance, conversions, or speed. Determine whether you require a website, a web application, an e-commerce platform, or system integrations.',
'insights.webPartner.section2.p2': 'Include this in a Project Requirements Document (PRD). It\'s easier to check if offers are valid, negotiations go more smoothly, and suppliers can be compared fairly when there is a clear PRD.',
'insights.webPartner.section2.imageAlt': 'How to Evaluate & Choose the Right Web Development Partner for Long-Term Success',

// --- Section 3 ---
'insights.webPartner.section3.title': '3. What to Look for in a Partner for Web Development',

'insights.webPartner.section3.sub1.title': 'Technical Expertise and Technology Alignment',
'insights.webPartner.section3.sub1.p1': 'Check to see if the partner has worked with the tools, frameworks, CMS platforms, cloud infrastructure, and other technologies that your project needs to run. When technical alignment is strong, the risk goes down, and it is easier to keep things running over time.',

'insights.webPartner.section3.sub2.title': 'Industry Knowledge and Experience',
'insights.webPartner.section3.sub2.p1': 'Partners that have worked in the same field before know the rules, what consumers want, and what problems come up every day. You can make better decisions and get things done faster with this information.',

'insights.webPartner.section3.sub3.title': 'Portfolio and Case Studies',
'insights.webPartner.section3.sub3.p1': 'Look at previous work to see how useful it is, how effectively the UI/UX works, how quickly it responds, and how well it meets business goals. You can think strategically and solve problems, as evidenced by case studies.',

'insights.webPartner.section3.sub4.title': 'Communication and Collaboration Model',
'insights.webPartner.section3.sub4.p1': 'Effective communication prevents misunderstandings and excessive delays. Determine the frequency of updates, the tools utilized, and the presence of a project manager for oversight.',

'insights.webPartner.section3.sub5.title': 'Security, Scalability, and Delivery Process',
'insights.webPartner.section3.sub5.p1': 'You can trust partners who implement organized methods such as Agile, prioritize security and compliance, and plan for growth by monitoring performance and performing regular maintenance.',

'insights.webPartner.section3.sub6.title': 'Transparent Pricing and Long-Term Value',
'insights.webPartner.section3.sub6.p1': 'Instead of looking for the cheapest choice, look for the best value. Look for detailed cost breakdowns, realistic schedules, and choices for long-term help.',

// --- Key Takeaways ---
'insights.webPartner.keyTakeaways.title': 'Key Takeaways',
'insights.webPartner.keyTakeaways.item1': 'Web development partnerships are long-term strategic relationships',
'insights.webPartner.keyTakeaways.item2': 'Clear requirements enable better partner evaluation and alignment',
'insights.webPartner.keyTakeaways.item3': 'Industry experience and technical fit reduce delivery risk',
'insights.webPartner.keyTakeaways.item4': 'Transparency, security, and scalability matter more than short-term cost',

// --- Section 4 ---
'insights.webPartner.section4.title': '4. Final Partner Evaluation Checklist',
'insights.webPartner.section4.p1': 'Before making a final decision, confirm that you have:',
'insights.webPartner.section4.item1': 'Documented clear project goals and requirements',
'insights.webPartner.section4.item2': 'Reviewed portfolios and validated references',
'insights.webPartner.section4.item3': 'Evaluated communication and delivery processes',
'insights.webPartner.section4.item4': 'Confirmed security, compliance, and scalability plans',
'insights.webPartner.section4.item5': 'Reviewed pricing and long-term support models',

// --- Conclusion ---
'insights.webPartner.conclusion.title': 'Conclusion',
'insights.webPartner.conclusion.p1': 'Choosing the right web development partner is a critical business decision that directly impacts your organization’s digital success. By prioritizing alignment, governance, and long-term value, you can build a partnership that supports sustainable growth and continuous improvement.',
'insights.webPartner.conclusion.p2': 'The right partner does more than deliver software - they help you build a resilient digital foundation that evolves with your business.',

// --- Sidebar ---
'insights.webPartner.sidebar.toc.title': 'In This Article',
'insights.webPartner.sidebar.toc.item1': '1. Why Partner Choice Matters',
'insights.webPartner.sidebar.toc.item2': '2. Define Project Needs',
'insights.webPartner.sidebar.toc.item3': '3. What to Look for in a Partner',
'insights.webPartner.sidebar.toc.item4': '4. Final Evaluation Checklist',
'insights.webPartner.sidebar.toc.item5': '5. Conclusion',

'insights.webPartner.sidebar.share.title': 'Share This Article',
'insights.webPartner.sidebar.share.copied': 'Link copied!',


// ========================================
// CASE STUDY PAGE
// How We Deliver High-Performance Web Platforms
// ========================================

// --- Hero ---
'caseStudies.highPerformance.hero.tag1': 'Web Performance',
'caseStudies.highPerformance.hero.tag2': 'Platform Architecture',
'caseStudies.highPerformance.hero.industry': 'Digital Platform',
'caseStudies.highPerformance.hero.title': 'How We Deliver High-Performance Web Platforms',
'caseStudies.highPerformance.hero.subtitle': 'A real delivery breakdown showing how performance-first architecture improved speed, engagement, and scalability without rebuilding infrastructure.',
'caseStudies.highPerformance.hero.bgAlt': 'Insurance protection background',

// --- Metrics ---
'caseStudies.highPerformance.metrics.item1.value': '50%↓',
'caseStudies.highPerformance.metrics.item1.label': 'Page Load Time',
'caseStudies.highPerformance.metrics.item2.value': '40%↓',
'caseStudies.highPerformance.metrics.item2.label': 'Bounce Rate',
'caseStudies.highPerformance.metrics.item3.value': '30%↑',
'caseStudies.highPerformance.metrics.item3.label': 'User Engagement',
'caseStudies.highPerformance.metrics.item4.value': '0',
'caseStudies.highPerformance.metrics.item4.label': 'Infrastructure Rebuilds',

// --- Context ---
'caseStudies.highPerformance.context.label': 'The Context',
'caseStudies.highPerformance.context.title': 'The platform was being held back by performance',
'caseStudies.highPerformance.context.p1': 'The platform wasn\'t broken, but it could have been better. There was a lot of traffic, new features were added all the time, and people were still highly interested. But behind the scenes, problems with performance were slowly making the user experience and scalability worse.',
'caseStudies.highPerformance.context.p2': 'When there were a lot of people on the site, it took a long time for pages to load. There were times when new features made things worse. Developers spent more time fixing issues than making the product better. These problems weren\'t too severe, but they did slow things down.',
'caseStudies.highPerformance.context.p3': 'This case study shows how we made a high-performance online platform by changing the way it was planned, improving the way it was delivered, and making performance a part of every stage of the process.',

// --- Challenge ---
'caseStudies.highPerformance.challenge.label': 'The Challenge',
'caseStudies.highPerformance.challenge.title': 'The issue wasn’t technology - it was delivery methodology',
'caseStudies.highPerformance.challenge.p1': 'The main problem was not the lack of skills or tools; it was how performance was managed.',
'caseStudies.highPerformance.challenge.p2': 'Some of the greatest problems were:',
'caseStudies.highPerformance.challenge.item1': 'Enhancing performance is too late in the life cycle.',
'caseStudies.highPerformance.challenge.item2': 'Teams that just work on the front end and back end',
'caseStudies.highPerformance.challenge.item3': 'There are no fixed rules for how well things should work.',
'caseStudies.highPerformance.challenge.item4': 'Testing by hand and fixing problems as they come up',
'caseStudies.highPerformance.challenge.item5': 'We were unable to see how well actual users performed.',
'caseStudies.highPerformance.challenge.p3': 'With each new release, the risk grew as more individuals used the product. The platform was getting bigger, but it wasn\'t getting better at what it did.',

// --- Approach ---
'caseStudies.highPerformance.approach.label': 'Our Approach',
'caseStudies.highPerformance.approach.title': 'Designing for performance from day one',

// Phase 1
'caseStudies.highPerformance.approach.phase1.number': '1',
'caseStudies.highPerformance.approach.phase1.title': 'Setting Performance Baselines',
'caseStudies.highPerformance.approach.phase1.duration': 'Weeks 1–2',
'caseStudies.highPerformance.approach.phase1.p1': 'We started by checking out the platform\'s frontend, backend, and infrastructure levels. We selected crucial numbers like load time, API response, and Core Web Vitals as benchmarks to give us a clear place to start.',
'caseStudies.highPerformance.approach.phase1.p2': 'This quickly showed where performance problems had the biggest effect on the business.',

// Phase 2
'caseStudies.highPerformance.approach.phase2.number': '2',
'caseStudies.highPerformance.approach.phase2.title': 'Web Architecture That Puts Performance First',
'caseStudies.highPerformance.approach.phase2.duration': 'Weeks 3–4',
'caseStudies.highPerformance.approach.phase2.p1': 'We didn\'t just make small adjustments; we rewrote important elements of the system using performance-first principles:',
'caseStudies.highPerformance.approach.phase2.item1': 'Things on the front end that can be changed',
'caseStudies.highPerformance.approach.phase2.item2': 'Better answers from the API',
'caseStudies.highPerformance.approach.phase2.item3': 'Ways to cache that work',
'caseStudies.highPerformance.approach.phase2.item4': 'Cloud infrastructure that can grow',
'caseStudies.highPerformance.approach.phase2.p2': 'This ensured the web platform could evolve without constant maintenance.',

// Phase 3
'caseStudies.highPerformance.approach.phase3.number': '3',
'caseStudies.highPerformance.approach.phase3.title': 'Delivery Pipelines with Automated Performance Checks',
'caseStudies.highPerformance.approach.phase3.duration': 'Weeks 5–7',
'caseStudies.highPerformance.approach.phase3.p1': 'We added performance testing right into the process of producing and distributing. Before going live, every release was automatically checked to make sure it met performance standards.',
'caseStudies.highPerformance.approach.phase3.p2': 'This procedure got rid of regressions and made it so that manual testing was no longer needed.',

// Phase 4
'caseStudies.highPerformance.approach.phase4.number': '4',
'caseStudies.highPerformance.approach.phase4.title': 'Watching and growing better in real time',
'caseStudies.highPerformance.approach.phase4.duration': 'Weeks 8–10',
'caseStudies.highPerformance.approach.phase4.p1': 'Live monitoring dashboards showed how well real users were doing. Teams can find problems immediately, including slowdowns, traffic surges, or errors, without having to wait for users to complain.',

// --- Results ---
'caseStudies.highPerformance.results.label': 'The Results',
'caseStudies.highPerformance.results.title': 'Performance became a competitive advantage',
'caseStudies.highPerformance.results.card1.before': 'Slow',
'caseStudies.highPerformance.results.card1.after': '50%↓',
'caseStudies.highPerformance.results.card1.label': 'Faster page loads',
'caseStudies.highPerformance.results.card2.before': 'High',
'caseStudies.highPerformance.results.card2.after': '40%↓',
'caseStudies.highPerformance.results.card2.label': 'Bounce rate reduced',
'caseStudies.highPerformance.results.card3.before': 'Low',
'caseStudies.highPerformance.results.card3.after': '30%↑',
'caseStudies.highPerformance.results.card3.label': 'User engagement increased',
'caseStudies.highPerformance.results.card4.before': 'Risky',
'caseStudies.highPerformance.results.card4.after': 'Stable',
'caseStudies.highPerformance.results.card4.label': 'Faster releases with fewer rollbacks',

// --- Testimonial ---
'caseStudies.highPerformance.testimonial.quote': 'Our users now explore, interact, and complete actions instead of leaving after a few seconds. The redesign completely changed how people engage with our platform.',
'caseStudies.highPerformance.testimonial.authorName': 'Head of Product',
'caseStudies.highPerformance.testimonial.authorTitle': 'Digital Platform Company',

// --- CTA ---
'caseStudies.highPerformance.cta.title': 'Want to Increase Engagement Without More Traffic?',
'caseStudies.highPerformance.cta.subtitle': 'We help digital platforms turn passive visitors into active users through research-driven UX design.',
'caseStudies.highPerformance.cta.primary': 'Schedule a Consultation',
'caseStudies.highPerformance.cta.secondary': 'View More Case Studies',

// ========================================
// INSIGHT PAGE
// The Connection Between Web Architecture, SEO & Digital Growth
// ========================================

// --- Hero ---
'insights.webArchitecture.hero.category': 'Web Architecture & SEO',
'insights.webArchitecture.hero.date': 'February 06, 2026',
'insights.webArchitecture.hero.title': 'The Connection Between Web Architecture, SEO & Digital Growth',
'insights.webArchitecture.hero.excerpt': 'Web architecture forms the technical foundation of SEO and long-term digital growth. This article explains how structure, performance, and scalability directly influence search visibility, user experience, and business outcomes.',
'insights.webArchitecture.hero.bgAlt': 'Insurance protection background',

// --- Body ---
'insights.webArchitecture.body.p1': 'In today\'s digital-first world, a website is more than just a nice picture. It is also a technical base that has an effect on how easy it is to find in search engines, how well it works for users, and how well the business does in the long run. At the core of this foundation is web architecture. How search engines analyze, index, and rank your website is incredibly significant. Web architecture and SEO work together to build a robust engine that will help you succeed online for a long time.',

// Section 1
'insights.webArchitecture.section1.title': '1. What does it mean to have web architecture?',
'insights.webArchitecture.section1.p1': 'The sequence of the pages, the structure of the URLs, the internal linking, the navigation, and the technological setup are all part of web architecture. A structure that is carefully thought out makes it easy for visitors and search engines to understand and use the site.',
'insights.webArchitecture.section1.p2': 'When the architecture is bad, things run slowly, links fail, content duplicates, and crawling is hard. All of these factors are bad for SEO and getting people to utilize your site.',

// Section 2
'insights.webArchitecture.section2.title': '2. How the layout of a website influences SEO',
'insights.webArchitecture.section2.p1': 'Search engines demand your website to have a clear structure. When the design is clear and makes sense, search engine bots can crawl and index content correctly. You can share link equity by effectively using categories, ensuring clarity in your URLs, and appropriately linking to the relevant pages.',
'insights.webArchitecture.section2.p2': 'Site speed and how well it functions on mobile devices are two very important architectural factors that affect ranking. A lightweight codebase, efficient assets, and scalable infrastructure all help with load times and lower bounce rates. These things all have an effect on search rankings.',
'insights.webArchitecture.section2.p3': 'Structured navigation also helps people find things faster, which keeps them on the site longer and minimizes pogo-sticking. Both of these things are beneficial for SEO.',

// Section 3
'insights.webArchitecture.section3.title': '3. How SEO Helps Digital Growth',
'insights.webArchitecture.section3.p1': 'SEO isn\'t only about achieving high rankings; it\'s also about acquiring traffic that is likely to become sales. When web design follows SEO best practices, businesses enjoy more organic traffic, a better user experience, and higher conversion rates.',
'insights.webArchitecture.section3.p2': 'A design that can grow allows businesses to add additional content, services, and markets without compromising their search engine rankings. This level of flexibility is necessary for long-term digital growth.',

// Section 4
'insights.webArchitecture.section4.title': '4. Web Architecture as a Way to Get Bigger',
'insights.webArchitecture.section4.p1': 'Companies that make effective web architecture from the start don\'t have to pay for expensive fixes later. Design that is good for SEO helps with content marketing, makes it easier for users to find your site, and makes your business look more trustworthy. As organic traffic increases, the requirement for paid ads decreases, which over time leads to a better return on investment.',
'insights.webArchitecture.section4.p2': 'On the other hand, failing to design your architecture can hold down growth, even if you have superb content and marketing.',

// --- Key Takeaways ---
'insights.webArchitecture.takeaways.title': 'Key Takeaways',
'insights.webArchitecture.takeaways.item1': 'Web architecture is the foundation of SEO performance',
'insights.webArchitecture.takeaways.item2': 'Clear structure improves crawlability and indexation',
'insights.webArchitecture.takeaways.item3': 'Performance and mobile optimization directly impact rankings',
'insights.webArchitecture.takeaways.item4': 'Scalable architecture supports long-term digital growth',

// --- Conclusion ---
'insights.webArchitecture.conclusion.title': 'Conclusion',
'insights.webArchitecture.conclusion.p1': 'Web architecture, SEO, and digital growth are closely connected. A well-organized website makes it easier for search engines to find your information, improves the user experience, and gives your business a platform that can expand with it. By ensuring that site architecture and SEO strategy work together, businesses can build a strong digital foundation that helps them stay visible, engage customers, and succeed in the long run.',

// --- Sidebar ---
'insights.webArchitecture.sidebar.tocTitle': 'In This Article',
'insights.webArchitecture.sidebar.item1': '1. What does it mean to have web architecture?',
'insights.webArchitecture.sidebar.item2': '2. How the layout of a website influences SEO',
'insights.webArchitecture.sidebar.item3': '3. How SEO Helps Digital Growth',
'insights.webArchitecture.sidebar.item4': '4. Web Architecture as a Way to Get Bigger',
'insights.webArchitecture.sidebar.item5': '5. Conclusion',
'insights.webArchitecture.sidebar.shareTitle': 'Share This Article',
'insights.webArchitecture.sidebar.copyFeedback': 'Link copied!',

// ========================================
// CASE STUDY PAGE
// Automating Lead Follow-Ups for a Plumbing Business
// ========================================

// --- Hero ---
'caseStudies.plumbing.hero.tag1': 'Automation',
'caseStudies.plumbing.hero.tag2': 'Lead Management',
'caseStudies.plumbing.hero.industry': 'Local Services',
'caseStudies.plumbing.hero.title': 'Automating Lead Follow-Ups for a Plumbing Business',
'caseStudies.plumbing.hero.subtitle': 'How a local plumbing company increased bookings and revenue by automating lead follow-ups without increasing ad spend or headcount.',
'caseStudies.plumbing.hero.bgAlt': 'Insurance protection background',

// --- Metrics ---
'caseStudies.plumbing.metrics.item1.value': '80%↓',
'caseStudies.plumbing.metrics.item1.label': 'Response Time',
'caseStudies.plumbing.metrics.item2.value': '47%↑',
'caseStudies.plumbing.metrics.item2.label': 'Booked Jobs',
'caseStudies.plumbing.metrics.item3.value': '35%↑',
'caseStudies.plumbing.metrics.item3.label': 'Monthly Revenue',
'caseStudies.plumbing.metrics.item4.value': '0',
'caseStudies.plumbing.metrics.item4.label': 'Missed Leads',

// --- Context ---
'caseStudies.plumbing.context.label': 'The Context',
'caseStudies.plumbing.context.title': 'High lead volume, low follow-through',
'caseStudies.plumbing.context.p1': 'A medium-sized plumbing business serving a local metro area was generating a steady flow of leads from its website, Google Ads, emergency service requests, and phone inquiries.',
'caseStudies.plumbing.context.p2': 'Demand was strong, but bookings were inconsistent. The issue wasn’t marketing - it was slow and unreliable lead follow-up that caused potential customers to move on to competitors.',
'caseStudies.plumbing.context.p3': 'This case study outlines how automating lead follow-ups transformed response times, increased conversions, and unlocked revenue growth without additional marketing spend.',

// --- Challenge ---
'caseStudies.plumbing.challenge.label': 'The Challenge',
'caseStudies.plumbing.challenge.title': 'Manual follow-up was costing revenue',
'caseStudies.plumbing.challenge.p1': 'Before automation, a small office team manually handled every lead. This approach created operational strain and lost opportunities.',
'caseStudies.plumbing.challenge.item1': 'Leads were contacted hours later or the next day',
'caseStudies.plumbing.challenge.item2': 'After-hours and busy-period leads were missed entirely',
'caseStudies.plumbing.challenge.item3': 'Inconsistent messaging and no structured follow-up',
'caseStudies.plumbing.challenge.item4': 'Leads frequently chose competitors who responded faster',
'caseStudies.plumbing.challenge.p2': 'In emergency plumbing situations, speed determines trust. Delayed responses directly translated into lost jobs.',

// --- Approach ---
'caseStudies.plumbing.approach.label': 'Our Approach',
'caseStudies.plumbing.approach.title': 'Automated, fast, and human-centered follow-up',

// Phase 1
'caseStudies.plumbing.approach.phase1.number': '1',
'caseStudies.plumbing.approach.phase1.title': 'Centralized Lead Capture',
'caseStudies.plumbing.approach.phase1.duration': 'Weeks 1',
'caseStudies.plumbing.approach.phase1.p1': 'All leads from website forms, ads, emergency requests, and calls were routed into a single CRM. This ensured visibility, ownership, and zero lead loss.',

// Phase 2
'caseStudies.plumbing.approach.phase2.number': '2',
'caseStudies.plumbing.approach.phase2.title': 'Immediate Automated Responses',
'caseStudies.plumbing.approach.phase2.duration': 'Weeks 2',
'caseStudies.plumbing.approach.phase2.p1': 'Within 60 seconds of sending in a form or query, prospects got the following:',
'caseStudies.plumbing.approach.phase2.item1': 'A personalized SMS message letting them know they got their request',
'caseStudies.plumbing.approach.phase2.item2': 'An email with information about the service and what to do next',
'caseStudies.plumbing.approach.phase2.item3': 'This rapid answer made clients feel like help was on the way.',

// Phase 3
'caseStudies.plumbing.approach.phase3.number': '3',
'caseStudies.plumbing.approach.phase3.title': 'Smart Follow-Up Sequences',
'caseStudies.plumbing.approach.phase3.duration': 'Weeks 3',
'caseStudies.plumbing.approach.phase3.p1': 'If a lead didn’t book immediately, the system triggered timed follow-ups at two hours, one day, and three days - maintaining momentum without being intrusive.',

// Phase 4
'caseStudies.plumbing.approach.phase4.number': '4',
'caseStudies.plumbing.approach.phase4.title': 'Scheduling & Team Alerts',
'caseStudies.plumbing.approach.phase4.duration': 'Weeks 4',
'caseStudies.plumbing.approach.phase4.p1': 'Leads could book appointments instantly via scheduling links, while office staff received real-time alerts for replies, bookings, and high-intent keywords.',

// --- Results ---
'caseStudies.plumbing.results.label': 'The Results',
'caseStudies.plumbing.results.title': 'Automation delivered measurable growth',
'caseStudies.plumbing.results.card1.before': 'Hours',
'caseStudies.plumbing.results.card1.after': '< 1 min',
'caseStudies.plumbing.results.card1.label': 'Response time reduced',
'caseStudies.plumbing.results.card2.before': 'Low',
'caseStudies.plumbing.results.card2.after': '47%↑',
'caseStudies.plumbing.results.card2.label': 'More leads converted to jobs',
'caseStudies.plumbing.results.card3.before': 'Flat',
'caseStudies.plumbing.results.card3.after': '35%↑',
'caseStudies.plumbing.results.card3.label': 'Monthly revenue growth',
'caseStudies.plumbing.results.card4.before': 'Manual',
'caseStudies.plumbing.results.card4.after': 'Automated',
'caseStudies.plumbing.results.card4.label': 'Zero missed leads',

// --- Testimonial ---
'caseStudies.plumbing.testimonial.quote': 'Our users now explore, interact, and complete actions instead of leaving after a few seconds. The redesign completely changed how people engage with our platform.',
'caseStudies.plumbing.testimonial.authorName': 'Head of Product',
'caseStudies.plumbing.testimonial.authorTitle': 'Digital Platform Company',

// --- CTA ---
'caseStudies.plumbing.cta.title': 'Want to Increase Engagement Without More Traffic?',
'caseStudies.plumbing.cta.subtitle': 'We help digital platforms turn passive visitors into active users through research-driven UX design.',
'caseStudies.plumbing.cta.primary': 'Schedule a Consultation',
'caseStudies.plumbing.cta.secondary': 'View More Case Studies',

// ========================================
// CONTACT PAGE
// Book a Discovery Call
// ========================================

// --- Hero ---
'contact.discovery.hero.title': 'Book a Discovery Call',
'contact.discovery.hero.subtitle': 'A structured conversation about your operations — no sales pitch. Pick a time that works for you.',
'contact.discovery.hero.bgAlt': 'Insurance protection background',

// ========================================
// INSIGHTS ARTICLE
// AI Adoption Roadmap (Full Literal Extraction)
// ========================================

// --- Hero ---
'insights.aiAdoption.hero.image.alt': 'Insurance protection background',
'insights.aiAdoption.hero.category': 'AI Strategy ',
'insights.aiAdoption.hero.date': 'February 26, 2026',
'insights.aiAdoption.hero.title': 'AI Adoption Roadmap for Mid-Sized Enterprises',
'insights.aiAdoption.hero.excerpt': 'AI is no longer reserved for tech giants. Mid-sized enterprises can now deploy governed, scalable AI systems - if they follow a structured roadmap aligned to business outcomes.',

// --- Body Intro ---
'insights.aiAdoption.body.intro.p1': 'Tech companies don\'t have a monopoly on artificial intelligence anymore. Today, mid-sized businesses may use strong AI tools to make their operations more efficient, cut expenses, and find new ways to make money. But it doesn\'t just happen that AI adoption works out. It needs a well-planned roadmap that connects technology to business strategy, establishes strong data foundations, and scales in a smart way.',
'insights.aiAdoption.body.intro.p2': 'Here\'s a realistic, step-by-step guide to help you get started with AI if you\'re a mid-sized business.',

// --- Section 1 ---
'insights.aiAdoption.body.businessGoals.title': '1. Set clear goals for your business',
'insights.aiAdoption.body.businessGoals.p1': 'AI should never say, "Let\'s try something cool" at the outset. The first question should be, "What problem are we trying to solve?"',
'insights.aiAdoption.body.businessGoals.p2': 'Find locations that will have a big influence, such as:',
'insights.aiAdoption.body.businessGoals.item1': 'Making customer service respond faster',
'insights.aiAdoption.body.businessGoals.item2': 'Making operations more efficient',
'insights.aiAdoption.body.businessGoals.item3': 'Making sales forecasts more accurate',
'insights.aiAdoption.body.businessGoals.item4': 'Making sales forecasts more accurate',
'insights.aiAdoption.body.businessGoals.p3': 'Look at use cases that have a direct effect on income, savings, or customer satisfaction. It\'s easier to quantify performance when the business goal is clear.',

// --- Section 2 ---
'insights.aiAdoption.body.readiness.title': '2. Check to see whether you\'re ready for AI',
'insights.aiAdoption.body.readiness.p1': 'Before you buy AI tools, think about what you can already do. MIT CISR research shows that a lot of companies have problems since they start using AI without knowing how mature they are.',
'insights.aiAdoption.body.readiness.p2': 'Important things to look at:',
'insights.aiAdoption.body.readiness.item1': 'Data Quality: Is data clean, structured, and reliable?',
'insights.aiAdoption.body.readiness.item2': 'Infrastructure: Can systems support scalable AI workloads?',
'insights.aiAdoption.body.readiness.item3': 'Talent & Capabilities: Do internal teams possess data literacy and AI oversight skills?',
'insights.aiAdoption.body.readiness.item4': 'Governance: Are compliance, privacy, and security frameworks established?',
'insights.aiAdoption.body.readiness.p3': 'This evaluation eliminates costly mistakes and creates reasonable goals.',

// --- Image ---
'insights.aiAdoption.body.image.alt': 'AI Adoption Roadmap for Mid-Sized Enterprises',

// --- Section 3 ---
'insights.aiAdoption.body.dataFoundation.title': '3. Build a Strong Data Foundation',
'insights.aiAdoption.body.dataFoundation.p1': 'Data is what AI needs to work. AI projects will stop if your data is spread out across departments or stuck in old systems.',
'insights.aiAdoption.body.dataFoundation.p2': 'Mid-sized businesses should put the following at the top of their lists:',
'insights.aiAdoption.body.dataFoundation.item1': 'Centralized data storage, like data lakes or unified platforms',
'insights.aiAdoption.body.dataFoundation.item2': 'Cleaning and standardizing data',
'insights.aiAdoption.body.dataFoundation.item3': 'Policies for clear data ownership and governance',
'insights.aiAdoption.body.dataFoundation.p3': 'Databricks and other platforms let businesses bring together data and analytics in one place, which lowers silos and makes it easier for people to work together.',
'insights.aiAdoption.body.dataFoundation.p4': 'Even the best AI models won\'t work well if they don\'t have access to accurate data.',

// --- Section 4 ---
'insights.aiAdoption.body.pilots.title': '4. Start with pilot projects that have a big effect',
'insights.aiAdoption.body.pilots.p1': 'Instead than trying to change the whole firm at once, start with small trial projects.',
'insights.aiAdoption.body.pilots.p2': 'The best pilot traits are:',
'insights.aiAdoption.body.pilots.item1': 'Clearly defined scope',
'insights.aiAdoption.body.pilots.item2': 'Measurable success metrics',
'insights.aiAdoption.body.pilots.item3': 'Strong executive sponsorship',
'insights.aiAdoption.body.pilots.item4': 'Defined ROI tracking mechanisms',
'insights.aiAdoption.body.pilots.p3': 'For instance, using an AI chatbot to help customers or using predictive analytics to manage inventory.',
'insights.aiAdoption.body.pilots.p4': 'IBM and other companies stress how important it is to start small but plan for growth from the beginning. Early wins boost confidence within the company and make more investment seem worth it.',

// --- Section 5 ---
'insights.aiAdoption.body.governance.title': '5. Set up risk management and governance',
'insights.aiAdoption.body.governance.p1': 'Governance becomes more important as AI systems make judgments.',
'insights.aiAdoption.body.governance.p2': 'Medium-sized businesses need to make rules about:',
'insights.aiAdoption.body.governance.item1': 'Data privacy and regulatory compliance',
'insights.aiAdoption.body.governance.item2': 'Model transparency and explainability',
'insights.aiAdoption.body.governance.item3': 'Bias detection and ethical use standards',
'insights.aiAdoption.body.governance.item4': 'Performance monitoring and auditability',
'insights.aiAdoption.body.governance.p3': 'Advisory organizations like Gartner say that companies should balance innovation with risk management to prevent regulatory and reputational problems.',
'insights.aiAdoption.body.governance.p4': 'Strong governance generates trust with customers, employees, and other important people.',

// --- Section 6 ---
'insights.aiAdoption.body.talent.title': '6. Build an AI culture and grow talent',
'insights.aiAdoption.body.talent.p1': 'AI transformation is as much cultural as it is technical.',
'insights.aiAdoption.body.talent.p2': 'Organizations should:',
'insights.aiAdoption.body.talent.item1': 'Upskill staff in data literacy and AI fundamentals',
'insights.aiAdoption.body.talent.item2': 'Encourage cross-functional collaboration',
'insights.aiAdoption.body.talent.item3': 'Engage external experts where specialized capability is required',
'insights.aiAdoption.body.talent.item4': 'Communicate how AI enhances roles rather than replacing them',
'insights.aiAdoption.body.talent.p3': 'Adoption accelerates when business users - not just IT teams - are empowered to leverage AI tools responsibly.',

// --- Section 7 ---
'insights.aiAdoption.body.workflow.title': '7. Integrate AI into Core Workflows',
'insights.aiAdoption.body.workflow.p1': 'AI delivers value when embedded directly into operational systems - not when isolated as a dashboard.',
'insights.aiAdoption.body.workflow.p2': 'This includes:',
'insights.aiAdoption.body.workflow.item1': 'Integrating AI outputs into CRM, ERP, and finance systems',
'insights.aiAdoption.body.workflow.item2': 'Automating routine decisions with human oversight controls',
'insights.aiAdoption.body.workflow.item3': 'Continuously refining models based on operational feedback',
'insights.aiAdoption.body.workflow.p3': 'AI should support real-time decision-making within daily workflows.',

// --- Section 8 ---
'insights.aiAdoption.body.scaling.title': '8. Scale with Structured Architecture',
'insights.aiAdoption.body.scaling.p1': 'Once pilots demonstrate measurable impact, scaling must be deliberate - not fragmented.',
'insights.aiAdoption.body.scaling.p2': 'Scaling requires:',
'insights.aiAdoption.body.scaling.item1': 'Standardized platforms and shared data environments',
'insights.aiAdoption.body.scaling.item2': 'Central governance oversight',
'insights.aiAdoption.body.scaling.item3': 'Documentation and operational playbooks',
'insights.aiAdoption.body.scaling.item4': 'Continuous performance measurement',
'insights.aiAdoption.body.scaling.p3': 'Avoid departmental AI silos. Build a unified ecosystem capable of long-term operational reliability.',

// --- Section 9 ---
'insights.aiAdoption.body.continuous.title': '9. Measure and Continuously Improve',
'insights.aiAdoption.body.continuous.p1': 'AI adoption is not a one-time implementation - it is an evolving capability.',
'insights.aiAdoption.body.continuous.p2': 'Enterprises should monitor:',
'insights.aiAdoption.body.continuous.item1': 'Return on investment',
'insights.aiAdoption.body.continuous.item2': 'Operational efficiency gains',
'insights.aiAdoption.body.continuous.item3': 'Customer satisfaction metrics',
'insights.aiAdoption.body.continuous.item4': 'Model accuracy and stability',
'insights.aiAdoption.body.continuous.item5': 'Compliance and audit indicators',
'insights.aiAdoption.body.continuous.p3': 'Continuous tuning ensures AI systems remain aligned with evolving business objectives.',

// --- Key Takeaways ---
'insights.aiAdoption.body.takeaways.title': 'Key Takeaways',
'insights.aiAdoption.body.takeaways.item1': 'AI adoption must begin with measurable business objectives',
'insights.aiAdoption.body.takeaways.item2': 'Data readiness determines operational reliability',
'insights.aiAdoption.body.takeaways.item3': 'Governance should be embedded from day one',
'insights.aiAdoption.body.takeaways.item4': 'Pilot projects validate enterprise-wide scaling',
'insights.aiAdoption.body.takeaways.item5': 'Continuous measurement ensures sustained ROI',

// --- Conclusion ---
'insights.aiAdoption.body.conclusion.title': 'Conclusion',
'insights.aiAdoption.body.conclusion.p1': 'For mid-sized enterprises, AI adoption represents both a strategic opportunity and an operational imperative.',
'insights.aiAdoption.body.conclusion.p2': 'The organizations that succeed:',
'insights.aiAdoption.body.conclusion.item1': 'Align AI with clear business objectives',
'insights.aiAdoption.body.conclusion.item2': 'Establish strong data foundations',
'insights.aiAdoption.body.conclusion.item3': 'Launch controlled, high-impact pilots',
'insights.aiAdoption.body.conclusion.item4': 'Embed governance and compliance early',
'insights.aiAdoption.body.conclusion.item5': 'Scale through unified architecture',
'insights.aiAdoption.body.conclusion.item6': 'Commit to ongoing optimization',
'insights.aiAdoption.body.conclusion.p3': 'AI is not about following trends. It is about building governed systems that convert enterprise data into dependable, measurable decisions.',
'insights.aiAdoption.body.conclusion.p4': 'Start deliberately. Build strong foundations. Scale with purpose.',

// --- Sidebar ---
'insights.aiAdoption.sidebar.tocTitle': 'In This Article',
'insights.aiAdoption.sidebar.toc.item1': '1. Define Clear Business Objectives',
'insights.aiAdoption.sidebar.toc.item2': '2. Assess Organizational Readiness',
'insights.aiAdoption.sidebar.toc.item3': '3. Build a Strong Data Foundation',
'insights.aiAdoption.sidebar.toc.item4': '4. Launch High-Impact Pilot Projects',
'insights.aiAdoption.sidebar.toc.item5': '5. Embed Governance and Risk Management',
'insights.aiAdoption.sidebar.toc.item6': '6. Develop Talent and an AI-Ready Culture',
'insights.aiAdoption.sidebar.toc.item7': '7. Integrate AI into Core Workflows',
'insights.aiAdoption.sidebar.toc.item8': '8. Scale with Structured Architecture',
'insights.aiAdoption.sidebar.toc.item9': '9. Measure and Continuously Improve',
'insights.aiAdoption.sidebar.toc.item10': '10. Conclusion',

'insights.aiAdoption.sidebar.shareTitle': 'Share This Article',
'insights.aiAdoption.sidebar.share.linkedin': 'Share on LinkedIn',
'insights.aiAdoption.sidebar.share.twitter': 'Share on Twitter',
'insights.aiAdoption.sidebar.share.facebook': 'Share on Facebook',
'insights.aiAdoption.sidebar.share.copy': 'Copy link',
'insights.aiAdoption.sidebar.copyFeedback': 'Link copied!',

// ========================================
// INSIGHTS ARTICLE
// From Data to Decisions
// ========================================

// --- Hero ---
'insights.fromDataToDecisions.hero.image.alt': 'Insurance protection background',
'insights.fromDataToDecisions.hero.category': 'AI Strategy & Enterprise Architecture',
'insights.fromDataToDecisions.hero.date': 'February 24, 2026',
'insights.fromDataToDecisions.hero.title': 'From Data to Decisions: Building an Enterprise-Ready AI Ecosystem',
'insights.fromDataToDecisions.hero.excerpt': 'Enterprise AI in 2026 is not about experimentation. It is about building scalable, governed ecosystems that turn data into reliable business decisions.',

// --- Body Intro ---
'insights.fromDataToDecisions.body.intro.p1': 'It\'s not about trying out the newest tools to build an enterprise-ready AI ecosystem in 2026. It\'s about making a system that can grow, is reliable, and works for everyone in your company while also supporting your business goals. It\'s a big difference between testing out a few AI programs and making AI a part of how your business runs every day.',

// --- Section 1 ---
'insights.fromDataToDecisions.body.enterpriseMeaning.title': '1. What "Enterprise-Ready AI" Really Means',
'insights.fromDataToDecisions.body.enterpriseMeaning.p1': 'Think about how different a prototype car is from a production car. The prototype may look great, but the production car has been put through a lot of tests, built to last, and made to work every day. The production model is AI that is ready for business.',
'insights.fromDataToDecisions.body.enterpriseMeaning.p2': 'It has to:',
'insights.fromDataToDecisions.body.enterpriseMeaning.item1': 'As the number of users and data grows, scale.',
'insights.fromDataToDecisions.body.enterpriseMeaning.item2': 'Work with current systems like CRM, ERP, and supply chain platforms.',
'insights.fromDataToDecisions.body.enterpriseMeaning.item3': 'Be honest, have accurate data, and make decisions that can be explained.',
'insights.fromDataToDecisions.body.enterpriseMeaning.item4': 'Be mindful of your surroundings and how your specific workflows work.',
'insights.fromDataToDecisions.body.enterpriseMeaning.p3': 'Databricks and other companies stress that enterprise AI isn\'t only about doing trials on their own. It needs a unified environment where data moves freely and smart automation is a normal element of business.',

// --- Section 2 ---
'insights.fromDataToDecisions.body.infrastructure.title': '2. Why Infrastructure Is Important',
'insights.fromDataToDecisions.body.infrastructure.p1': 'It\'s easy to plug in an AI tool and think it will work. But infrastructure is what makes the difference between short-term tests and long-term change.',
'insights.fromDataToDecisions.body.infrastructure.p2': 'Without the right foundations:',
'insights.fromDataToDecisions.body.infrastructure.item1': 'Every department makes AI solutions that don\'t work together.',
'insights.fromDataToDecisions.body.infrastructure.item2': 'Data is still spread out over different platforms.',
'insights.fromDataToDecisions.body.infrastructure.item3': 'Automation is blocked by manual processes.',
'insights.fromDataToDecisions.body.infrastructure.item4': 'Scaling gets out of hand.',
'insights.fromDataToDecisions.body.infrastructure.item5': 'The dangers of security and compliance go up.',
'insights.fromDataToDecisions.body.infrastructure.p3': 'Strong infrastructure makes data fusion possible, which means putting together customer, sales, and product data into one base. It also facilitates autonomous decision-making, which means that AI may handle things like regular approvals, routing customers, or optimizing inventories on its own.',
'insights.fromDataToDecisions.body.infrastructure.p4': 'Infrastructure also makes sure that rules are followed and governance is in place in regulated businesses. You won\'t be able to get out of pilot mode if you skip this step.',
'insights.fromDataToDecisions.body.infrastructure.image.alt': 'Why AI Strategy Fails Without Strong IT Foundations',

// --- Section 3 ---
'insights.fromDataToDecisions.body.maturity.title': '3. The Four Levels of AI Maturity',
'insights.fromDataToDecisions.body.maturity.item1': 'Initial Adoption: Limited pilots with minimal operational impact',
'insights.fromDataToDecisions.body.maturity.item2': 'Fragmented Growth: Department-level experimentation',
'insights.fromDataToDecisions.body.maturity.item3': 'Enterprise Integration: Unified platforms and governance',
'insights.fromDataToDecisions.body.maturity.item4': 'Transformational AI: AI embedded in core competitive processes',
'insights.fromDataToDecisions.body.maturity.p1': 'Transformative Enterprise AI means putting AI into key business operations to give you an edge over your competitors.',
'insights.fromDataToDecisions.body.maturity.p2': 'Most businesses today are somewhere between stages two and three. The framework shows you how to grow in a planned way instead of a haphazard way.',

// --- Section 4 ---
'insights.fromDataToDecisions.body.dataReadiness.title': '4. What Makes Data Ready for AI?',
'insights.fromDataToDecisions.body.dataReadiness.p1': 'Not all data can be used by AI. Data that is ready for AI must meet three requirements:',
'insights.fromDataToDecisions.body.dataReadiness.item1': 'Quality: Clean, consistent, and validated data',
'insights.fromDataToDecisions.body.dataReadiness.item2': 'Accessibility: Structured and available to systems and decision-makers',
'insights.fromDataToDecisions.body.dataReadiness.item3': 'Trust: Governed, secure, and privacy-compliant',
'insights.fromDataToDecisions.body.dataReadiness.p2': 'AI models trained on inconsistent or fragmented data will generate unreliable outcomes. Centralized data architectures transform scattered information into structured, decision-grade assets.',
'insights.fromDataToDecisions.body.dataReadiness.p3': 'Poor data inputs create unstable outputs. Strong data foundations enable dependable automation.',

// --- Section 5 ---
'insights.fromDataToDecisions.body.roadmap.title': '5. Designing a Strategic AI Roadmap',
'insights.fromDataToDecisions.body.roadmap.p1': 'Technology alone does not create enterprise AI success. A strategic roadmap must address:',
'insights.fromDataToDecisions.body.roadmap.item1': 'Data architecture modernization',
'insights.fromDataToDecisions.body.roadmap.item2': 'System interoperability',
'insights.fromDataToDecisions.body.roadmap.item3': 'Risk management and governance frameworks',
'insights.fromDataToDecisions.body.roadmap.item4': 'Operational alignment',
'insights.fromDataToDecisions.body.roadmap.item5': 'Talent and capability development',
'insights.fromDataToDecisions.body.roadmap.item6': 'Scalable innovation processes',
'insights.fromDataToDecisions.body.roadmap.p2': 'Successful organizations balance early quick wins with long-term architectural planning. AI deployment must be phased, governed, and aligned with measurable business objectives.',

// --- Section 6 ---
'insights.fromDataToDecisions.body.trends.title': '6. Enterprise AI Trends Shaping 2026',
'insights.fromDataToDecisions.body.trends.p1': 'Several trends are accelerating enterprise AI adoption:',
'insights.fromDataToDecisions.body.trends.item1': 'Cloud modernization and scalable data platforms',
'insights.fromDataToDecisions.body.trends.item2': 'Democratized AI tools for business users',
'insights.fromDataToDecisions.body.trends.item3': 'Multimodal AI systems (text, image, audio, video)',
'insights.fromDataToDecisions.body.trends.item4': 'Integrated data and AI operating models',
'insights.fromDataToDecisions.body.trends.item5': 'Maturity benchmarking frameworks',
'insights.fromDataToDecisions.body.trends.p2': 'Organizations increasingly measure AI progress against governance standards and operational performance benchmarks rather than experimentation volume.',

// --- Section 7 ---
'insights.fromDataToDecisions.body.risks.title': '7. Risks to Manage',
'insights.fromDataToDecisions.body.risks.p1': 'Enterprise AI introduces measurable risk. Common challenges include:',
'insights.fromDataToDecisions.body.risks.item1': 'Model bias caused by poor data quality',
'insights.fromDataToDecisions.body.risks.item2': 'Legacy system integration barriers',
'insights.fromDataToDecisions.body.risks.item3': 'Compliance and governance exposure',
'insights.fromDataToDecisions.body.risks.item4': 'Scaling failures after successful pilots',
'insights.fromDataToDecisions.body.risks.item5': 'AI talent shortages',
'insights.fromDataToDecisions.body.risks.p2': 'Mitigating these risks requires proactive monitoring, explainable AI mechanisms, and structured oversight frameworks.',

// --- Conclusion ---
'insights.fromDataToDecisions.body.conclusion.title': '8. Conclusion',
'insights.fromDataToDecisions.body.conclusion.p1': 'Enterprise-ready AI in 2026 is not optional. It is becoming foundational to operational competitiveness.',
'insights.fromDataToDecisions.body.conclusion.p2': 'The organizations that succeed:',
'insights.fromDataToDecisions.body.conclusion.item1': 'Build on governed, high-quality data foundations',
'insights.fromDataToDecisions.body.conclusion.item2': 'Adopt maturity-driven growth strategies',
'insights.fromDataToDecisions.body.conclusion.item3': 'Align AI initiatives with measurable business objectives',
'insights.fromDataToDecisions.body.conclusion.item4': 'Modernize infrastructure before scaling automation',
'insights.fromDataToDecisions.body.conclusion.item5': 'Foster a culture of continuous improvement',
'insights.fromDataToDecisions.body.conclusion.p3': 'AI is not a separate initiative. It is an interconnected ecosystem embedded within enterprise operations.',
'insights.fromDataToDecisions.body.conclusion.p4': 'Start deliberately. Build strong foundations. Scale with purpose.',
'insights.fromDataToDecisions.body.conclusion.p5': 'The goal is not simply to deploy AI. The goal is to build governed systems that convert data into dependable, enterprise-grade decisions.',

// --- Key Takeaways ---
'insights.fromDataToDecisions.body.takeaways.title': 'Key Takeaways',
'insights.fromDataToDecisions.body.takeaways.item1': 'Enterprise AI requires infrastructure, not experimentation',
'insights.fromDataToDecisions.body.takeaways.item2': 'Data readiness determines decision reliability',
'insights.fromDataToDecisions.body.takeaways.item3': 'Maturity models guide structured AI scaling',
'insights.fromDataToDecisions.body.takeaways.item4': 'Governance and security must be embedded early',
'insights.fromDataToDecisions.body.takeaways.item5': 'AI ecosystems must align with measurable business outcomes',

// --- Sidebar ---
'insights.fromDataToDecisions.sidebar.tocTitle': 'In This Article',
'insights.fromDataToDecisions.sidebar.toc.item1': '1. What "Enterprise-Ready AI"',
'insights.fromDataToDecisions.sidebar.toc.item2': '2. Why Infrastructure',
'insights.fromDataToDecisions.sidebar.toc.item3': '3. Four Levels of AI Maturity',
'insights.fromDataToDecisions.sidebar.toc.item4': '4. What Makes Data Ready for AI?',
'insights.fromDataToDecisions.sidebar.toc.item5': '5. Strategic AI Roadmap',
'insights.fromDataToDecisions.sidebar.toc.item6': '6. AI Trends Shaping 2026',
'insights.fromDataToDecisions.sidebar.toc.item7': '7. Risks to Manage',
'insights.fromDataToDecisions.sidebar.toc.item8': '8. Conclusion',

'insights.fromDataToDecisions.sidebar.shareTitle': 'Share This Article',
'insights.fromDataToDecisions.sidebar.share.linkedin': 'Share on LinkedIn',
'insights.fromDataToDecisions.sidebar.share.twitter': 'Share on Twitter',
'insights.fromDataToDecisions.sidebar.share.facebook': 'Share on Facebook',
'insights.fromDataToDecisions.sidebar.share.copy': 'Copy link',
'insights.fromDataToDecisions.sidebar.copyFeedback': 'Link copied!',


// ========================================
// INSIGHTS ARTICLE
// Why AI Strategy Fails Without Strong IT Foundations
// ========================================

// --- Hero ---
'insights.whyAIStrategyFails.hero.image.alt': 'Insurance protection background',
'insights.whyAIStrategyFails.hero.category': 'AI Strategy & IT Architecture',
'insights.whyAIStrategyFails.hero.date': 'February 23, 2026',
'insights.whyAIStrategyFails.hero.title': 'Why AI Strategy Fails Without Strong IT Foundations',
'insights.whyAIStrategyFails.hero.excerpt': 'AI fails when built on weak IT foundations. Scalable infrastructure and governed data are essential for sustainable results.',

// --- Body Intro ---
'insights.whyAIStrategyFails.body.intro.p1': 'Artificial intelligence is no longer only a test. Businesses in many fields are spending a lot of money on AI projects, from predictive analytics to generative automation. But even with bigger funds and support from executives, many AI projects stop working, don\'t do what they\'re supposed to do, or fail outright.',
'insights.whyAIStrategyFails.body.intro.p2': 'The reason isn\'t bad algorithms.',
'insights.whyAIStrategyFails.body.intro.p3': 'The IT fundamentals are poor.',

// --- Section 1 ---
'insights.whyAIStrategyFails.body.notSimple.title': '1. AI Is Not a Simple Fix',
'insights.whyAIStrategyFails.body.notSimple.p1': 'Companies typically see AI as an add-on to their software, something that can be added to existing systems without making any big changes. AI needs a lot of infrastructure to work. It needs a scalable architecture, clean data pipelines, safe surroundings, and workflows for continuous integration.',
'insights.whyAIStrategyFails.body.notSimple.p2': 'AI becomes unreliable, costly, and hard to scale without current IT foundations.',
'insights.whyAIStrategyFails.body.notSimple.p3': 'Before using advanced models, businesses need to check if their infrastructure can handle AI workloads well.',

// --- Section 2 ---
'insights.whyAIStrategyFails.body.legacy.title': '2. Old systems cause structural problems',
'insights.whyAIStrategyFails.body.legacy.p1': 'Many businesses still use monolithic structures and databases that are broken up. These systems were never meant to do real-time analytics, machine learning processes, or process large amounts of data.',
'insights.whyAIStrategyFails.body.legacy.p2': 'When AI tools are added to old systems, certain problems often happen:',
'insights.whyAIStrategyFails.body.legacy.item1': 'Data silos make it impossible to train a single model.',
'insights.whyAIStrategyFails.body.legacy.item2': 'Slow systems make it hard to get insights.',
'insights.whyAIStrategyFails.body.legacy.item3': 'Automation is blocked by manual processes.',
'insights.whyAIStrategyFails.body.legacy.item4': 'Costs of integration go grow unexpectedly',
'insights.whyAIStrategyFails.body.legacy.p3': 'Cloud-native, API-driven, and scalable systems are necessary for modern AI. AI projects have a hard time moving past the proof-of-concept stage without modernization.',
'insights.whyAIStrategyFails.body.legacy.image.alt': 'Why AI Strategy Fails Without Strong IT Foundations',

// --- Section 3 ---
'insights.whyAIStrategyFails.body.dataQuality.title': '3. The quality of the data affects how well AI works.',
'insights.whyAIStrategyFails.body.dataQuality.p1': 'AI systems can only work as well as the data they use. Poor data governance, inconsistent formats, missing information, and duplicate records can make performance very bad.',
'insights.whyAIStrategyFails.body.dataQuality.p2': 'Businesses often don\'t realize how much work it takes to:',
'insights.whyAIStrategyFails.body.dataQuality.item1': 'Make data sources the same',
'insights.whyAIStrategyFails.body.dataQuality.item2': 'Make sure your data pipelines work.',
'insights.whyAIStrategyFails.body.dataQuality.item3': 'Set up frameworks for data validation',
'insights.whyAIStrategyFails.body.dataQuality.item4': 'Make sure you follow the rules',
'insights.whyAIStrategyFails.body.dataQuality.p3': 'Strong IT foundations create centralized data architectures and governance structures that make AI safe and reliable.',

// --- Section 4 ---
'insights.whyAIStrategyFails.body.scalability.title': '4. Not assuming scalability is a must',
'insights.whyAIStrategyFails.body.scalability.p1': 'Many AI pilots have shown good early performance. But when companies try to use these solutions throughout the whole company, they start to see problems with their infrastructure.',
'insights.whyAIStrategyFails.body.scalability.p2': 'Limitations on computing, storage, and performance problems immediately become clear.',
'insights.whyAIStrategyFails.body.scalability.p3': 'Amazon Web Services, Microsoft Azure, and Google Cloud are examples of cloud-native platforms that allow for elastic scaling. However, this only works if the systems are built to take use of them.',
'insights.whyAIStrategyFails.body.scalability.p4': 'Designing for scale from the start is important for AI to work.',

// --- Section 5 ---
'insights.whyAIStrategyFails.body.security.title': '5. Don\'t forget about security and governance',
'insights.whyAIStrategyFails.body.security.p1': 'AI adds new levels of risk, such as worries about data privacy, bias in models, exposure to regulations, and weak spots in cybersecurity.',
'insights.whyAIStrategyFails.body.security.p2': 'Companies that don\'t have good IT governance risk compliance failures and damage to their reputation.',
'insights.whyAIStrategyFails.body.security.p3': 'A strong infrastructure must have:',
'insights.whyAIStrategyFails.body.security.item1': 'Managing identities and access',
'insights.whyAIStrategyFails.body.security.item2': 'Protocols for encryption',
'insights.whyAIStrategyFails.body.security.item3': 'Audit traces',
'insights.whyAIStrategyFails.body.security.item4': 'Systems for monitoring models',
'insights.whyAIStrategyFails.body.security.p4': 'A planned AI roadmap must work with company security frameworks, not against them.',

// --- Section 6 ---
'insights.whyAIStrategyFails.body.itFirst.title': '6. IT Strategy Comes First in AI Strategy',
'insights.whyAIStrategyFails.body.itFirst.p1': 'Companies who do well with AI use it in diverse ways. First, they put money into:',
'insights.whyAIStrategyFails.body.itFirst.item1': 'Modernizing the cloud',
'insights.whyAIStrategyFails.body.itFirst.item2': 'Automation and DevOps',
'insights.whyAIStrategyFails.body.itFirst.item3': 'Engineering data',
'insights.whyAIStrategyFails.body.itFirst.item4': 'Interoperability of systems',
'insights.whyAIStrategyFails.body.itFirst.p2': 'They see AI as a tool that can be used on top of a robust digital infrastructure, not as a way to speed up innovation.',
'insights.whyAIStrategyFails.body.itFirst.p3': 'We think of AI strategy at Synexum Labs as an extension of IT architecture. Before putting intelligent systems into use, we make sure that businesses have the right structures in place to support them over time.',
'insights.whyAIStrategyFails.body.itFirst.p4': 'AI doesn\'t fail because it doesn\'t want to.',
'insights.whyAIStrategyFails.body.itFirst.p5': 'When the base underneath it isn\'t strong enough to hold it up, it fails.',

// --- Key Takeaways ---
'insights.whyAIStrategyFails.body.takeaways.title': 'Key Takeaways',
'insights.whyAIStrategyFails.body.takeaways.item1': 'AI initiatives fail primarily due to weak IT infrastructure',
'insights.whyAIStrategyFails.body.takeaways.item2': 'Legacy systems limit scalability and integration',
'insights.whyAIStrategyFails.body.takeaways.item3': 'Data governance is critical to AI reliability',
'insights.whyAIStrategyFails.body.takeaways.item4': 'Security and compliance must be embedded from the start',
'insights.whyAIStrategyFails.body.takeaways.item5': 'Modern IT architecture must precede AI deployment',

// --- Conclusion ---
'insights.whyAIStrategyFails.body.conclusion.title': 'Conclusion',
'insights.whyAIStrategyFails.body.conclusion.p1': 'Artificial intelligence is powerful, but it is not self-sustaining. Sustainable AI transformation requires modern infrastructure, governed data environments, and scalable architecture.',
'insights.whyAIStrategyFails.body.conclusion.p2': 'Organizations that prioritize IT modernization before AI deployment position themselves for long-term operational reliability and measurable impact.',
'insights.whyAIStrategyFails.body.conclusion.p3': 'Without strong foundations, even the most advanced AI strategy will struggle to deliver enterprise value.',

// --- Sidebar ---
'insights.whyAIStrategyFails.sidebar.tocTitle': 'In This Article',
'insights.whyAIStrategyFails.sidebar.toc.item1': '1. AI Is Not a Simple Add-On',
'insights.whyAIStrategyFails.sidebar.toc.item2': '2. Legacy System Constraints',
'insights.whyAIStrategyFails.sidebar.toc.item3': '3. Data & Governance',
'insights.whyAIStrategyFails.sidebar.toc.item4': '4. Scalability Requirements',
'insights.whyAIStrategyFails.sidebar.toc.item5': '5. Security & Governance',
'insights.whyAIStrategyFails.sidebar.toc.item6': '6. IT Before AI',
'insights.whyAIStrategyFails.sidebar.toc.item7': '7. Conclusion',

'insights.whyAIStrategyFails.sidebar.shareTitle': 'Share This Article',
'insights.whyAIStrategyFails.sidebar.share.linkedin': 'Share on LinkedIn',
'insights.whyAIStrategyFails.sidebar.share.twitter': 'Share on Twitter',
'insights.whyAIStrategyFails.sidebar.share.facebook': 'Share on Facebook',
'insights.whyAIStrategyFails.sidebar.share.copy': 'Copy link',
'insights.whyAIStrategyFails.sidebar.copyFeedback': 'Link copied!',










    },
    fr: {

        // ========================================
// HOMEPAGE
// ========================================

// --- Hero ---
'home.hero.eyebrow': 'Stratégie qui se concrétise',
'home.hero.title.line1': "Le Système d’Exploitation pour",
'home.hero.title.highlight': 'la Transformation Numérique',
'home.hero.subtitle': "Nous construisons des systèmes gouvernés, évolutifs et durables qui comblent l’écart entre la stratégie et l’exécution. Une infrastructure décisionnelle qui rend votre organisation plus intelligente, plus rapide et plus responsable.",
'home.hero.cta.primary': 'Réserver un Appel Découverte',
'home.hero.cta.secondary': 'Télécharger la Présentation des Capacités',
'home.hero.trust.title': 'Adopté par des organisations institutionnelles',
'home.hero.trust.item1': 'Services Financiers',
'home.hero.trust.item2': 'Santé',
'home.hero.trust.item3': 'Entreprise',
'home.hero.trust.item4': 'Gouvernement',

// --- Client Fit Section ---
'home.clientFit.title': 'Conçu pour les Organisations qui Exigent Plus',
'home.clientFit.subtitle': "Nous travaillons avec des clients institutionnels qui ont besoin de solutions d’IA et d’automatisation fiables, gouvernées et mesurables.",

'home.clientFit.card1.title': 'Opérations Institutionnelles',
'home.clientFit.card1.desc': 'Organisations avec des processus complexes et à forts enjeux nécessitant précision et contrôle.',

'home.clientFit.card2.title': 'Environnements Axés sur la Conformité',
'home.clientFit.card2.desc': 'Équipes opérant sous des exigences réglementaires strictes et des obligations d’audit.',

'home.clientFit.card3.title': 'Flux de Travail Intensifs en Données',
'home.clientFit.card3.desc': 'Opérations générant des volumes importants de données pouvant être exploitées pour l’automatisation.',

'home.clientFit.card4.title': 'Défis de Mise à l’Échelle',
'home.clientFit.card4.desc': 'Organisations en croissance où les processus manuels créent des goulots d’étranglement.',

'home.clientFit.card5.title': 'Résultats Mesurables Requis',
'home.clientFit.card5.desc': 'Dirigeants responsables d’un ROI démontrable et d’améliorations opérationnelles.',

// --- Capabilities Section ---
'home.capabilities.title': 'Notre Modèle de Service Intégré',
'home.capabilities.subtitle': "Construit sur notre architecture Core/Grid + Cellules Modulaires, chaque solution est à la fois évolutive et gouvernée - de l’architecture des systèmes vivants au maintien de niveau institutionnel.",

// Capability 1
'home.capabilities.card1.title': 'Modèle de Livraison Gouverné',
'home.capabilities.card1.problem.label': 'Problème :',
'home.capabilities.card1.problem': 'Équipes fragmentées et lacunes de conformité',
'home.capabilities.card1.solution.label': 'Solution :',
'home.capabilities.card1.solution': 'Cadre de livraison unifié avec responsabilité décisionnelle claire',
'home.capabilities.card1.outcome.label': 'Résultat :',
'home.capabilities.card1.outcome': 'Objectifs stratégiques atteints avec une exécution de niveau institutionnel',

// Capability 2
'home.capabilities.card2.title': 'Architecture de Systèmes Vivants',
'home.capabilities.card2.problem.label': 'Problème :',
'home.capabilities.card2.problem': 'Données, décisions et exécution déconnectées',
'home.capabilities.card2.solution.label': 'Solution :',
'home.capabilities.card2.solution': 'Couche d’intelligence qui observe, apprend et s’adapte',
'home.capabilities.card2.outcome.label': 'Résultat :',
'home.capabilities.card2.outcome': 'Systèmes durables qui accumulent de la valeur au fil du temps',

// Capability 3
'home.capabilities.card3.title': 'Ingénierie de Plateformes Évolutives',
'home.capabilities.card3.problem.label': 'Problème :',
'home.capabilities.card3.problem': 'Déploiement lent et stack technologique fragmenté',
'home.capabilities.card3.solution.label': 'Solution :',
'home.capabilities.card3.solution': 'Développement full-stack, IA/ML, DevOps et services QA',
'home.capabilities.card3.outcome.label': 'Résultat :',
'home.capabilities.card3.outcome': 'Déploiement rapide soutenu à travers les fuseaux horaires avec gouvernance',

// Capability 4
'home.capabilities.card4.title': 'Développement de Cellules Modulaires',
'home.capabilities.card4.problem.label': 'Problème :',
'home.capabilities.card4.problem': 'La mise à l’échelle sacrifie le contrôle et la conformité',
'home.capabilities.card4.solution.label': 'Solution :',
'home.capabilities.card4.solution': 'Unités d’exécution spécifiques par domaine héritant de la gouvernance du Core/Grid',
'home.capabilities.card4.outcome.label': 'Résultat :',
'home.capabilities.card4.outcome': 'Évoluer avec autonomie et rapidité sans sacrifier le contrôle',

// Capability 5
'home.capabilities.card5.title': 'Maintien de Niveau Institutionnel',
'home.capabilities.card5.problem.label': 'Problème :',
'home.capabilities.card5.problem': 'Instabilité et dérive après le lancement',
'home.capabilities.card5.solution.label': 'Solution :',
'home.capabilities.card5.solution': 'Support opérationnel continu et gestion du système',
'home.capabilities.card5.outcome.label': 'Résultat :',
'home.capabilities.card5.outcome': 'Les systèmes restent stables, conformes et continuent d’accumuler de la valeur',

'home.capabilities.cta': 'Voir Toutes les Capacités',

// --- Process Section ---
'home.process.title': 'Comment Nous Travaillons',
'home.process.subtitle': 'Une approche structurée et gouvernée qui offre des résultats prévisibles avec une visibilité opérationnelle complète.',

'home.process.step1.title': 'Découvrir',
'home.process.step1.desc': 'Nous évaluons vos opérations actuelles, contraintes et objectifs. Aucune évaluation générique — analyse spécifique de vos systèmes, données et processus.',
'home.process.step1.tag1': 'Audit opérationnel',
'home.process.step1.tag2': 'Analyse du paysage de données',
'home.process.step1.tag3': 'Priorisation des opportunités',

'home.process.step2.title': 'Concevoir',
'home.process.step2.desc': 'Architecture et conception de solutions alignées avec vos exigences de sécurité, de conformité et d’exploitation. Spécifications claires avant tout développement.',
'home.process.step2.tag1': 'Architecture de solution',
'home.process.step2.tag2': 'Spécifications d’intégration',
'home.process.step2.tag3': 'Cadre de gouvernance',

'home.process.step3.title': 'Construire',
'home.process.step3.desc': 'Développement itératif avec visibilité continue pour les parties prenantes. Aucune boîte noire — vous voyez les progrès et pouvez ajuster à tout moment.',
'home.process.step3.tag1': 'Composants fonctionnels du système',
'home.process.step3.tag2': 'Documentation',
'home.process.step3.tag3': 'Supports de formation',

'home.process.step4.title': 'Exploiter',
'home.process.step4.desc': 'Gestion continue du système, surveillance et optimisation. Nous ne livrons pas simplement pour disparaître — nous assurons une performance durable.',
'home.process.step4.tag1': 'Surveillance du système',
'home.process.step4.tag2': 'Optimisation des performances',
'home.process.step4.tag3': 'Amélioration continue',

'home.process.cta': 'En Savoir Plus sur Notre Processus',

// --- Proof Section ---
'home.proof.title': 'Impact Mesurable',
'home.proof.subtitle': 'Résultats réels issus de mises en œuvre réelles. Nous mesurons le succès par les améliorations opérationnelles, pas par la simple livraison de projet.',

'home.proof.metric1.label': 'Réduction du temps de traitement',
'home.proof.metric1.context': 'Moyenne sur les projets d’automatisation',

'home.proof.metric2.label': 'Taux de précision',
'home.proof.metric2.context': 'Comparé à une base manuelle de 94 %',

'home.proof.metric3.label': 'Amélioration du débit',
'home.proof.metric3.context': 'Sans effectif supplémentaire',

'home.proof.metric4.label': 'Délai typique de ROI',
'home.proof.metric4.context': 'Temps jusqu’au retour positif',

// --- Case Studies ---
'home.caseStudies.card1.tag': 'Automatisation des Processus',
'home.caseStudies.card1.title': 'Remplacer le Travail Administratif par l’Automatisation',
'home.caseStudies.card1.desc': 'Une configuration réelle de Go High Level montrant comment l’automatisation a remplacé la coordination manuelle et la charge administrative - sans recruter de personnel supplémentaire.',
'home.caseStudies.card1.metric1': '60 % + tâches administratives automatisées',
'home.caseStudies.card1.metric2': '↓45 % coordination manuelle',
'home.caseStudies.card1.metric3': '↑35 % vitesse opérationnelle',
'home.caseStudies.card1.metric4': '0 nouveaux recrutements administratifs',

'home.caseStudies.card2.tag': 'Design UI / UX',
'home.caseStudies.card2.title': 'Refonte UX pour Augmenter l’Engagement',
'home.caseStudies.card2.desc': 'Transformation de visiteurs passifs en utilisateurs actifs grâce à des améliorations UX basées sur le comportement - augmentation de l’engagement sans dépenses supplémentaires en trafic.',
'home.caseStudies.card2.metric1': '↓42 % taux de rebond',
'home.caseStudies.card2.metric2': '↑65 % durée de session',
'home.caseStudies.card2.metric3': '↑78 % interactions CTA',
'home.caseStudies.card2.metric4': '4–5 actions par visite',

'home.caseStudies.card3.tag': 'Services Financiers',
'home.caseStudies.card3.title': 'Rapports de Conformité Automatisés',
'home.caseStudies.card3.desc': 'Transformation d’un processus manuel hebdomadaire de 40 heures en un système automatisé en temps réel avec pistes d’audit intégrées.',
'home.caseStudies.card3.metric1': '92 % réduction du temps',
'home.caseStudies.card3.metric2': 'Zéro lacune de conformité',
'home.caseStudies.card3.metric3': 'Visibilité en temps réel',

'home.caseStudies.cta': 'Voir Toutes les Études de Cas',

// --- Final CTA ---
'home.finalCta.title': 'Intéressé à Travailler Ensemble ?',
'home.finalCta.desc': 'Renseignez vos informations et notre équipe vous contactera rapidement pour poursuivre la conversation. Nous explorerons ensuite comment nos solutions pourraient s’aligner avec les besoins et priorités de votre organisation.',
'home.finalCta.emailLabel': 'Vous préférez le courriel ?',
'home.finalCta.emailText': 'Contactez-nous à support@synexumlabs.com',
'home.finalCta.formTitle': 'Commencer la Conversation',
'home.finalCta.note': 'Nous répondons sous un jour ouvrable',





        //Header
        'nav.capabilities': 'Capacités',
        'nav.caseStudies': 'Études de cas',
        'nav.howWeWork': 'Notre approche',
        'nav.insights': 'Perspectives',
        'nav.about': 'À propos',

        'nav.capabilities.governed': 'Modèle de livraison gouverné',
        'nav.capabilities.governed.desc': 'Gouvernance unifiée de la livraison',

        'nav.capabilities.living': 'Architecture système évolutive',
        'nav.capabilities.living.desc': 'Intelligence connectée et adaptative',

        'nav.capabilities.scalable': 'Ingénierie de plateformes évolutives',
        'nav.capabilities.scalable.desc': 'Plateformes IA full-stack',

        'nav.capabilities.modular': 'Développement modulaire autonome',
        'nav.capabilities.modular.desc': 'Unités autonomes et gouvernées',

        'nav.capabilities.viewAll': 'Voir toutes les capacités →',

        'nav.cta.discovery': 'Réserver un appel découverte',

        'nav.capabilities.mobile': 'CAPACITÉS',

        'nav.language': 'Langue',

        // SYNEXUM ABOUT PAGE (FR)

        'about.hero.title': 'Le pont entre stratégie et exécution',
        'about.hero.desc': 'Synexum Labs est née d’un constat partagé : les organisations échouent dans leur transformation numérique non pas par manque de stratégie, mais par incapacité à exécuter à travers des équipes fragmentées, des systèmes disparates et des environnements réglementaires complexes. Le problème est structurel — l’écart entre la vision stratégique et la réalité opérationnelle.',

        'about.story.title': 'Notre histoire',

        'about.story.p1': 'Nous avons reconnu que cet écart existe parce que le marché manque d’une approche unifiée. Les organisations ont besoin à la fois de clarté stratégique et de gouvernance institutionnelle d’un côté, combinées à la capacité d’exécution, à la rapidité et à la scalabilité de l’autre. Aucune de ces dimensions ne suffit seule. Il faut un pont : un modèle opérationnel unifié qui rend la stratégie exécutable et l’exécution gouvernée.',

        'about.story.p2': 'Synexum Labs est ce pont. Nous sommes le modèle opérationnel unifié où l’orientation stratégique devient un système exécutable et où la puissance d’ingénierie devient un moteur de livraison contrôlé et de niveau institutionnel.',

        'about.story.p3': 'Synexum Labs est ce pont — où la direction stratégique devient un système exécutable et où la puissance d’ingénierie devient un moteur de livraison contrôlé et institutionnel. Notre concept fondamental est que la transformation numérique n’est pas un logiciel — c’est une infrastructure décisionnelle.',

        'about.story.p4': 'Nous construisons des « systèmes vivants » capables d’observer, de décider, de déclencher des actions et d’apprendre des résultats, tout en restant gouvernés. C’est le fondement de notre approche : une clarté stratégique unifiée avec une exécution évolutive grâce au système opérationnel Synexum.',

        'about.mission.title': 'Notre mission',

        'about.mission.p1': 'Nous résolvons le paradoxe de la croissance : augmenter la capacité d’exécution sans perdre la gouvernance, la responsabilité ou la cohérence institutionnelle. Notre modèle opérationnel unifié permet aux organisations de concevoir, déployer et maintenir des systèmes numériques complexes avec crédibilité institutionnelle et rapidité.',

        'about.mission.p2': 'En collaboration avec Coigne Capital, nous offrons un pont fluide — de la vision stratégique de Coigne à la livraison technique robuste de Synexum. Ce partenariat garantit que les clients prospèrent à la fois structurellement et numériquement.',

        'about.values.precision.title': 'Précision',
        'about.values.precision.desc': 'Nous mesurons le succès par les résultats, pas par l’activité.',

        'about.values.transparency.title': 'Transparence',
        'about.values.transparency.desc': 'Aucune boîte noire. Vous avez une visibilité complète sur nos processus et nos systèmes.',

        'about.values.governance.title': 'La gouvernance avant tout',
        'about.values.governance.desc': 'La sécurité, la conformité et le contrôle sont fondamentaux — jamais des ajouts tardifs.',

        'about.leadership.title': 'Équipe de direction',
        'about.leadership.subtitle': 'Des dirigeants expérimentés ayant construit et dirigé des organisations technologiques à grande échelle dans des environnements réglementés.',

        'about.standards.title': 'Nos standards',
        'about.standards.desc': 'Nous opérons selon des standards institutionnels parce que nos clients l’exigent — et parce que c’est la bonne manière de construire des systèmes durables.',

        'about.coigne.title': 'Membre du portefeuille Coigne Capital',
        'about.coigne.link': 'En savoir plus sur Coigne Capital',

        'about.cta.title': 'Discutons de vos opérations',
        'about.cta.desc': 'Planifiez un appel découverte pour explorer comment Synexum Labs peut transformer vos opérations grâce à l’automatisation intelligente.',
        'about.cta.button': 'Réserver un appel découverte',

        // SYNEXUM CAPABILITIES PAGE (FR)

// --- Hero ---
'cap.hero.title': 'Construisez et gérez votre système opérationnel institutionnel',
'cap.hero.desc': 'Notre suite intégrée de services repose sur notre architecture Core/Grid + Cellules modulaires, garantissant que chaque solution soit à la fois évolutive et gouvernée.',

// --- Governed Delivery Model ---
'cap.governed.title': 'Modèle de livraison gouverné',
'cap.governed.desc': 'Nous mettons en œuvre et gérons un cadre de livraison unifié qui garantit que vos objectifs stratégiques soient atteints avec une exécution de niveau institutionnel. Cela inclut une responsabilité décisionnelle claire, la gestion de la conformité transfrontalière et l’intégration d’outils fragmentés dans un système cohérent.',

'cap.governed.highlight1': 'Responsabilité décisionnelle',
'cap.governed.highlight2': 'Conformité transfrontalière',
'cap.governed.highlight3': 'Intégration des outils',
'cap.governed.highlight4': 'Cadres de gouvernance',

// --- Living Systems Architecture ---
'cap.living.title': 'Architecture de systèmes évolutifs',
'cap.living.desc': 'Nous concevons et construisons la couche d’intelligence qui relie vos données, vos décisions et votre exécution. Pas seulement des applications — mais des systèmes durables qui observent, apprennent et s’adaptent à votre environnement opérationnel.',

'cap.living.highlight1': 'Observer & décider',
'cap.living.highlight2': 'Déclencher & apprendre',
'cap.living.highlight3': 'Intégration IA',
'cap.living.highlight4': 'Contrôles de gouvernance',

// --- Scalable Platform Engineering ---
'cap.scalable.title': 'Ingénierie de plateformes évolutives',
'cap.scalable.desc': 'Développement full-stack, intégration IA/ML, DevOps et assurance qualité. Notre capacité d’exécution mondiale garantit un déploiement rapide et une livraison continue dans le respect de notre cadre de gouvernance.',

'cap.scalable.highlight1': 'Développement full-stack',
'cap.scalable.highlight2': 'Intégration IA/ML',
'cap.scalable.highlight3': 'DevOps & QA',
'cap.scalable.highlight4': 'Capacité mondiale',

// --- Modular Cell Development ---
'cap.modular.title': 'Développement de cellules modulaires',
'cap.modular.desc': 'Unités d’exécution spécialisées ("Cellules") pour la finance, les opérations, l’analytique et plus encore. Chaque cellule fonctionne avec autonomie et rapidité tout en héritant de la gouvernance du Core/Grid.',

'cap.modular.highlight1': 'Architecture Core/Grid',
'cap.modular.highlight2': 'Cellules métiers',
'cap.modular.highlight3': 'Héritage de gouvernance',
'cap.modular.highlight4': 'Contrôle évolutif',

// --- Institutional-Grade Sustainment ---
'cap.sustain.title': 'Maintien de niveau institutionnel',
'cap.sustain.desc': 'Notre engagement ne s’arrête pas au lancement. Nous fournissons un support opérationnel continu afin que vos systèmes restent stables, conformes et continuent à générer de la valeur dans le temps.',

'cap.sustain.highlight1': 'Surveillance 24/7',
'cap.sustain.highlight2': 'Maintenance proactive',
'cap.sustain.highlight3': 'Maintien de la conformité',
'cap.sustain.highlight4': 'Amélioration continue',

// --- CTA ---
'cap.cta.title': 'Prêt à transformer vos opérations ?',
'cap.cta.desc': 'Discutons de la manière dont nos capacités s’alignent avec vos objectifs. Nous vous aiderons à identifier les opportunités à plus fort impact.',
'cap.cta.primary': 'Réserver un appel découverte',
'cap.cta.secondary': 'Voir les études de cas',

// SYNEXUM CONTACT PAGE (FR)

// --- Hero ---
'contact.hero.title': 'Entamons la conversation',
'contact.hero.desc': 'Planifiez un appel découverte pour discuter des besoins de votre organisation et explorer comment nous pouvons soutenir votre transformation numérique.',

// --- Booking Column ---
'contact.booking.title': 'Réserver un appel découverte',
'contact.booking.intro': 'Un appel vidéo de 30 minutes pour comprendre vos enjeux et explorer comment l\'automatisation intelligente peut générer des améliorations mesurables.',

'contact.booking.detail1.title': '30 minutes',
'contact.booking.detail1.desc': 'Session découverte ciblée',

'contact.booking.detail2.title': 'Conférence vidéo',
'contact.booking.detail2.desc': 'Google Meet ou Zoom',

'contact.booking.detail3.title': 'Planification flexible',
'contact.booking.detail3.desc': 'Choisissez l\'horaire qui vous convient',

'contact.booking.button': 'Planifier votre appel découverte',
'contact.booking.note': 'Aucun argumentaire commercial — une discussion structurée sur vos opérations',

// --- What to Expect ---
'contact.expect.title': 'À quoi s\'attendre',
'contact.expect.item1': 'Discussion sur vos défis actuels et vos objectifs opérationnels',
'contact.expect.item2': 'Exploration des opportunités en IA et automatisation',
'contact.expect.item3': 'Définition des prochaines étapes recommandées',

// --- Contact Info ---
'contact.info.title': 'Nous contacter',
'contact.info.intro': 'Vous préférez nous joindre directement ? Nous sommes là pour vous aider.',

'contact.info.email': 'Envoyez-nous un courriel',
'contact.info.phone': 'Appelez-nous',
'contact.info.address.title': 'Adresse du bureau',

'contact.response': 'Nous répondons généralement sous un jour ouvrable',

// --- Coigne ---
'contact.coigne.title': 'Membre du portefeuille Coigne Capital',
'contact.coigne.link': 'En savoir plus sur Coigne Capital',

// --- Case Studies Hero ---
'casestudies.hero.title': 'Études de Cas',
'casestudies.hero.desc': 'Des résultats concrets issus de mises en œuvre réelles. Découvrez comment nous avons aidé des organisations institutionnelles à transformer leurs opérations avec des résultats mesurables.',

// --- Featured Section ---
'casestudies.featured.title': 'Projets à la Une',

'casestudies.featured.project1.title': 'Refonte UX pour Augmenter l’Engagement',
'casestudies.featured.project1.client': 'Entreprise de Plateforme Digitale',
'casestudies.featured.project1.summary': 'Transformation des visiteurs passifs en utilisateurs actifs grâce à des améliorations UX stratégiques sans augmenter le budget trafic.',
'casestudies.featured.project1.metric1.value': '↓42%',
'casestudies.featured.project1.metric1.label': 'Taux de Rebond',
'casestudies.featured.project1.metric2.value': '↑65%',
'casestudies.featured.project1.metric2.label': 'Durée de Session',
'casestudies.featured.project1.metric3.value': '↑78%',
'casestudies.featured.project1.metric3.label': 'Clics sur CTA',

'casestudies.featured.project2.title': 'Rapports de Conformité Automatisés',
'casestudies.featured.project2.client': 'Société Régionale de Services Financiers',
'casestudies.featured.project2.summary': 'Transformation d’un processus manuel de 40 heures par semaine en un système automatisé en temps réel avec pistes d’audit intégrées.',
'casestudies.featured.project2.metric1.value': '92%',
'casestudies.featured.project2.metric1.label': 'Réduction du Temps',
'casestudies.featured.project2.metric2.value': '99.8%',
'casestudies.featured.project2.metric2.label': 'Précision',
'casestudies.featured.project2.metric3.value': '4 mois',
'casestudies.featured.project2.metric3.label': 'Délai de ROI',

// --- All Case Studies Section ---
'casestudies.all.title': 'Toutes les Études de Cas',

'casestudies.all.study1.industry': 'Services Locaux',
'casestudies.all.study1.title': 'Automatisation du Suivi des Leads pour une Entreprise de Plomberie',
'casestudies.all.study1.client': 'Entreprise Régionale de Services de Plomberie',
'casestudies.all.study1.metric.value': '80%',
'casestudies.all.study1.metric.label': 'Temps de Réponse Plus Rapide',

'casestudies.all.study2.industry': 'Santé',
'casestudies.all.study2.title': 'Automatisation du Build & Déploiement pour une Suite de Payeur Santé',
'casestudies.all.study2.client': 'Plateforme Cloud de Payeur Santé',
'casestudies.all.study2.metric.value': '55%↑',
'casestudies.all.study2.metric.label': 'Vitesse de Publication',

'casestudies.all.study3.industry': 'Plateforme Digitale',
'casestudies.all.study3.title': 'Comment Nous Livrons des Plateformes Web Haute Performance',
'casestudies.all.study3.client': 'Entreprise de Services Digitaux à Fort Trafic',
'casestudies.all.study3.metric.value': '50%',
'casestudies.all.study3.metric.label': 'Chargement Plus Rapide',

'casestudies.all.study4.industry': 'Automatisation des Processus',
'casestudies.all.study4.title': 'Remplacement des Tâches Administratives par l’Automatisation',
'casestudies.all.study4.client': 'Entreprise de Services Digitaux',
'casestudies.all.study4.metric.value': '60%+',
'casestudies.all.study4.metric.label': 'Tâches Administratives Automatisées',

'casestudies.all.study5.industry': 'Plateforme Digitale',
'casestudies.all.study5.title': 'Refonte UX pour Augmenter l’Engagement',
'casestudies.all.study5.client': 'Entreprise de Plateforme Digitale',
'casestudies.all.study5.metric.value': '↑78%',
'casestudies.all.study5.metric.label': 'Clics sur CTA',

'casestudies.all.study6.industry': 'Services Financiers',
'casestudies.all.study6.title': 'Rapports de Conformité Automatisés',
'casestudies.all.study6.client': 'Société Régionale de Services Financiers',
'casestudies.all.study6.metric.value': '92%',
'casestudies.all.study6.metric.label': 'Réduction du Temps',

// --- CTA Section ---
'casestudies.cta.title': 'Prêt à Obtenir des Résultats Similaires ?',
'casestudies.cta.desc': 'Chaque organisation est différente. Discutons de vos défis spécifiques et voyons comment nous pouvons générer des améliorations mesurables.',
'casestudies.cta.button': 'Planifier un Appel Découverte',

// --- Footer Brand ---
'footer.tagline': 'Transformations Digitales • Logiciels • IA • Automatisation',
'footer.taglineSmall': 'Synexum Labs est une sous-marque de Coigne Capital Inc.',
'footer.newsletter.title': 'S’abonner aux Analyses',

// --- Footer Columns ---
'footer.capabilities.title': 'Capacités',
'footer.capabilities.link1': 'Modèle de Livraison Gouverné',
'footer.capabilities.link2': 'Architecture de Système Vivant',
'footer.capabilities.link3': 'Ingénierie de Plateforme Évolutive',
'footer.capabilities.link4': 'Développement Modulaire par Cellules',
'footer.capabilities.link5': 'Maintien de Niveau Institutionnel',

'footer.company.title': 'Entreprise',
'footer.company.link1': 'À Propos',
'footer.company.link2': 'Études de Cas',
'footer.company.link3': 'Analyses',
'footer.company.link4': 'Contact',

'footer.resources.title': 'Ressources',
'footer.resources.link1': 'Présentation des Capacités',

// --- Footer Bottom ---
'footer.copyright': '© Coigne Capital Inc. — Synexum Labs',
'footer.legal.privacy': 'Politique de Confidentialité',
'footer.legal.terms': 'Conditions d’Utilisation',
'footer.legal.disclaimer': 'Avertissement Légal',
'footer.legal.coigne': 'Une entreprise de Coigne Capital',


// --- Hero ---
'hww.hero.title': 'Comment Nous Travaillons',
'hww.hero.description': 'Une approche structurée et gouvernée qui offre des résultats prévisibles avec une visibilité opérationnelle complète. Aucune surprise, aucune boîte noire — uniquement des résultats mesurables.',

// --- Principles ---
'hww.principles.title': 'Nos Principes Directeurs',
'hww.principles.description': 'Chaque mission est guidée par ces principes fondamentaux afin de garantir des résultats durables pour les organisations institutionnelles.',

'hww.principle1.title': 'La Gouvernance Avant Tout',
'hww.principle1.desc': 'La sécurité, la conformité et les exigences d’audit sont intégrées dès le premier jour — jamais ajoutées après coup.',

'hww.principle2.title': 'Transparence Totale',
'hww.principle2.desc': 'Vous bénéficiez d’une visibilité complète sur l’avancement, les décisions et les livrables. Aucune boîte noire, aucune surprise.',

'hww.principle3.title': 'Alignement des Parties Prenantes',
'hww.principle3.desc': 'Nous collaborons avec vos équipes, jamais en contournement. Le transfert de connaissances et le renforcement des capacités font partie intégrante de chaque projet.',

'hww.principle4.title': 'Résultats Mesurables',
'hww.principle4.desc': 'Chaque initiative est liée à des objectifs métier précis et mesurables. Les indicateurs de succès sont définis dès le départ et suivis en continu.',

// --- Framework ---
'hww.framework.title': 'Notre Cadre de Livraison',
'hww.framework.description': 'Une méthodologie éprouvée en quatre phases garantissant une livraison réussie tout en maintenant gouvernance et contrôle.',

// Step 1
'hww.step1.title': 'Découvrir',
'hww.step1.timeline': 'Semaines 1-2',
'hww.step1.desc': 'Analyse approfondie de vos opérations, contraintes et objectifs afin d’identifier les opportunités à plus fort impact.',
'hww.step1.deliverables.title': 'Livrables',
'hww.step1.outcomes.title': 'Résultats',
'hww.step1.deliverable1': 'Audit des opérations',
'hww.step1.deliverable2': 'Analyse du paysage des données',
'hww.step1.deliverable3': 'Priorisation des opportunités',
'hww.step1.deliverable4': 'Entretiens avec les parties prenantes',
'hww.step1.outcome1': 'Compréhension claire de la situation actuelle',
'hww.step1.outcome2': 'Feuille de route priorisée',
'hww.step1.outcome3': 'Cartographie des risques et dépendances',

// Step 2
'hww.step2.title': 'Concevoir',
'hww.step2.timeline': 'Semaines 3-4',
'hww.step2.desc': 'Conception d’architecture alignée avec vos exigences de sécurité et conformité.',
'hww.step2.deliverables.title': 'Livrables',
'hww.step2.outcomes.title': 'Résultats',
'hww.step2.deliverable1': 'Architecture de solution',
'hww.step2.deliverable2': 'Spécifications d’intégration',
'hww.step2.deliverable3': 'Cadre de gouvernance',
'hww.step2.deliverable4': 'Revue de sécurité',
'hww.step2.outcome1': 'Conception technique validée',
'hww.step2.outcome2': 'Portée et jalons définis',
'hww.step2.outcome3': 'Plan d’atténuation des risques',

// Step 3
'hww.step3.title': 'Construire',
'hww.step3.timeline': 'Semaines 5-10',
'hww.step3.desc': 'Développement itératif avec visibilité continue et validation intégrée.',
'hww.step3.deliverables.title': 'Livrables',
'hww.step3.outcomes.title': 'Résultats',
'hww.step3.deliverable1': 'Composants fonctionnels',
'hww.step3.deliverable2': 'Documentation',
'hww.step3.deliverable3': 'Supports de formation',
'hww.step3.deliverable4': 'Résultats des tests',
'hww.step3.outcome1': 'Système prêt au déploiement',
'hww.step3.outcome2': 'Équipe formée',
'hww.step3.outcome3': 'Documentation complète',

// Step 4
'hww.step4.title': 'Exploiter',
'hww.step4.timeline': 'En Continu',
'hww.step4.desc': 'Gestion continue, surveillance et optimisation des performances.',
'hww.step4.deliverables.title': 'Livrables',
'hww.step4.outcomes.title': 'Résultats',
'hww.step4.deliverable1': 'Surveillance du système',
'hww.step4.deliverable2': 'Optimisation des performances',
'hww.step4.deliverable3': 'Amélioration continue',
'hww.step4.deliverable4': 'Rapports réguliers',
'hww.step4.outcome1': 'Performance fiable',
'hww.step4.outcome2': 'Résultats métier mesurables',
'hww.step4.outcome3': 'Capacités évolutives',

// --- CTA ---
'hww.cta.title': 'Prêt à Commencer ?',
'hww.cta.description': 'Discutons de vos objectifs et voyons comment notre méthodologie peut générer des résultats mesurables.',
'hww.cta.primary': 'Réserver un Appel Découverte',
'hww.cta.secondary': 'Voir les Études de Cas',

// PAGE: caseStudy.uxRedesignIncreaseEngagement
// LANGUAGE: fr

// --- Hero ---
'caseStudy.uxRedesignIncreaseEngagement.hero.imageAlt': 'Contexte de protection d’assurance',
'caseStudy.uxRedesignIncreaseEngagement.hero.tag1': 'Conception UI/UX',
'caseStudy.uxRedesignIncreaseEngagement.hero.tag2': 'Données & Analytique',
'caseStudy.uxRedesignIncreaseEngagement.hero.tag3': 'Entreprise de plateforme numérique',
'caseStudy.uxRedesignIncreaseEngagement.hero.title': 'Refonte UX pour augmenter l’engagement',
'caseStudy.uxRedesignIncreaseEngagement.hero.subtitle': 'Transformation de visiteurs passifs en utilisateurs actifs grâce à des améliorations UX stratégiques, en transformant les navigateurs en utilisateurs engagés sans dépenses supplémentaires en acquisition de trafic.',

// --- Metrics Bar ---
'caseStudy.uxRedesignIncreaseEngagement.metrics.item1.value': '42%↓',
'caseStudy.uxRedesignIncreaseEngagement.metrics.item1.label': 'Taux de rebond',
'caseStudy.uxRedesignIncreaseEngagement.metrics.item2.value': '65%↑',
'caseStudy.uxRedesignIncreaseEngagement.metrics.item2.label': 'Durée de session',
'caseStudy.uxRedesignIncreaseEngagement.metrics.item3.value': '78%↑',
'caseStudy.uxRedesignIncreaseEngagement.metrics.item3.label': 'Interactions CTA',
'caseStudy.uxRedesignIncreaseEngagement.metrics.item4.value': '4–5',
'caseStudy.uxRedesignIncreaseEngagement.metrics.item4.label': 'Actions utilisateur par visite',

// --- Context ---
'caseStudy.uxRedesignIncreaseEngagement.context.sectionLabel': 'Le Contexte',
'caseStudy.uxRedesignIncreaseEngagement.context.heading': 'Le trafic était fort. L’engagement ne l’était pas.',
'caseStudy.uxRedesignIncreaseEngagement.context.paragraph1': 'La plateforme attirait un flux constant de visiteurs via la recherche, les campagnes payantes et les recommandations. La notoriété n’était pas le problème — l’engagement l’était.',
'caseStudy.uxRedesignIncreaseEngagement.context.paragraph2': 'Les utilisateurs arrivaient mais repartaient rapidement. Les sessions étaient courtes, l’interaction était minimale et très peu de visiteurs s’inscrivaient, exploraient les outils ou convertissaient. L’entreprise ne manquait pas de trafic — elle peinait à transformer les visiteurs en utilisateurs actifs.',

// --- Challenge ---
'caseStudy.uxRedesignIncreaseEngagement.challenge.sectionLabel': 'Le Défi',
'caseStudy.uxRedesignIncreaseEngagement.challenge.heading': 'Taux d’abandon élevé et faible interaction',
'caseStudy.uxRedesignIncreaseEngagement.challenge.intro': 'Malgré une acquisition solide, le comportement des utilisateurs a révélé plusieurs barrières UX empêchant un engagement plus profond :',
'caseStudy.uxRedesignIncreaseEngagement.challenge.item1.title': 'Sorties immédiates :',
'caseStudy.uxRedesignIncreaseEngagement.challenge.item1.description': 'De nombreux utilisateurs quittaient les pages clés en quelques secondes sans interagir.',
'caseStudy.uxRedesignIncreaseEngagement.challenge.item2.title': 'Faible profondeur de défilement :',
'caseStudy.uxRedesignIncreaseEngagement.challenge.item2.description': 'Le contenu important et les fonctionnalités étaient rarement consultés.',
'caseStudy.uxRedesignIncreaseEngagement.challenge.item3.title': 'Parcours confus :',
'caseStudy.uxRedesignIncreaseEngagement.challenge.item3.description': 'La navigation et la structure du contenu rendaient peu clair ce qu’il fallait faire ensuite.',
'caseStudy.uxRedesignIncreaseEngagement.challenge.item4.title': 'Hiérarchie visuelle faible :',
'caseStudy.uxRedesignIncreaseEngagement.challenge.item4.description': 'Les actions clés ne ressortaient pas, entraînant l’inaction.',
'caseStudy.uxRedesignIncreaseEngagement.challenge.item5.title': 'CTA peu clairs :',
'caseStudy.uxRedesignIncreaseEngagement.challenge.item5.description': 'Les appels à l’action étaient soit absents, soit mal positionnés.',

// --- Approach ---
'caseStudy.uxRedesignIncreaseEngagement.approach.sectionLabel': 'Notre Approche',
'caseStudy.uxRedesignIncreaseEngagement.approach.heading': 'Refonte UX guidée par le comportement',

'caseStudy.uxRedesignIncreaseEngagement.approach.phase1.number': '1',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase1.title': 'Analyse du comportement utilisateur',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase1.duration': 'Semaines 1–2',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase1.description': 'Analyse des heatmaps, du suivi de défilement et des parcours utilisateurs pour identifier les points de friction, les zones d’abandon et les signaux d’intention peu clairs.',

'caseStudy.uxRedesignIncreaseEngagement.approach.phase2.number': '2',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase2.title': 'Navigation & architecture de l’information',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase2.duration': 'Semaines 3–4',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase2.description': 'Simplification de la navigation, regroupement des fonctionnalités connexes et clarification des parcours principaux et secondaires afin que les utilisateurs sachent toujours quoi faire ensuite.',

'caseStudy.uxRedesignIncreaseEngagement.approach.phase3.number': '3',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase3.title': 'Hiérarchie visuelle & optimisation des CTA',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase3.duration': 'Semaines 5–7',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase3.description': 'Utilisation du contraste, de l’espacement et de la priorisation de la mise en page pour mettre en avant les actions clés et réduire la charge cognitive.',

'caseStudy.uxRedesignIncreaseEngagement.approach.phase4.number': '4',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase4.title': 'Micro-interactions & feedback',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase4.duration': 'Semaines 8–10',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase4.description': 'Introduction d’états au survol, d’indicateurs de progression et de retours réactifs pour rendre l’expérience dynamique et humaine.',

'caseStudy.uxRedesignIncreaseEngagement.approach.phase5.number': '5',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase5.title': 'Tests & mesure',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase5.duration': 'Semaines 11–12',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase5.description': 'Suivi continu des métriques d’engagement et optimisation des parcours grâce à une itération guidée par les données.',

// --- Results ---
'caseStudy.uxRedesignIncreaseEngagement.results.sectionLabel': 'Les Résultats',
'caseStudy.uxRedesignIncreaseEngagement.results.heading': 'Du simple parcours à un engagement actif',

'caseStudy.uxRedesignIncreaseEngagement.results.card1.before': 'Élevé',
'caseStudy.uxRedesignIncreaseEngagement.results.card1.arrow': '→',
'caseStudy.uxRedesignIncreaseEngagement.results.card1.after': '↓42%',
'caseStudy.uxRedesignIncreaseEngagement.results.card1.label': 'Taux de rebond significativement réduit',

'caseStudy.uxRedesignIncreaseEngagement.results.card2.before': 'Faible',
'caseStudy.uxRedesignIncreaseEngagement.results.card2.arrow': '→',
'caseStudy.uxRedesignIncreaseEngagement.results.card2.after': '↑65%',
'caseStudy.uxRedesignIncreaseEngagement.results.card2.label': 'Durée de session augmentée',

'caseStudy.uxRedesignIncreaseEngagement.results.card3.before': 'Minimal',
'caseStudy.uxRedesignIncreaseEngagement.results.card3.arrow': '→',
'caseStudy.uxRedesignIncreaseEngagement.results.card3.after': '↑78%',
'caseStudy.uxRedesignIncreaseEngagement.results.card3.label': 'Forte hausse des interactions CTA',

'caseStudy.uxRedesignIncreaseEngagement.results.card4.before': '1–2',
'caseStudy.uxRedesignIncreaseEngagement.results.card4.arrow': '→',
'caseStudy.uxRedesignIncreaseEngagement.results.card4.after': '4–5',
'caseStudy.uxRedesignIncreaseEngagement.results.card4.label': 'Les actions utilisateur par visite ont doublé',

// --- Testimonial ---
'caseStudy.uxRedesignIncreaseEngagement.testimonial.quote': 'Nos utilisateurs explorent désormais, interagissent et complètent des actions au lieu de quitter après quelques secondes. La refonte a complètement transformé la façon dont les gens interagissent avec notre plateforme.',
'caseStudy.uxRedesignIncreaseEngagement.testimonial.authorName': 'Responsable Produit',
'caseStudy.uxRedesignIncreaseEngagement.testimonial.authorTitle': 'Entreprise de plateforme numérique',

// --- CTA ---
'caseStudy.uxRedesignIncreaseEngagement.cta.heading': 'Vous voulez augmenter l’engagement sans plus de trafic ?',
'caseStudy.uxRedesignIncreaseEngagement.cta.description': 'Nous aidons les plateformes numériques à transformer des visiteurs passifs en utilisateurs actifs grâce à un design UX basé sur la recherche.',
'caseStudy.uxRedesignIncreaseEngagement.cta.primaryButton': 'Planifier une consultation',
'caseStudy.uxRedesignIncreaseEngagement.cta.secondaryButton': 'Voir plus d’études de cas',

// ========================================
// Capabilities — Governed Delivery Model
// ========================================

// --- Hero ---
'capabilities.gdm.hero.title': 'Modèle de Livraison Gouverné',
'capabilities.gdm.hero.description': 'Un cadre de livraison unifié garantissant que vos objectifs stratégiques sont atteints avec une exécution de niveau institutionnel.',

// --- Overview ---
'capabilities.gdm.overview.title': 'Vue d’ensemble',
'capabilities.gdm.overview.description': 'Nous mettons en place et gérons un cadre de livraison unifié qui comble l’écart entre la vision stratégique et la réalité opérationnelle. Cela inclut la définition claire des responsabilités décisionnelles, la gestion de la conformité transfrontalière et l’intégration d’outils fragmentés dans un système cohérent. Notre modèle de livraison gouverné garantit que chaque initiative conserve une crédibilité institutionnelle tout en avançant à la vitesse exigée par votre organisation.',

// --- What We Deliver ---
'capabilities.gdm.deliverables.title': 'Ce Que Nous Livrons',

'capabilities.gdm.deliverables.decision.title': 'Cadre de Responsabilité Décisionnelle',
'capabilities.gdm.deliverables.decision.desc': 'Structures claires définissant la responsabilité des décisions, avec des mécanismes d’escalade et des points de contrôle de gouvernance.',

'capabilities.gdm.deliverables.compliance.title': 'Gestion de la Conformité Transfrontalière',
'capabilities.gdm.deliverables.compliance.desc': 'Cadres pour gérer les exigences réglementaires dans plusieurs juridictions tout en maintenant la rapidité d’exécution.',

'capabilities.gdm.deliverables.tooling.title': 'Intégration et Consolidation des Outils',
'capabilities.gdm.deliverables.tooling.desc': 'Intégration d’outils fragmentés dans un écosystème cohérent et gouverné améliorant la visibilité et le contrôle.',

'capabilities.gdm.deliverables.playbooks.title': 'Manuels d’Exécution',
'capabilities.gdm.deliverables.playbooks.desc': 'Processus standardisés garantissant une livraison cohérente et de haute qualité sur l’ensemble des initiatives.',

'capabilities.gdm.deliverables.dashboard.title': 'Tableau de Bord de Gouvernance',
'capabilities.gdm.deliverables.dashboard.desc': 'Visibilité en temps réel sur l’état de livraison, les indicateurs de conformité et les pistes d’audit décisionnelles.',

'capabilities.gdm.deliverables.risk.title': 'Protocoles de Gestion des Risques',
'capabilities.gdm.deliverables.risk.desc': 'Identification proactive et atténuation des risques avec des procédures d’escalade clairement définies.',

// --- Integrations ---
'capabilities.gdm.integrations.title': 'Intégrations Typiques',
'capabilities.gdm.integrations.intro': 'Nous travaillons avec votre stack technologique existante et nous intégrons de manière fluide aux plateformes standards du secteur.',

// --- Example Deliverables ---
'capabilities.gdm.examples.title': 'Exemples de Livrables',
'capabilities.gdm.examples.item1': 'Documentation du cadre de gouvernance de livraison',
'capabilities.gdm.examples.item2': 'Matrice des droits décisionnels et diagrammes RACI',
'capabilities.gdm.examples.item3': 'Tableaux de bord de suivi et de reporting de conformité',
'capabilities.gdm.examples.item4': 'Spécifications d’architecture des outils intégrés',
'capabilities.gdm.examples.item5': 'Protocoles de communication des parties prenantes',
'capabilities.gdm.examples.item6': 'Points de contrôle qualité et workflows d’approbation',


// ========================================
// PAGE INSIGHTS
// ========================================

'insights.hero.title': 'Analyses',
'insights.hero.description': 'Perspectives sur l’IA, l’automatisation et l’excellence opérationnelle pour les organisations institutionnelles. Des cadres pratiques, sans battage médiatique.',

'insights.featured.badge': 'À la Une',
'insights.featured.category': 'Design UI/UX',
'insights.featured.title': 'Techniques de Design UI/UX Centré Utilisateur pour Augmenter l’Engagement et la Rétention',
'insights.featured.excerpt': 'Les produits numériques performants ne se contentent pas de bien fonctionner — ils créent clarté, confiance et connexion émotionnelle.',
'insights.featured.date': '2 Février 2026',

'insights.latest.title': 'Articles Récents',

'insights.article1.category': 'Architecture Web & SEO',
'insights.article1.title': 'Le Lien Entre Architecture Web, SEO et Croissance Digitale',
'insights.article1.excerpt': 'L’architecture web constitue la base technique du SEO et de la croissance numérique durable.',
'insights.article1.date': '06 Février 2026',

'insights.article2.category': 'Services IT & Conseil',
'insights.article2.title': 'Comment Évaluer et Choisir le Bon Partenaire de Développement Web',
'insights.article2.excerpt': 'Choisir le bon partenaire de développement web est une décision stratégique.',
'insights.article2.date': '05 Février 2026',

'insights.article3.category': 'Services IT & Conseil',
'insights.article3.title': 'Concevoir des Pipelines CI/CD pour des Équipes à Haute Vélocité',
'insights.article3.excerpt': 'Les équipes performantes s’appuient sur des pipelines CI/CD modernes.',
'insights.article3.date': '04 Février 2026',

'insights.article4.category': 'Services IT & Conseil',
'insights.article4.title': 'Fondations IT Modernes : Prérequis pour une IA Évolutive',
'insights.article4.excerpt': 'L’IA évolutive nécessite des fondations IT modernes et gouvernées.',
'insights.article4.date': '03 Février 2026',

'insights.article5.category': 'Design UI/UX',
'insights.article5.title': 'Techniques UI/UX Centré Utilisateur',
'insights.article5.excerpt': 'Les produits performants créent clarté et engagement durable.',
'insights.article5.date': '02 Février 2026',

'insights.article6.category': 'Stratégie IA',
'insights.article6.title': 'Préparation à l’IA pour les Opérations Institutionnelles',
'insights.article6.excerpt': 'La réussite de l’IA dépend des fondations organisationnelles.',
'insights.article6.date': '15 Janvier 2026',



// ========================================
// ÉTUDE DE CAS
// Automatisation de l’Administration de Fonds
// ========================================

'casestudies.fundAdministration.hero.tag1': 'Automatisation des Processus',
'casestudies.fundAdministration.hero.tag2': 'Intégration de Systèmes',
'casestudies.fundAdministration.hero.industry': 'Gestionnaire d’Actifs Alternatifs',
'casestudies.fundAdministration.hero.title': 'Automatisation de l’Administration de Fonds pour un Gestionnaire de 12 Md$',
'casestudies.fundAdministration.hero.subtitle': 'Réduction du temps de clôture trimestrielle de 60% et élimination des erreurs manuelles.',

'casestudies.fundAdministration.context.label': 'Contexte',
'casestudies.fundAdministration.challenge.label': 'Défi',
'casestudies.fundAdministration.approach.label': 'Notre Approche',
'casestudies.fundAdministration.results.label': 'Résultats',

'casestudies.fundAdministration.cta.title': 'Vous Faites Face à des Défis Similaires ?',
'casestudies.fundAdministration.cta.primary': 'Planifier une Consultation',
'casestudies.fundAdministration.cta.secondary': 'Voir Plus d’Études de Cas',


// ========================================
// CASE STUDY PAGE
// ========================================
// Automating Fund Administration
// ========================================

// --- Hero ---
'caseStudy.fundAdmin.meta.tag1': 'Automatisation des Processus',
'caseStudy.fundAdmin.meta.tag2': 'Intégration de Systèmes',
'caseStudy.fundAdmin.meta.tag3': 'Gestionnaire d’Actifs Alternatifs',
'caseStudy.fundAdmin.title': "Automatisation de l’Administration des Fonds pour un Gestionnaire d’Actifs Alternatifs de 12 Md$",
'caseStudy.fundAdmin.subtitle': "Comment nous avons réduit le temps de clôture trimestrielle de 60 % et éliminé les erreurs de rapprochement manuel grâce à l’automatisation intelligente des flux de travail.",

// --- Metrics Bar ---
'caseStudy.fundAdmin.metrics.item1.value': '60%',
'caseStudy.fundAdmin.metrics.item1.label': 'Réduction du Temps de Clôture',
'caseStudy.fundAdmin.metrics.item2.value': '100%',
'caseStudy.fundAdmin.metrics.item2.label': 'Élimination des Erreurs',
'caseStudy.fundAdmin.metrics.item3.value': '1,2 M$',
'caseStudy.fundAdmin.metrics.item3.label': 'Économies Annuelles',
'caseStudy.fundAdmin.metrics.item4.value': '14 Semaines',
'caseStudy.fundAdmin.metrics.item4.label': 'Délai de Mise en Valeur',

// --- Context ---
'caseStudy.fundAdmin.context.label': 'Le Contexte',
'caseStudy.fundAdmin.context.title': 'Un Fonds en Croissance avec des Difficultés Croissantes',
'caseStudy.fundAdmin.context.p1': "Un gestionnaire d’actifs alternatifs mid-market avec 12 Md$ d’actifs sous gestion connaissait une pression opérationnelle importante. Ses processus d’administration de fonds — construits sur des feuilles de calcul et des flux de travail manuels sur une décennie — ne pouvaient plus suivre son rythme de croissance.",
'caseStudy.fundAdmin.context.p2': "Avec des plans pour lancer trois nouveaux véhicules de fonds dans les 18 mois, la direction a reconnu que faire évoluer les processus existants nécessiterait une augmentation proportionnelle des effectifs et introduirait des niveaux de risque inacceptables.",

// --- Challenge ---
'caseStudy.fundAdmin.challenge.label': 'Le Défi',
'caseStudy.fundAdmin.challenge.title': 'Processus Manuels à l’Échelle Institutionnelle',
'caseStudy.fundAdmin.challenge.intro': "L’équipe d’administration des fonds faisait face à plusieurs défis interconnectés qui s’intensifiaient chaque trimestre :",

'caseStudy.fundAdmin.challenge.item1': "Fragmentation des données : Les données investisseurs étaient réparties sur 7 systèmes différents sans source unique de vérité, entraînant des rapprochements complexes.",
'caseStudy.fundAdmin.challenge.item2': "Appels de capitaux manuels : Chaque appel de capitaux nécessitait plus de 40 heures de préparation manuelle des données, de validation et de distribution.",
'caseStudy.fundAdmin.challenge.item3': "Reporting sujet aux erreurs : Les relevés trimestriels aux investisseurs comptaient en moyenne 3 à 5 erreurs par cycle, nuisant aux relations avec les LP et nécessitant des corrections importantes.",
'caseStudy.fundAdmin.challenge.item4': "Exposition à l’audit : L’absence de documentation des processus et de pistes d’audit créait un risque de conformité et prolongeait les cycles d’audit de 30 %.",

// --- Approach ---
'caseStudy.fundAdmin.approach.label': 'Notre Approche',
'caseStudy.fundAdmin.approach.title': 'Automatisation par Phases avec Gouvernance Intégrée',
'caseStudy.fundAdmin.approach.intro': "Nous avons conçu une mission de 14 semaines structurée autour de gains rapides et de changements durables — et non d’une transformation pluriannuelle qui perdrait son élan.",

// Phase 1
'caseStudy.fundAdmin.phase1.title': 'Découverte & Cartographie des Processus',
'caseStudy.fundAdmin.phase1.duration': 'Semaines 1-2',
'caseStudy.fundAdmin.phase1.desc': "Analyse approfondie des flux de travail existants, du paysage système et des points de douleur. Nous avons interrogé 12 parties prenantes et documenté 47 étapes de processus distinctes à travers le cycle de vie de l’administration des fonds.",
'caseStudy.fundAdmin.phase1.deliverables.title': 'Livrables',
'caseStudy.fundAdmin.phase1.deliverables.item1': 'Cartographies des processus actuels',
'caseStudy.fundAdmin.phase1.deliverables.item2': 'Audit d’intégration des systèmes',
'caseStudy.fundAdmin.phase1.deliverables.item3': 'Matrice des opportunités d’automatisation',
'caseStudy.fundAdmin.phase1.deliverables.item4': 'Évaluation des risques',

// Phase 2
'caseStudy.fundAdmin.phase2.title': 'Architecture & Intégration des Données',
'caseStudy.fundAdmin.phase2.duration': 'Semaines 3-6',
'caseStudy.fundAdmin.phase2.desc': "Mise en place d’une couche de données unifiée reliant les 7 systèmes sources. Implémentation d’une synchronisation en temps réel avec résolution des conflits et établissement d’une source unique de vérité dont l’équipe avait urgemment besoin.",
'caseStudy.fundAdmin.phase2.deliverables.title': 'Livrables',
'caseStudy.fundAdmin.phase2.deliverables.item1': 'Architecture d’intégration',
'caseStudy.fundAdmin.phase2.deliverables.item2': 'Règles de validation des données',
'caseStudy.fundAdmin.phase2.deliverables.item3': 'Tableau de bord de surveillance de synchronisation',
'caseStudy.fundAdmin.phase2.deliverables.item4': 'Procédures de retour arrière',

// Phase 3
'caseStudy.fundAdmin.phase3.title': 'Automatisation des Flux de Travail',
'caseStudy.fundAdmin.phase3.duration': 'Semaines 7-11',
'caseStudy.fundAdmin.phase3.desc': "Déploiement d’une automatisation intelligente pour les appels de capitaux, distributions et reporting investisseurs. Intégration de points de contrôle humains pour les décisions à forte valeur tout en automatisant les validations de routine.",
'caseStudy.fundAdmin.phase3.deliverables.title': 'Livrables',
'caseStudy.fundAdmin.phase3.deliverables.item1': 'Moteur automatisé d’appels de capitaux',
'caseStudy.fundAdmin.phase3.deliverables.item2': 'Calculateur de distributions',
'caseStudy.fundAdmin.phase3.deliverables.item3': 'Générateur de relevés',
'caseStudy.fundAdmin.phase3.deliverables.item4': 'Flux de gestion des exceptions',

// Phase 4
'caseStudy.fundAdmin.phase4.title': 'Gouvernance & Transmission',
'caseStudy.fundAdmin.phase4.duration': 'Semaines 12-14',
'caseStudy.fundAdmin.phase4.desc': "Établissement de guides opérationnels, formation des équipes internes et mise en place de tableaux de bord de supervision. Garantie que le client puisse maintenir et étendre la solution de manière autonome.",
'caseStudy.fundAdmin.phase4.deliverables.title': 'Livrables',
'caseStudy.fundAdmin.phase4.deliverables.item1': 'Guide opérationnel',
'caseStudy.fundAdmin.phase4.deliverables.item2': 'Sessions de formation des équipes',
'caseStudy.fundAdmin.phase4.deliverables.item3': 'Tableaux de bord KPI',
'caseStudy.fundAdmin.phase4.deliverables.item4': 'Procédures d’escalade',

// --- Results ---
'caseStudy.fundAdmin.results.label': 'Les Résultats',
'caseStudy.fundAdmin.results.title': 'Impact Mesurable, Valeur Durable',

'caseStudy.fundAdmin.results.item1.before': '12 jours',
'caseStudy.fundAdmin.results.item1.after': '5 jours',
'caseStudy.fundAdmin.results.item1.label': 'Temps de clôture trimestrielle réduit de 60 %',

'caseStudy.fundAdmin.results.item2.before': '3-5 erreurs',
'caseStudy.fundAdmin.results.item2.after': '0 erreur',
'caseStudy.fundAdmin.results.item2.label': 'Aucune erreur de relevé pendant 4 trimestres consécutifs',

'caseStudy.fundAdmin.results.item3.before': '40+ heures',
'caseStudy.fundAdmin.results.item3.after': '4 heures',
'caseStudy.fundAdmin.results.item3.label': 'Temps de préparation des appels de capitaux réduit de 90 %',

'caseStudy.fundAdmin.results.item4.before': '6 ETP',
'caseStudy.fundAdmin.results.item4.after': '2 ETP',
'caseStudy.fundAdmin.results.item4.label': 'Équipe recentrée sur les relations stratégiques avec les investisseurs',

// --- Testimonial ---
'caseStudy.fundAdmin.testimonial.quote': "Synexum n’a pas seulement automatisé nos processus — ils nous ont aidés à repenser la manière dont l’administration des fonds devrait fonctionner. L’équipe libérée se concentre désormais sur les relations LP au lieu du rapprochement de feuilles de calcul.",
'caseStudy.fundAdmin.testimonial.authorName': 'Directeur des Opérations',
'caseStudy.fundAdmin.testimonial.authorTitle': 'Gestionnaire d’Actifs Alternatifs',

// --- CTA ---
'caseStudy.fundAdmin.cta.title': 'Faites-vous Face à des Défis Similaires ?',
'caseStudy.fundAdmin.cta.desc': "Discutons de la manière dont l’automatisation intelligente peut transformer vos flux opérationnels et permettre à votre équipe de se concentrer sur ce qui compte le plus.",
'caseStudy.fundAdmin.cta.primary': 'Planifier une Consultation',
'caseStudy.fundAdmin.cta.secondary': 'Voir Plus d’Études de Cas',

// ========================================
// INSIGHTS ARTICLE
// AI Readiness
// ========================================

// --- Hero ---
'insights.aiReadiness.hero.category': 'Stratégie IA',
'insights.aiReadiness.hero.date': '15 Janvier 2026',
'insights.aiReadiness.hero.title': 'Préparation à l’IA pour les Opérations Institutionnelles : Un Cadre Pratique',
'insights.aiReadiness.hero.excerpt': 'La plupart des initiatives IA échouent non pas à cause de limites technologiques, mais parce que les organisations manquent des éléments fondamentaux nécessaires à une adoption réussie. Voici comment évaluer et construire une véritable préparation à l’IA.',

// --- Body Intro ---
'insights.aiReadiness.body.intro.p1': 'Le cycle d’engouement autour de l’IA a atteint son pic, mais le véritable travail ne fait que commencer. Après des années d’expérimentation, les organisations institutionnelles passent des preuves de concept à la production — et découvrent que la technologie est rarement le principal obstacle. Les organisations qui réussissent avec l’IA ont un point commun : elles ont investi dans la préparation avant de se précipiter vers l’implémentation.',

// --- Section: Why Initiatives Fail ---
'insights.aiReadiness.body.fail.title': 'Pourquoi la Plupart des Initiatives IA Échouent',
'insights.aiReadiness.body.fail.p1': 'Selon des recherches récentes du secteur, environ 85 % des projets IA n’atteignent jamais la production. Les raisons sont remarquablement constantes, quels que soient le secteur ou la taille de l’organisation :',
'insights.aiReadiness.body.fail.item1.title': 'Problèmes de qualité des données :',
'insights.aiReadiness.body.fail.item1.desc': 'Les systèmes d’IA ne valent que par la qualité des données sur lesquelles ils sont entraînés. Des données fragmentées, incohérentes ou incomplètes produisent des modèles peu fiables pour des décisions critiques.',
'insights.aiReadiness.body.fail.item2.title': 'Responsabilité floue :',
'insights.aiReadiness.body.fail.item2.desc': 'Lorsque les initiatives IA se situent entre l’IT et les unités métiers, des zones grises de responsabilité apparaissent. Les projets stagnent en attendant des décisions que personne ne se sent habilité à prendre.',
'insights.aiReadiness.body.fail.item3.title': 'Complexité d’intégration :',
'insights.aiReadiness.body.fail.item3.desc': 'Des outils IA isolés qui ne s’intègrent pas aux workflows existants créent des frictions. Les utilisateurs reviennent aux processus familiers au lieu d’adopter les nouveaux.',
'insights.aiReadiness.body.fail.item4.title': 'Lacunes en gouvernance :',
'insights.aiReadiness.body.fail.item4.desc': 'Sans politiques claires d’utilisation de l’IA, les organisations s’exposent à des risques de conformité et à des résultats incohérents entre équipes.',

// --- Quote ---
'insights.aiReadiness.body.quote': 'Les organisations qui réussissent avec l’IA la considèrent comme une capacité opérationnelle, pas comme un simple projet technologique. Elles construisent d’abord les fondations, puis étendent ce qui fonctionne.',

// --- Section: Four Pillars ---
'insights.aiReadiness.body.pillars.title': 'Les Quatre Piliers de la Préparation à l’IA',
'insights.aiReadiness.body.pillars.p1': 'La véritable préparation à l’IA n’est pas une simple liste de contrôle — c’est une capacité continue qui évolue avec votre organisation. Nous avons développé un cadre basé sur notre travail avec des dizaines de clients institutionnels, centré sur quatre piliers interconnectés :',

// --- Pillar 1 ---
'insights.aiReadiness.body.data.title': '1. Fondation des Données',
'insights.aiReadiness.body.data.p1': 'Avant toute initiative IA, les organisations doivent comprendre clairement leur paysage de données. Il ne s’agit pas seulement de savoir quelles données existent, mais d’en connaître la qualité, l’accessibilité et la gouvernance. Questions clés :',
'insights.aiReadiness.body.data.q1': 'Où résident les données opérationnelles critiques et qui en est responsable ?',
'insights.aiReadiness.body.data.q2': 'Quels problèmes de qualité des données existent et quelle est leur importance ?',
'insights.aiReadiness.body.data.q3': 'Les données sont-elles accessibles de manière programmatique ou nécessitent-elles une extraction manuelle ?',
'insights.aiReadiness.body.data.q4': 'Quelles contraintes de confidentialité et de conformité s’appliquent aux différents ensembles de données ?',

// --- Callout ---
'insights.aiReadiness.body.callout.title': 'Évaluation Rapide : Fondation des Données',
'insights.aiReadiness.body.callout.item1': 'Pouvez-vous produire un inventaire complet des sources de données opérationnelles en 24 heures ?',
'insights.aiReadiness.body.callout.item2': 'Disposez-vous de métriques documentées de qualité des données pour les systèmes critiques ?',
'insights.aiReadiness.body.callout.item3': 'Existe-t-il un responsable unique de la gouvernance des données à l’échelle de l’entreprise ?',

// --- Pillar 2 ---
'insights.aiReadiness.body.process.title': '2. Clarté des Processus',
'insights.aiReadiness.body.process.p1': 'L’IA complète les workflows humains — elle ne les remplace pas intégralement. Les organisations ont besoin de processus documentés et standardisés avant de pouvoir les automatiser ou les améliorer efficacement. Sans clarté des processus, les implémentations IA créent des variations supplémentaires au lieu d’améliorations cohérentes.',
'insights.aiReadiness.body.process.p2': 'Les initiatives IA les plus réussies ciblent des processus qui sont :',
'insights.aiReadiness.body.process.item1': 'Bien documentés avec des entrées et sorties claires',
'insights.aiReadiness.body.process.item2': 'Exécutés suffisamment fréquemment pour générer des données d’entraînement',
'insights.aiReadiness.body.process.item3': 'Assez précieux pour justifier un investissement en automatisation',
'insights.aiReadiness.body.process.item4': 'Suffisamment stables pour éviter un réentraînement constant du modèle',

// --- Pillar 3 ---
'insights.aiReadiness.body.alignment.title': '3. Alignement Organisationnel',
'insights.aiReadiness.body.alignment.p1': 'Les initiatives IA confinées aux silos IT réussissent rarement. Une adoption durable de l’IA exige un alignement entre technologie, opérations, risques et direction métier. Cela implique :',
'insights.aiReadiness.body.alignment.item1.title': 'Parrainage exécutif :',
'insights.aiReadiness.body.alignment.item1.desc': 'Un dirigeant senior responsable des résultats IA, et pas seulement des activités',
'insights.aiReadiness.body.alignment.item2.title': 'Gouvernance transverse :',
'insights.aiReadiness.body.alignment.item2.desc': 'Des structures décisionnelles intégrant toutes les parties prenantes',
'insights.aiReadiness.body.alignment.item3.title': 'Développement des compétences :',
'insights.aiReadiness.body.alignment.item3.desc': 'Des programmes de formation développant la culture IA dans toute l’organisation',
'insights.aiReadiness.body.alignment.item4.title': 'Gestion du changement :',
'insights.aiReadiness.body.alignment.item4.desc': 'Une communication proactive sur l’impact de l’IA sur les rôles et les workflows',

// --- Pillar 4 ---
'insights.aiReadiness.body.infrastructure.title': '4. Infrastructure Technique',
'insights.aiReadiness.body.infrastructure.p1': 'Enfin, les organisations ont besoin d’une base technique solide pour développer, déployer et superviser les systèmes IA. Il ne s’agit pas d’acheter les derniers outils, mais de disposer d’une infrastructure permettant l’expérimentation, l’intégration et la gouvernance.',

// --- Key Takeaways ---
'insights.aiReadiness.body.takeaways.title': 'Points Clés',
'insights.aiReadiness.body.takeaways.item1': '85 % des projets IA échouent — généralement à cause de lacunes fondamentales, pas de limites technologiques',
'insights.aiReadiness.body.takeaways.item2': 'La préparation à l’IA exige un investissement dans les données, les processus, l’organisation et l’infrastructure',
'insights.aiReadiness.body.takeaways.item3': 'Commencez par une évaluation honnête des capacités actuelles avant de sélectionner des cas d’usage IA',
'insights.aiReadiness.body.takeaways.item4': 'Considérez l’IA comme une capacité opérationnelle évolutive, et non comme un projet ponctuel',

// --- Getting Started ---
'insights.aiReadiness.body.gettingStarted.title': 'Par Où Commencer : L’Évaluation de Préparation',
'insights.aiReadiness.body.gettingStarted.p1': 'Pour les organisations qui débutent leur parcours IA — ou qui souhaitent repartir après des initiatives échouées — nous recommandons de commencer par une évaluation structurée de préparation. Il ne s’agit pas de se comparer à un benchmark arbitraire, mais d’identifier les lacunes spécifiques qui compromettront vos initiatives IA si elles ne sont pas traitées.',
'insights.aiReadiness.body.gettingStarted.p2': 'Une évaluation complète prend généralement 2 à 3 semaines et aboutit à une feuille de route priorisée pour renforcer la préparation à l’IA. Le résultat n’est pas une recommandation technologique — c’est une vision honnête des capacités organisationnelles et un plan d’action concret.',
'insights.aiReadiness.body.gettingStarted.p3': 'Les organisations qui investissent dans la préparation avant de se précipiter vers l’implémentation obtiennent systématiquement de meilleurs résultats : un délai de création de valeur plus court, des taux d’adoption plus élevés et des performances durables qui s’améliorent avec le temps.',

// --- Sidebar ---
'insights.aiReadiness.sidebar.tocTitle': 'Dans Cet Article',
'insights.aiReadiness.sidebar.shareTitle': 'Partager Cet Article',
'insights.aiReadiness.sidebar.copyFeedback': 'Lien copié !',
'insights.aiReadiness.sidebar.share.linkedin': 'Partager sur LinkedIn',
'insights.aiReadiness.sidebar.share.twitter': 'Partager sur Twitter',
'insights.aiReadiness.sidebar.share.facebook': 'Partager sur Facebook',
'insights.aiReadiness.sidebar.share.copy': 'Copier le lien',


// ========================================
// LEGAL PAGE
// Privacy Policy
// ========================================

// --- Header ---
'legal.privacy.hero.title': 'Politique de Confidentialité',
'legal.privacy.hero.lastUpdated': 'Dernière mise à jour : 28 Janvier 2026',

// --- Effective Entity ---
'legal.privacy.entity.title': 'Entité Responsable',
'legal.privacy.entity.description': 'La présente Politique de Confidentialité s’applique à Synexum Labs, exploité par Coigne Capital Inc.',
'legal.privacy.entity.companyName': 'Coigne Capital Inc.',
'legal.privacy.entity.address': '555 Bd Dr.-Frederik-Philips, Saint-Laurent, Québec, Canada',
'legal.privacy.entity.emailLabel': 'Courriel :',
'legal.privacy.entity.email': 'support@synexumlabs.com',
'legal.privacy.entity.phoneLabel': 'Téléphone :',
'legal.privacy.entity.phone': '+1 (514) 351-5101',

// --- Information We Collect ---
'legal.privacy.collection.title': 'Informations Que Nous Collectons',
'legal.privacy.collection.item1': 'Informations de contact (nom, courriel, téléphone)',
'legal.privacy.collection.item2': 'Informations de planification et de réservation',
'legal.privacy.collection.item3': 'Abonnements à l’infolettre',
'legal.privacy.collection.item4': 'Analytique web et témoins (cookies)',
'legal.privacy.collection.item5': 'Données d’entreprise des clients durant la prestation de services (y compris code, identifiants et accès aux systèmes, lorsque requis)',

// --- Purpose of Collection ---
'legal.privacy.purpose.title': 'Finalité de la Collecte',
'legal.privacy.purpose.intro': 'Les informations sont collectées afin de :',
'legal.privacy.purpose.item1': 'Répondre aux demandes',
'legal.privacy.purpose.item2': 'Fournir les services contractuels',
'legal.privacy.purpose.item3': 'Transmettre des mises à jour de projet et communications',
'legal.privacy.purpose.item4': 'Améliorer les services et la fonctionnalité du site web',
'legal.privacy.purpose.item5': 'Respecter les obligations légales et contractuelles',

// --- Data Storage & Transfers ---
'legal.privacy.storage.title': 'Stockage et Transferts des Données',
'legal.privacy.storage.p1': 'Les données peuvent être stockées et traitées au Canada et aux États-Unis, notamment sur l’infrastructure Amazon Web Services (AWS).',
'legal.privacy.storage.p2': 'Les renseignements personnels peuvent être transférés à l’extérieur du Canada. Des mesures de protection appropriées sont mises en place conformément aux lois applicables en matière de protection de la vie privée.',

// --- Data Retention ---
'legal.privacy.retention.title': 'Conservation des Données',
'legal.privacy.retention.p1': 'Les données personnelles et d’entreprise sont conservées uniquement pour la durée nécessaire afin de satisfaire aux exigences contractuelles, légales ou opérationnelles.',

// --- Your Rights ---
'legal.privacy.rights.title': 'Vos Droits',
'legal.privacy.rights.intro': 'Vous pouvez demander :',
'legal.privacy.rights.item1': 'L’accès à vos renseignements personnels',
'legal.privacy.rights.item2': 'La correction ou la suppression de vos données',
'legal.privacy.rights.item3': 'Le retrait de votre consentement',
'legal.privacy.rights.item4': 'Le retrait des communications marketing',
'legal.privacy.rights.contactText': 'Les demandes peuvent être soumises à :',
'legal.privacy.rights.email': 'support@synexumlabs.com',

// --- Privacy Officer ---
'legal.privacy.officer.title': 'Responsable de la Protection des Renseignements Personnels',
'legal.privacy.officer.intro': 'Les demandes et questions relatives à la protection des renseignements personnels doivent être adressées à :',
'legal.privacy.officer.name': 'Responsable de la Protection des Renseignements Personnels – Coigne Capital Inc.',
'legal.privacy.officer.emailLabel': 'Courriel :',
'legal.privacy.officer.email': 'support@synexumlabs.com',

// --- Electronic Communications ---
'legal.privacy.communications.title': 'Communications Électroniques',
'legal.privacy.communications.p1': 'Synexum Labs et Coigne Capital Inc. peuvent envoyer des communications électroniques incluant des messages marketing, des infolettres et des mises à jour de projet.',
'legal.privacy.communications.p2': 'Toutes les communications respectent la Loi canadienne anti-pourriel (LCAP/CASL) ainsi que les réglementations américaines applicables. Chaque message inclut l’identification de l’expéditeur et un mécanisme de désabonnement.',
'legal.privacy.communications.p3': 'Vous pouvez retirer votre consentement en tout temps en utilisant le lien de désabonnement ou en nous contactant directement.',


// ========================================
// LEGAL PAGE
// Terms of Service
// ========================================

// --- Header ---
'legal.terms.hero.title': 'Conditions d’Utilisation',
'legal.terms.hero.lastUpdated': 'Dernière mise à jour : 28 Janvier 2026',

// --- Governing Entity ---
'legal.terms.entity.title': 'Entité Responsable',
'legal.terms.entity.p1': 'Tous les services fournis sous la marque Synexum Labs sont offerts par Coigne Capital Inc., constituée au Québec, Canada.',

// --- Scope of Services ---
'legal.terms.scope.title': 'Portée des Services',
'legal.terms.scope.intro': 'Les services incluent, sans s’y limiter :',
'legal.terms.scope.item1': 'Développement logiciel sur mesure',
'legal.terms.scope.item2': 'Applications web et cloud',
'legal.terms.scope.item3': 'Systèmes d’automatisation et de workflows',
'legal.terms.scope.item4': 'Intégration d’intelligence artificielle',
'legal.terms.scope.item5': 'Analytique de données et tableaux de bord',
'legal.terms.scope.item6': 'Infrastructure et support DevOps',
'legal.terms.scope.item7': 'Services-conseils numériques et techniques',

// --- No Guarantees ---
'legal.terms.noGuarantees.title': 'Absence de Garantie',
'legal.terms.noGuarantees.p1': 'Synexum Labs ne garantit aucun résultat, temps de disponibilité, performance, disponibilité des systèmes ou résultats commerciaux. Les accords de niveau de service (SLA), lorsqu’applicables, sont fournis exclusivement par contrat écrit.',

// --- Hosting & Infrastructure ---
'legal.terms.infrastructure.title': 'Hébergement et Infrastructure',
'legal.terms.infrastructure.p1': 'Les travaux de développement peuvent être hébergés temporairement sur une infrastructure située aux États-Unis durant les phases de développement ou réalisés directement dans les environnements fournis par le client, conformément aux ententes contractuelles.',

// --- Intellectual Property ---
'legal.terms.ip.title': 'Propriété Intellectuelle',
'legal.terms.ip.p1': 'La propriété des livrables, du code et de la propriété intellectuelle est régie exclusivement par l’entente écrite applicable. En l’absence d’une entente écrite, toute propriété intellectuelle demeure la propriété de Coigne Capital Inc.',

// --- Limitation of Liability ---
'legal.terms.liability.title': 'Limitation de Responsabilité',
'legal.terms.liability.p1': 'Dans toute la mesure permise par la loi, Coigne Capital Inc. et ses affiliés ne pourront être tenus responsables des dommages indirects, accessoires, consécutifs, spéciaux ou punitifs.',

// --- Dispute Resolution ---
'legal.terms.dispute.title': 'Règlement des Différends',
'legal.terms.dispute.p1': 'Tout différend sera d’abord soumis à une médiation de bonne foi, puis à un arbitrage exécutoire. La loi applicable sera celle de la province de Québec et les lois fédérales du Canada applicables, sauf entente écrite contraire.',

// --- Contact Information ---
'legal.terms.contact.title': 'Coordonnées',
'legal.terms.contact.intro': 'Si vous avez des questions concernant ces Conditions d’Utilisation, veuillez nous contacter :',
'legal.terms.contact.company': 'Coigne Capital Inc.',
'legal.terms.contact.address': '555 Bd Dr.-Frederik-Philips, Saint-Laurent, Québec, Canada',
'legal.terms.contact.emailLabel': 'Courriel :',
'legal.terms.contact.email': 'info@synexumlabs.com',
'legal.terms.contact.phoneLabel': 'Téléphone :',
'legal.terms.contact.phone': '+1 (514) 351-5101',
'legal.terms.contact.generalInquiries': 'Demandes générales :',
'legal.terms.contact.contactForm': 'Formulaire de contact',


// ========================================
// LEGAL PAGE
// Legal Disclaimer
// ========================================

// --- Header ---
'legal.disclaimer.hero.title': 'Avis Juridique',
'legal.disclaimer.hero.lastUpdated': 'Dernière mise à jour : 28 Janvier 2026',

// --- Relationship Disclosure ---
'legal.disclaimer.relationship.title': 'Divulgation de Relation',
'legal.disclaimer.relationship.p1': 'Synexum Labs est une sous-marque technologique et de transformation numérique de Coigne Capital Inc., une société constituée selon les lois du Canada et enregistrée dans la province de Québec.',
'legal.disclaimer.relationship.p2': 'Synexum Labs opère comme une division dédiée à la transformation numérique, au développement logiciel et à l’automatisation au sein de l’écosystème Coigne Capital. Les services fournis sous la marque Synexum Labs sont contractés par Coigne Capital Inc., sauf indication écrite contraire.',
'legal.disclaimer.relationship.p3': 'Synexum Labs opère conformément à un accord formel de développement commercial et stratégique entre Coigne Capital Inc. et Happy People AI, en vertu duquel Happy People AI agit comme collaborateur technologique stratégique et partenaire de développement.',
'legal.disclaimer.relationship.p4': 'Le modèle de développement et de livraison de Synexum Labs est décentralisé et comprend des membres d’équipe et collaborateurs situés au Canada, aux États-Unis, en Inde et dans certaines juridictions d’Amérique latine.',
'legal.disclaimer.relationship.p5': 'Chaque entité au sein de cet écosystème opère de manière indépendante. Rien sur ce site web ne doit être interprété comme créant un partenariat, une coentreprise, une relation fiduciaire ou une relation d’agence au-delà de ce qui est expressément défini dans des ententes écrites.',

// --- Professional & Regulatory Disclaimer ---
'legal.disclaimer.professional.title': 'Avis Professionnel et Réglementaire',
'legal.disclaimer.professional.p1': 'Synexum Labs est le bras de transformation numérique et de prestation technologique de Coigne Capital Inc. Les services comprennent le développement logiciel sur mesure, les applications web, les systèmes d’automatisation, l’intégration d’IA, l’analytique de données, le support d’infrastructure et les services-conseils numériques.',
'legal.disclaimer.professional.p2': 'Ni Synexum Labs ni Coigne Capital Inc. ne sont des conseillers en placement enregistrés, courtiers, négociants ou intermédiaires en valeurs mobilières. Aucun contenu de ce site ne constitue un avis juridique, fiscal, comptable, d’investissement ou une sollicitation de produits ou services financiers réglementés.',
'legal.disclaimer.professional.p3': 'Les services technologiques peuvent soutenir des entreprises opérant dans des secteurs réglementés ou critiques; toutefois, la conformité réglementaire, l’interprétation juridique et le risque opérationnel demeurent la responsabilité exclusive du client.',
'legal.disclaimer.professional.caps': 'AUCUNE GARANTIE—EXPRESSE OU IMPLICITE—N’EST FOURNIE, Y COMPRIS, SANS S’Y LIMITER, LES GARANTIES DE QUALITÉ MARCHANDE, D’ADÉQUATION À UN USAGE PARTICULIER, D’EXACTITUDE OU DE DISPONIBILITÉ ININTERROMPUE.',

// --- Contact Information ---
'legal.disclaimer.contact.title': 'Coordonnées',
'legal.disclaimer.contact.intro': 'Pour toute question concernant cet Avis Juridique, veuillez nous contacter :',
'legal.disclaimer.contact.company': 'Coigne Capital Inc.',
'legal.disclaimer.contact.address': '555 Bd Dr.-Frederik-Philips, Saint-Laurent, Québec, Canada',
'legal.disclaimer.contact.emailLabel': 'Courriel :',
'legal.disclaimer.contact.email': 'info@synexumlabs.com',
'legal.disclaimer.contact.phoneLabel': 'Téléphone :',
'legal.disclaimer.contact.phone': '+1 (514) 351-5101',


// ========================================
// CAPABILITY BRIEF PAGE
// Synexum Labs – Capability Brief
// ========================================

// --- Meta ---
'capabilityBrief.meta.title': 'Synexum Labs – Présentation des Capacités',

// --- Top Bar ---
'capabilityBrief.top.back': '← Retour au site',
'capabilityBrief.top.print': 'Imprimer / Enregistrer en PDF',
'capabilityBrief.top.download': 'Télécharger le PDF',

// --- Header ---
'capabilityBrief.header.title': 'Présentation des Capacités',
'capabilityBrief.header.subtitle': 'Systèmes Intelligents pour les Opérations Institutionnelles',
'capabilityBrief.header.logoAlt': 'Logo Synexum Labs',
'capabilityBrief.header.logoAria': 'Synexum Labs - Accueil',

// --- Executive Summary ---
'capabilityBrief.executive.title': 'Résumé Exécutif',
'capabilityBrief.executive.p1': 'Synexum Labs conçoit, développe et exploite des systèmes intelligents d’IA et d’automatisation qui réduisent les cycles opérationnels, améliorent le contrôle et génèrent des résultats mesurables pour les organisations institutionnelles.',

// --- Core Capabilities ---
'capabilityBrief.capabilities.title': 'Capacités Principales',

'capabilityBrief.capabilities.governed.title': 'Modèle de Livraison Gouverné',
'capabilityBrief.capabilities.governed.desc': 'Exécution de niveau institutionnel avec responsabilité claire, contrôle de conformité et outils intégrés.',

'capabilityBrief.capabilities.architecture.title': 'Architecture de Systèmes Évolutive',
'capabilityBrief.capabilities.architecture.desc': 'Systèmes adaptatifs reliant données, décisions et exécution sous un cadre de gouvernance.',

'capabilityBrief.capabilities.platform.title': 'Ingénierie de Plateforme Évolutive',
'capabilityBrief.capabilities.platform.desc': 'Ingénierie full-stack et IA livrée via un modèle global gouverné.',

'capabilityBrief.capabilities.modular.title': 'Développement en Cellules Modulaires',
'capabilityBrief.capabilities.modular.desc': 'Unités autonomes opérant dans un cadre de gouvernance centralisé.',

'capabilityBrief.capabilities.sustainment.title': 'Maintien de Niveau Institutionnel',
'capabilityBrief.capabilities.sustainment.desc': 'Surveillance continue, support de conformité et amélioration opérationnelle permanente.',

// --- Methodology ---
'capabilityBrief.methodology.title': 'Notre Méthodologie',

'capabilityBrief.methodology.step1': 'Découvrir',
'capabilityBrief.methodology.step2': 'Concevoir',
'capabilityBrief.methodology.step3': 'Construire',
'capabilityBrief.methodology.step4': 'Exploiter',

// --- Proven Results ---
'capabilityBrief.results.title': 'Résultats Prouvés',

'capabilityBrief.results.item1.value': '92 %',
'capabilityBrief.results.item1.label': 'Réduction du Temps',

'capabilityBrief.results.item2.value': '99,8 %',
'capabilityBrief.results.item2.label': 'Précision',

'capabilityBrief.results.item3.value': '4 mois',
'capabilityBrief.results.item3.label': 'Délai de ROI',

// --- Industries ---
'capabilityBrief.industries.title': 'Secteurs Desservis',
'capabilityBrief.industries.item1': 'Services Financiers',
'capabilityBrief.industries.item2': 'Santé',
'capabilityBrief.industries.item3': 'Entreprises',
'capabilityBrief.industries.item4': 'Gouvernement',

// --- Get Started ---
'capabilityBrief.cta.title': 'Commencer',
'capabilityBrief.cta.p1': 'Planifiez un appel de découverte pour explorer comment Synexum Labs peut transformer vos opérations.',
'capabilityBrief.cta.websiteLabel': 'Site web :',
'capabilityBrief.cta.website': 'synexumlabs.com',
'capabilityBrief.cta.emailLabel': 'Courriel :',
'capabilityBrief.cta.email': 'support@synexumlabs.com',

// --- Footer ---
'capabilityBrief.footer.copyright': '© Coigne Capital Inc. — Synexum Labs',
'capabilityBrief.footer.confidential': 'Confidentiel – Destiné uniquement aux clients potentiels.',



// ========================================
// CAPABILITIES PAGE
// Living Systems Architecture
// ========================================

// --- Hero ---
'capabilities.livingSystems.hero.title': 'Architecture de Systèmes Évolutifs',
'capabilities.livingSystems.hero.subtitle': "La couche d'intelligence qui relie vos données, vos décisions et votre exécution - des systèmes qui observent, apprennent et s’adaptent.",
'capabilities.livingSystems.hero.bgAlt': 'Arrière-plan de protection assurance',

// --- Overview ---
'capabilities.livingSystems.overview.title': 'Aperçu',
'capabilities.livingSystems.overview.p1': "Nous concevons et développons la couche d'intelligence qui relie vos données, vos décisions et votre exécution. Il ne s'agit pas simplement de créer des applications ; il s'agit de bâtir un système durable qui observe ce qui se passe, détermine ce qui est important, déclenche des actions et apprend des résultats - tout en restant gouverné. Ces « systèmes évolutifs » constituent l’infrastructure décisionnelle qui rend votre organisation plus intelligente, plus rapide et plus responsable.",

// --- What We Deliver ---
'capabilities.livingSystems.deliver.title': 'Ce que nous livrons',

'capabilities.livingSystems.deliver.observe.title': "Couche d'Observation",
'capabilities.livingSystems.deliver.observe.desc': "Infrastructure de collecte et de détection des données qui capte les signaux opérationnels de votre organisation en temps réel.",

'capabilities.livingSystems.deliver.decide.title': 'Couche de Décision',
'capabilities.livingSystems.deliver.decide.desc': "Moteurs décisionnels alimentés par l’IA qui évaluent les conditions, appliquent les règles métier et déterminent les actions optimales.",

'capabilities.livingSystems.deliver.trigger.title': 'Couche de Déclenchement',
'capabilities.livingSystems.deliver.trigger.desc': "Orchestration d’exécution qui initie des flux de travail, des notifications et des réponses automatisées basées sur les décisions.",

'capabilities.livingSystems.deliver.learn.title': "Couche d'Apprentissage",
'capabilities.livingSystems.deliver.learn.desc': "Boucles de rétroaction et composants d’apprentissage automatique qui améliorent continuellement les performances du système.",

'capabilities.livingSystems.deliver.governance.title': 'Contrôles de Gouvernance',
'capabilities.livingSystems.deliver.governance.desc': "Pistes d’audit intégrées, mécanismes d’explicabilité et points de contrôle humain pour les décisions critiques.",

'capabilities.livingSystems.deliver.integration.title': "Architecture d'Intégration",
'capabilities.livingSystems.deliver.integration.desc': "Structure connective reliant les systèmes évolutifs à votre écosystème technologique existant.",

// --- Integrations ---
'capabilities.livingSystems.integrations.title': 'Intégrations Typiques',
'capabilities.livingSystems.integrations.intro': "Nous travaillons avec votre pile technologique existante et nous intégrons de manière transparente aux plateformes standards de l’industrie.",

'capabilities.livingSystems.integrations.azure': 'Azure AI',
'capabilities.livingSystems.integrations.aws': 'AWS SageMaker',
'capabilities.livingSystems.integrations.google': 'Google Cloud AI',
'capabilities.livingSystems.integrations.openai': 'OpenAI',
'capabilities.livingSystems.integrations.anthropic': 'Anthropic',
'capabilities.livingSystems.integrations.databricks': 'Databricks',
'capabilities.livingSystems.integrations.snowflake': 'Snowflake',
'capabilities.livingSystems.integrations.kafka': 'Apache Kafka',
'capabilities.livingSystems.integrations.kubernetes': 'Kubernetes',
'capabilities.livingSystems.integrations.custom': 'Pipelines ML personnalisés',

// --- Example Deliverables ---
'capabilities.livingSystems.examples.title': 'Exemples de Livrables',

'capabilities.livingSystems.examples.item1': "Plan directeur d’architecture des systèmes évolutifs",
'capabilities.livingSystems.examples.item2': 'Conceptions de flux de travail Observer-Décider-Déclencher-Apprendre (ODTL)',
'capabilities.livingSystems.examples.item3': 'Spécifications des modèles IA et plans d’entraînement',
'capabilities.livingSystems.examples.item4': "Documentation d’architecture d’intégration",
'capabilities.livingSystems.examples.item5': "Cadres de gouvernance et d’explicabilité",
'capabilities.livingSystems.examples.item6': 'Tableaux de bord de suivi des performances',


// ========================================
// CAPABILITIES PAGE
// Scalable Platform Engineering
// ========================================

// --- Hero ---
'capabilities.platformEngineering.hero.title': 'Ingénierie de Plateforme Évolutive',
'capabilities.platformEngineering.hero.subtitle': 'Développement full-stack, intégration IA/ML, DevOps et services QA avec capacité d’exécution mondiale.',
'capabilities.platformEngineering.hero.bgAlt': 'Arrière-plan de protection assurance',

// --- Overview ---
'capabilities.platformEngineering.overview.title': 'Aperçu',
'capabilities.platformEngineering.overview.p1': "Nous fournissons des services de développement full-stack, d’intégration IA/ML, DevOps et d’assurance qualité. Notre capacité d’exécution mondiale nous permet de déployer rapidement et d’assurer une livraison continue à travers les fuseaux horaires, tout en respectant le cadre de gouvernance du modèle Synexum. Que vous souhaitiez créer de nouvelles applications, moderniser des systèmes existants ou renforcer votre capacité d’ingénierie, nous livrons avec une qualité et une rapidité de niveau institutionnel.",

// --- What We Deliver ---
'capabilities.platformEngineering.deliver.title': 'Ce que nous livrons',

'capabilities.platformEngineering.deliver.fullstack.title': 'Développement Full-Stack',
'capabilities.platformEngineering.deliver.fullstack.desc': 'Développement applicatif de bout en bout pour le web, le mobile et les plateformes d’entreprise en utilisant des stacks technologiques modernes.',

'capabilities.platformEngineering.deliver.aiml.title': 'Intégration IA/ML',
'capabilities.platformEngineering.deliver.aiml.desc': "Intégration de capacités d’intelligence artificielle et d’apprentissage automatique dans vos applications et flux de travail.",

'capabilities.platformEngineering.deliver.devops.title': 'DevOps & Infrastructure Cloud',
'capabilities.platformEngineering.deliver.devops.desc': "Pipelines CI/CD, infrastructure as code et architecture cloud pour des déploiements fiables et évolutifs.",

'capabilities.platformEngineering.deliver.qa.title': 'Assurance Qualité',
'capabilities.platformEngineering.deliver.qa.desc': "Stratégies de test complètes incluant tests automatisés, tests de performance et évaluations de sécurité.",

'capabilities.platformEngineering.deliver.api.title': 'Développement d’API',
'capabilities.platformEngineering.deliver.api.desc': "Conception et mise en œuvre d’API RESTful et GraphQL pour une intégration système fluide.",

'capabilities.platformEngineering.deliver.legacy.title': 'Modernisation des Systèmes Hérités',
'capabilities.platformEngineering.deliver.legacy.desc': "Migration stratégique et modernisation des systèmes existants tout en maintenant la continuité des activités.",

// --- Integrations ---
'capabilities.platformEngineering.integrations.title': 'Intégrations Typiques',
'capabilities.platformEngineering.integrations.intro': "Nous travaillons avec votre pile technologique existante et nous intégrons de manière transparente aux plateformes standards de l’industrie.",

'capabilities.platformEngineering.integrations.aws': 'AWS',
'capabilities.platformEngineering.integrations.azure': 'Azure',
'capabilities.platformEngineering.integrations.google': 'Google Cloud',
'capabilities.platformEngineering.integrations.kubernetes': 'Kubernetes',
'capabilities.platformEngineering.integrations.docker': 'Docker',
'capabilities.platformEngineering.integrations.terraform': 'Terraform',
'capabilities.platformEngineering.integrations.github': 'GitHub Actions',
'capabilities.platformEngineering.integrations.jenkins': 'Jenkins',
'capabilities.platformEngineering.integrations.react': 'React',
'capabilities.platformEngineering.integrations.node': 'Node.js',
'capabilities.platformEngineering.integrations.python': 'Python',
'capabilities.platformEngineering.integrations.dotnet': '.NET',

// --- Example Deliverables ---
'capabilities.platformEngineering.examples.title': 'Exemples de Livrables',

'capabilities.platformEngineering.examples.item1': 'Applications et microservices prêts pour la production',
'capabilities.platformEngineering.examples.item2': 'Configurations de pipelines CI/CD',
'capabilities.platformEngineering.examples.item3': 'Architecture d’infrastructure cloud',
'capabilities.platformEngineering.examples.item4': 'Documentation et spécifications d’API',
'capabilities.platformEngineering.examples.item5': 'Suites de tests automatisés',
'capabilities.platformEngineering.examples.item6': 'Rapports d’optimisation des performances',

// ========================================
// CAPABILITIES PAGE
// Modular Cell Development
// ========================================

// --- Hero ---
'capabilities.modularCell.hero.title': 'Développement de Cellules Modulaires',
'capabilities.modularCell.hero.subtitle': "Unités d’exécution spécifiques à un domaine qui opèrent avec autonomie et rapidité tout en héritant de la gouvernance du Core/Grid.",
'capabilities.modularCell.hero.bgAlt': 'Arrière-plan de protection assurance',

// --- Overview ---
'capabilities.modularCell.overview.title': 'Aperçu',
'capabilities.modularCell.overview.p1': "Nous construisons des unités d’exécution spécifiques à un domaine (« Cellules ») pour des fonctions telles que la Finance, les Opérations et l’Analytique. Chaque Cellule fonctionne avec autonomie et rapidité, mais hérite de ses normes de gouvernance et de conformité du « Core/Grid » central, vous permettant de croître sans sacrifier le contrôle. Cette architecture résout le paradoxe de l’évolutivité : comment accroître la capacité d’exécution sans perdre la gouvernance, la responsabilité ou la cohérence institutionnelle.",

// --- What We Deliver ---
'capabilities.modularCell.deliver.title': 'Ce que nous livrons',

'capabilities.modularCell.deliver.core.title': 'Architecture Core/Grid',
'capabilities.modularCell.deliver.core.desc': 'Couche centrale de gouvernance définissant les normes, politiques et exigences de conformité héritées par toutes les Cellules.',

'capabilities.modularCell.deliver.cells.title': 'Cellules Spécifiques au Domaine',
'capabilities.modularCell.deliver.cells.desc': 'Unités d’exécution autonomes adaptées à des fonctions spécifiques telles que la Finance, les Opérations, les RH ou l’Analytique.',

'capabilities.modularCell.deliver.inheritance.title': 'Héritage de Gouvernance des Cellules',
'capabilities.modularCell.deliver.inheritance.desc': 'Mécanismes garantissant que chaque Cellule hérite automatiquement et applique les normes de gouvernance du Core/Grid.',

'capabilities.modularCell.deliver.communication.title': 'Communication Inter-Cellules',
'capabilities.modularCell.deliver.communication.desc': 'Interfaces sécurisées et gouvernées pour l’échange de données et de flux de travail entre Cellules.',

'capabilities.modularCell.deliver.monitoring.title': 'Suivi des Performances des Cellules',
'capabilities.modularCell.deliver.monitoring.desc': 'Tableaux de bord et indicateurs suivant les performances, la conformité et la santé opérationnelle des Cellules.',

'capabilities.modularCell.deliver.scaling.title': 'Guides de Mise à l’Échelle',
'capabilities.modularCell.deliver.scaling.desc': 'Processus documentés pour créer de nouvelles Cellules ou étendre celles existantes tout en maintenant la gouvernance.',

// --- Integrations ---
'capabilities.modularCell.integrations.title': 'Intégrations Typiques',
'capabilities.modularCell.integrations.intro': "Nous travaillons avec votre pile technologique existante et nous intégrons de manière transparente aux plateformes standards de l’industrie.",

'capabilities.modularCell.integrations.kubernetes': 'Kubernetes',
'capabilities.modularCell.integrations.docker': 'Docker',
'capabilities.modularCell.integrations.kafka': 'Apache Kafka',
'capabilities.modularCell.integrations.rabbitmq': 'RabbitMQ',
'capabilities.modularCell.integrations.terraform': 'Terraform',
'capabilities.modularCell.integrations.consul': 'Consul',
'capabilities.modularCell.integrations.vault': 'Vault',
'capabilities.modularCell.integrations.prometheus': 'Prometheus',
'capabilities.modularCell.integrations.grafana': 'Grafana',
'capabilities.modularCell.integrations.custom': 'Orchestration personnalisée',

// --- Example Deliverables ---
'capabilities.modularCell.examples.title': 'Exemples de Livrables',

'capabilities.modularCell.examples.item1': 'Spécifications de l’architecture Core/Grid',
'capabilities.modularCell.examples.item2': 'Plans directeurs de Cellules pour chaque domaine',
'capabilities.modularCell.examples.item3': 'Documentation sur l’héritage de gouvernance',
'capabilities.modularCell.examples.item4': 'Contrats API inter-Cellules',
'capabilities.modularCell.examples.item5': 'Configurations de surveillance et d’alertes',
'capabilities.modularCell.examples.item6': 'Runbooks de mise à l’échelle et de déploiement des Cellules',


// ========================================
// CAPABILITIES PAGE
// Institutional-Grade Sustainment
// ========================================

// --- Hero ---
'capabilities.sustainment.hero.title': 'Maintien de Niveau Institutionnel',
'capabilities.sustainment.hero.subtitle': "Support opérationnel continu garantissant que vos systèmes restent stables, conformes et continuent à générer de la valeur dans le temps.",
'capabilities.sustainment.hero.bgAlt': 'Arrière-plan de protection assurance',

// --- Overview ---
'capabilities.sustainment.overview.title': 'Aperçu',
'capabilities.sustainment.overview.p1': "Notre engagement ne s’arrête pas au lancement. Nous fournissons un support opérationnel continu afin de garantir que vos systèmes restent stables, conformes et continuent à générer de la valeur au fil du temps. Nous gérons le système pour que vous puissiez vous concentrer sur votre activité. Ce maintien de niveau institutionnel garantit que vos investissements numériques ne se dégradent pas, mais s’améliorent continuellement et s’adaptent aux besoins évolutifs de l’entreprise.",

// --- What We Deliver ---
'capabilities.sustainment.deliver.title': 'Ce que nous livrons',

'capabilities.sustainment.deliver.monitoring.title': 'Surveillance des Opérations 24/7',
'capabilities.sustainment.deliver.monitoring.desc': "Surveillance continue de la santé, des performances et de la sécurité du système avec réponse immédiate aux incidents.",

'capabilities.sustainment.deliver.maintenance.title': 'Maintenance Proactive',
'capabilities.sustainment.deliver.maintenance.desc': "Mises à jour planifiées, correctifs et optimisations qui préviennent les problèmes avant qu’ils n’impactent les opérations.",

'capabilities.sustainment.deliver.compliance.title': 'Maintien de la Conformité',
'capabilities.sustainment.deliver.compliance.desc': "Surveillance continue de la conformité et adaptation aux exigences réglementaires en évolution.",

'capabilities.sustainment.deliver.performance.title': 'Optimisation des Performances',
'capabilities.sustainment.deliver.performance.desc': "Ajustements et améliorations continus pour garantir que les systèmes atteignent leurs objectifs de performance.",

'capabilities.sustainment.deliver.capacity.title': 'Gestion de la Capacité',
'capabilities.sustainment.deliver.capacity.desc': "Mise à l’échelle proactive et gestion des ressources pour gérer la croissance et les fluctuations de la demande.",

'capabilities.sustainment.deliver.improvement.title': 'Amélioration Continue',
'capabilities.sustainment.deliver.improvement.desc': "Revues régulières et améliorations qui font évoluer vos systèmes sur la base des apprentissages opérationnels.",

// --- Integrations ---
'capabilities.sustainment.integrations.title': 'Intégrations Typiques',
'capabilities.sustainment.integrations.intro': "Nous nous intégrons à votre écosystème technologique existant et nous alignons sur des plateformes et chaînes d’outils de livraison de niveau entreprise.",

'capabilities.sustainment.integrations.pagerduty': 'PagerDuty',
'capabilities.sustainment.integrations.datadog': 'Datadog',
'capabilities.sustainment.integrations.newrelic': 'New Relic',
'capabilities.sustainment.integrations.splunk': 'Splunk',
'capabilities.sustainment.integrations.servicenow': 'ServiceNow',
'capabilities.sustainment.integrations.jira': 'Jira Service Management',
'capabilities.sustainment.integrations.cloudwatch': 'AWS CloudWatch',
'capabilities.sustainment.integrations.azuremonitor': 'Azure Monitor',
'capabilities.sustainment.integrations.prometheus': 'Prometheus',
'capabilities.sustainment.integrations.grafana': 'Grafana',

// --- Example Deliverables ---
'capabilities.sustainment.examples.title': 'Exemples de Livrables',

'capabilities.sustainment.examples.item1': 'Accords de niveau de service (SLA)',
'capabilities.sustainment.examples.item2': 'Configurations de surveillance et d’alertes',
'capabilities.sustainment.examples.item3': 'Playbooks de réponse aux incidents',
'capabilities.sustainment.examples.item4': 'Rapports mensuels d’exploitation',
'capabilities.sustainment.examples.item5': 'Documentation d’audit de conformité',
'capabilities.sustainment.examples.item6': 'Feuilles de route d’amélioration continue',


// ========================================
// CASE STUDIES PAGE
// Replacing Admin Work With Automation
// ========================================

// --- Hero ---
'caseStudies.adminAutomation.hero.title': "Remplacer le Travail Administratif par l’Automatisation : Analyse Complète d’une Mise en Place Réelle avec Go High Level",
'caseStudies.adminAutomation.hero.subtitle': "Une analyse détaillée d’une mise en place réelle avec Go High Level montrant comment l’automatisation a remplacé les tâches administratives répétitives sans embaucher davantage de personnel.",
'caseStudies.adminAutomation.hero.tag1': 'Automatisation des Processus',
'caseStudies.adminAutomation.hero.tag2': 'Opérations',
'caseStudies.adminAutomation.hero.tag3': 'Entreprise de Services Numériques',
'caseStudies.adminAutomation.hero.bgAlt': 'Arrière-plan de protection assurance',

// --- Metrics ---
'caseStudies.adminAutomation.metrics.item1.value': '60%+',
'caseStudies.adminAutomation.metrics.item1.label': 'Tâches Administratives Automatisées',

'caseStudies.adminAutomation.metrics.item2.value': '45%↓',
'caseStudies.adminAutomation.metrics.item2.label': 'Coordination Manuelle',

'caseStudies.adminAutomation.metrics.item3.value': '35%↑',
'caseStudies.adminAutomation.metrics.item3.label': 'Vitesse Opérationnelle',

'caseStudies.adminAutomation.metrics.item4.value': '0',
'caseStudies.adminAutomation.metrics.item4.label': 'Nouvelles Embauches Administratives',

// --- Context ---
'caseStudies.adminAutomation.context.label': 'Le Contexte',
'caseStudies.adminAutomation.context.title': "Le travail administratif ralentissait la croissance.",
'caseStudies.adminAutomation.context.p1': "L’entreprise ne reculait pas.",
'caseStudies.adminAutomation.context.p2': "En réalité, la demande restait stable.",
'caseStudies.adminAutomation.context.p3': "Les prospects arrivaient, les clients étaient accompagnés et les revenus entraient. Mais en coulisses, l’équipe était submergée par des tâches administratives devenues silencieusement un frein au progrès.",
'caseStudies.adminAutomation.context.p4': "Les tâches manuelles représentaient une grande partie des opérations quotidiennes :",

'caseStudies.adminAutomation.context.list1': 'Ajout et mise à jour des prospects',
'caseStudies.adminAutomation.context.list2': 'Relances et rappels',
'caseStudies.adminAutomation.context.list3': 'Coordination des rendez-vous',
'caseStudies.adminAutomation.context.list4': 'Suivi des statuts dans des feuilles de calcul',
'caseStudies.adminAutomation.context.list5': 'Transferts internes via email et WhatsApp',

'caseStudies.adminAutomation.context.p5': "Aucun de ces efforts ne générait directement des revenus, mais ils consommaient beaucoup de temps, d’attention et d’énergie.",
'caseStudies.adminAutomation.context.p6': "Cette étude de cas montre comment Go High Level a utilisé l’automatisation pour remplacer les tâches administratives répétitives, rendant l’entreprise plus agile, plus rapide et plus évolutive sans recruter davantage.",

// --- Challenge ---
'caseStudies.adminAutomation.challenge.label': 'Le Défi',
'caseStudies.adminAutomation.challenge.title': "Des personnes faisaient des tâches qui ne devraient pas être humaines",
'caseStudies.adminAutomation.challenge.p1': "Des employés effectuaient des tâches que les systèmes auraient dû gérer. Parmi les principaux problèmes :",

'caseStudies.adminAutomation.challenge.list1': "Des employés passant des heures à saisir des données",
'caseStudies.adminAutomation.challenge.list2': "Des relances manquées à cause d’un suivi manuel",
'caseStudies.adminAutomation.challenge.list3': "Des membres de l’équipe utilisant des processus différents",
'caseStudies.adminAutomation.challenge.list4': "Des transferts et validations trop longs",
'caseStudies.adminAutomation.challenge.list5': "Aucune visibilité en temps réel sur les opérations",

'caseStudies.adminAutomation.challenge.p2': "À mesure que le volume augmentait, la charge administrative croissait proportionnellement. Plus de clients signifiait plus de communications, plus de coordination et davantage de risques d’erreurs. L’entreprise grandissait, mais son efficacité n’augmentait pas.",

// --- Approach ---
'caseStudies.adminAutomation.approach.label': 'Notre Approche',
'caseStudies.adminAutomation.approach.title': "Pourquoi embaucher plus d’administratif n’était pas la solution",
'caseStudies.adminAutomation.approach.p1': "Embaucher davantage de personnel administratif aurait augmenté les coûts, la complexité et la dépendance sans résoudre le problème fondamental. Le problème n’était pas la capacité, mais la conception des processus. L’automatisation a éliminé la coordination manuelle à la source.",

// Phase 1
'caseStudies.adminAutomation.approach.phase1.title': 'Cartographie des Tâches Administratives',
'caseStudies.adminAutomation.approach.phase1.duration': 'Semaines 1–2',
'caseStudies.adminAutomation.approach.phase1.desc': "Avant de commencer, Go High Level a réalisé un audit opérationnel complet pour comprendre où le temps et les efforts étaient consacrés.",
'caseStudies.adminAutomation.approach.phase1.p1': 'Nous avons cartographié :',
'caseStudies.adminAutomation.approach.phase1.list1': 'Les tâches quotidiennes, hebdomadaires et mensuelles',
'caseStudies.adminAutomation.approach.phase1.list2': 'La durée de chaque tâche',
'caseStudies.adminAutomation.approach.phase1.list3': 'Les dépendances entre tâches',
'caseStudies.adminAutomation.approach.phase1.list4': 'Les points d’erreur ou de retard',
'caseStudies.adminAutomation.approach.phase1.p2': "Plus de 60 % du temps administratif était consacré à des tâches répétitives avec des règles claires, idéales pour l’automatisation.",

// Phase 2
'caseStudies.adminAutomation.approach.phase2.title': 'Un Système Unique de Référence',
'caseStudies.adminAutomation.approach.phase2.duration': 'Semaines 3–4',
'caseStudies.adminAutomation.approach.phase2.desc': "Le trop grand nombre d’outils créait duplication, confusion et réconciliation manuelle.",
'caseStudies.adminAutomation.approach.phase2.p1': "Toutes les données opérationnelles ont été centralisées dans un système unique, éliminant les vérifications croisées et les relances inutiles.",

// Phase 3
'caseStudies.adminAutomation.approach.phase3.title': 'Automatisation des Flux Administratifs Clés',
'caseStudies.adminAutomation.approach.phase3.duration': 'Semaines 5–7',
'caseStudies.adminAutomation.approach.phase3.desc': "Les tâches administratives critiques ont été automatisées pour permettre au système de créer, assigner et suivre le travail sans intervention manuelle.",

// Phase 4
'caseStudies.adminAutomation.approach.phase4.title': 'Intervention Humaine Basée sur les Exceptions',
'caseStudies.adminAutomation.approach.phase4.duration': 'Semaines 8–10',
'caseStudies.adminAutomation.approach.phase4.desc': "L’automatisation gérait le parcours standard, tandis que les employés intervenaient uniquement en cas d’exception (retards, blocages, décisions nécessitant un jugement).",

// Phase 5
'caseStudies.adminAutomation.approach.phase5.title': 'Reporting, Responsabilité et Visibilité',
'caseStudies.adminAutomation.approach.phase5.duration': 'Semaines 11–12',
'caseStudies.adminAutomation.approach.phase5.desc': "Des tableaux de bord en temps réel ont remplacé le suivi manuel, offrant une visibilité complète sur les progrès et les performances opérationnelles.",

// --- Results ---
'caseStudies.adminAutomation.results.label': 'Les Résultats',
'caseStudies.adminAutomation.results.title': 'Du Travail Administratif Manuel aux Opérations Automatisées',

'caseStudies.adminAutomation.results.card1.before': 'Élevé',
'caseStudies.adminAutomation.results.card1.after': '60%+↓',
'caseStudies.adminAutomation.results.card1.label': 'Charge administrative fortement réduite',

'caseStudies.adminAutomation.results.card2.before': 'Lent',
'caseStudies.adminAutomation.results.card2.after': '35%↑',
'caseStudies.adminAutomation.results.card2.label': 'Exécution des tâches plus rapide',

'caseStudies.adminAutomation.results.card3.before': 'Fréquent',
'caseStudies.adminAutomation.results.card3.after': '45%↓',
'caseStudies.adminAutomation.results.card3.label': 'Réduction des erreurs et des relances manquées',

'caseStudies.adminAutomation.results.card4.before': 'Manuel',
'caseStudies.adminAutomation.results.card4.after': 'Automatisé',
'caseStudies.adminAutomation.results.card4.label': 'Gestion des prospects et coordination interne',

// --- Testimonial ---
'caseStudies.adminAutomation.testimonial.quote': "Nos utilisateurs explorent désormais, interagissent et finalisent des actions au lieu de quitter la plateforme après quelques secondes. La refonte a complètement transformé l’engagement.",
'caseStudies.adminAutomation.testimonial.author': 'Responsable Produit',
'caseStudies.adminAutomation.testimonial.title': 'Entreprise de Plateforme Numérique',

// --- CTA ---
'caseStudies.adminAutomation.cta.title': 'Vous souhaitez augmenter l’engagement sans plus de trafic ?',
'caseStudies.adminAutomation.cta.subtitle': 'Nous aidons les plateformes numériques à transformer des visiteurs passifs en utilisateurs actifs grâce à une conception UX basée sur la recherche.',
'caseStudies.adminAutomation.cta.primary': 'Planifier une Consultation',
'caseStudies.adminAutomation.cta.secondary': 'Voir Plus d’Études de Cas',


// ========================================
// INSIGHTS PAGE
// Designing CI/CD Pipelines
// ========================================

// --- Hero ---
'insights.cicd.hero.category': 'Services et Conseil en TI',
'insights.cicd.hero.date': '04 février 2026',
'insights.cicd.hero.title': 'Concevoir des Pipelines CI/CD pour des Équipes d’Ingénierie à Haute Vélocité',
'insights.cicd.hero.excerpt': "Les équipes d’ingénierie à haute vélocité ont besoin de plus que de rapidité. Des pipelines CI/CD bien conçus permettent une livraison logicielle rapide tout en préservant la qualité, la sécurité et la fiabilité opérationnelle à grande échelle.",
'insights.cicd.hero.bgAlt': 'Arrière-plan de protection assurance',

// --- Body Intro ---
'insights.cicd.body.p1': "Dans le monde numérique actuel, où la concurrence est intense, la rapidité n’est pas une option ; c’est une nécessité. Les équipes d’ingénierie performantes doivent pouvoir ajouter rapidement de nouvelles fonctionnalités, corriger des défauts et maintenir une qualité élevée, même à grande échelle. C’est là que la mise en place de pipelines CI/CD devient essentielle pour la livraison rapide de logiciels et la vélocité d’ingénierie à long terme.",

'insights.cicd.body.p2': "Un pipeline CI/CD moderne permet aux équipes de déployer des changements rapidement et en toute sécurité sans compromettre la sécurité, la stabilité ou la confiance des développeurs. À mesure que les organisations adoptent des modèles Agile et DevOps, les déploiements manuels, les environnements incohérents et les boucles de rétroaction lentes deviennent des risques opérationnels. Les pipelines CI/CD conçus sur mesure répondent à ces défis en imposant la standardisation, en automatisant les contrôles qualité et en garantissant la cohérence entre les environnements.",

// --- Section 1 ---
'insights.cicd.section1.title': '1. Pourquoi CI/CD est essentiel pour les équipes à haute vélocité',
'insights.cicd.section1.p1': "Les équipes qui travaillent rapidement évoluent dans des environnements où le code change en permanence. Sans un système CI/CD solide, ces changements peuvent entraîner des échecs de compilation et de déploiement et ralentir le développement.",
'insights.cicd.section1.p2': "Les pipelines CI/CD automatisent la compilation, les tests et le déploiement du code. Les équipes peuvent ainsi se concentrer sur la création de nouvelles fonctionnalités plutôt que sur les mises en production. Correctement configurés, ils agissent comme un filet de sécurité en détectant les problèmes tôt et en assurant des livraisons rapides et fiables.",

// --- Section 2 ---
'insights.cicd.section2.title': '2. Principes fondamentaux des pipelines de livraison rapide',
'insights.cicd.section2.p1': "Pour fonctionner efficacement, la conception CI/CD doit privilégier la vitesse et la fiabilité. Les meilleurs pipelines réussissent parce qu’ils suivent des principes fondamentaux.",
'insights.cicd.section2.p2': "Tout d’abord, tout doit être automatisé. Les processus manuels ralentissent chaque étape. De la modification du code à la mise en production, l’automatisation garantit cohérence et efficacité.",
'insights.cicd.section2.p3': "Les tests doivent commencer tôt et se poursuivre en continu. Les tests unitaires, d’intégration et de sécurité doivent être exécutés dès que possible afin d’éviter les ralentissements ultérieurs.",
'insights.cicd.section2.p4': "L’exécution parallèle — exécuter les tests et les compilations simultanément — accélère considérablement les cycles de publication.",

// --- Section 3 ---
'insights.cicd.section3.title': '3. Concevoir des pipelines DevOps évolutifs',
'insights.cicd.section3.p1': "Un pipeline Agile DevOps doit évoluer avec l’équipe. À mesure que les organisations grandissent, leurs pipelines doivent gérer davantage de services, de contributeurs et d’environnements sans défaillance.",
'insights.cicd.section3.p2': "Les systèmes CI/CD évolutifs utilisent des pipelines modulaires, des modèles réutilisables et des approches pipeline-as-code pour garantir l’uniformité entre les projets.",
'insights.cicd.section3.p3': "Les solutions CI/CD cloud-native et les environnements conteneurisés offrent flexibilité et adaptabilité.",
'insights.cicd.section3.p4': "La visibilité est essentielle. Suivre les performances, les échecs et l’utilisation des pipelines permet une amélioration continue.",

// --- Section 4 ---
'insights.cicd.section4.title': '4. Maintenir la qualité dans des cycles de publication rapides',
'insights.cicd.section4.p1': "Des déploiements rapides ne signifient pas des déploiements négligés. Les équipes performantes utilisent des garde-fous pour équilibrer vitesse et qualité.",
'insights.cicd.section4.p2': "Les contrôles qualité automatisés, les processus d’approbation et les mécanismes de rollback garantissent la fiabilité.",
'insights.cicd.section4.p3': "La sécurité doit être intégrée au pipeline grâce à l’identification automatique des vulnérabilités et aux vérifications de dépendances.",

// --- Key Takeaways ---
'insights.cicd.takeaways.title': 'Points Clés',
'insights.cicd.takeaways.item1': "Les pipelines CI/CD sont essentiels à la vélocité d’ingénierie",
'insights.cicd.takeaways.item2': "Automatisation, tests et exécution parallèle permettent des retours rapides",
'insights.cicd.takeaways.item3': "Une conception évolutive soutient la croissance",
'insights.cicd.takeaways.item4': "Des garde-fous intégrés protègent la fiabilité",

// --- Conclusion ---
'insights.cicd.conclusion.title': 'Conclusion',
'insights.cicd.conclusion.p1': "Concevoir des pipelines CI/CD ne consiste pas seulement à automatiser, mais à instaurer la confiance nécessaire pour livrer rapidement.",
'insights.cicd.conclusion.p2': "Les organisations doivent se concentrer sur des pipelines rapides, évolutifs et alignés sur des normes de qualité strictes.",
'insights.cicd.conclusion.p3': "Un pipeline CI/CD bien conçu est un atout stratégique qui permet d’innover plus vite et de fournir une valeur constante.",

// --- Sidebar ---
'insights.cicd.sidebar.title': 'Dans Cet Article',
'insights.cicd.sidebar.item1': '1. Pourquoi CI/CD est important',
'insights.cicd.sidebar.item2': '2. Principes fondamentaux',
'insights.cicd.sidebar.item3': '3. Pipelines DevOps évolutifs',
'insights.cicd.sidebar.item4': '4. Garde-fous qualité & sécurité',
'insights.cicd.sidebar.item5': '5. Conclusion',

// --- Share ---
'insights.cicd.share.title': 'Partager Cet Article',
'insights.cicd.share.copied': 'Lien copié !',

// ========================================
// CASE STUDY PAGE
// Build & Deployment Automation
// ========================================

// --- Hero ---
'caseStudies.buildDeploy.hero.tag1': 'Automatisation des processus',
'caseStudies.buildDeploy.hero.tag2': 'Gouvernance & Sécurité',
'caseStudies.buildDeploy.hero.industry': 'Plateforme d’assureur santé',
'caseStudies.buildDeploy.hero.title': 'Automatisation du Build & du Déploiement pour une Suite d’Assureur Santé Basée sur le Cloud',
'caseStudies.buildDeploy.hero.subtitle': "Une analyse réelle de la mise en œuvre montrant comment une automatisation consciente des exigences de conformité a amélioré la vitesse de mise en production, la stabilité opérationnelle et la confiance — sans compromettre le contrôle réglementaire.",
'caseStudies.buildDeploy.hero.bgAlt': 'Arrière-plan de protection d’assurance',

// --- Metrics ---
'caseStudies.buildDeploy.metrics.item1.value': '55%↑',
'caseStudies.buildDeploy.metrics.item1.label': 'Cycles de mise en production plus rapides',
'caseStudies.buildDeploy.metrics.item2.value': '50%↓',
'caseStudies.buildDeploy.metrics.item2.label': 'Erreurs de déploiement',
'caseStudies.buildDeploy.metrics.item3.value': '40%↑',
'caseStudies.buildDeploy.metrics.item3.label': 'Stabilité opérationnelle',
'caseStudies.buildDeploy.metrics.item4.value': '100%',
'caseStudies.buildDeploy.metrics.item4.label': 'Automatisation conforme aux exigences réglementaires',

// --- Context ---
'caseStudies.buildDeploy.context.label': 'Le Contexte',
'caseStudies.buildDeploy.context.title': 'Les livraisons manuelles ralentissaient une plateforme critique',
'caseStudies.buildDeploy.context.p1': "Les builds manuels rendaient plus difficile l’innovation. La suite d’assureur santé était stable et fiable, mais elle subissait une forte pression en raison de sa croissance. La plateforme ne pouvait pas suivre les nouveaux besoins des assureurs, les changements réglementaires et les mises à jour fonctionnelles qui arrivaient plus rapidement qu’elle ne pouvait les publier.",
'caseStudies.buildDeploy.context.p2': "La demande restait élevée. Les clients avaient besoin que le système traite les réclamations, suive les polices et génère des rapports. Mais les processus de build et de déploiement étaient très manuels, lents et remplis de risques en arrière-plan.",
'caseStudies.buildDeploy.context.p3': "Plusieurs équipes devaient planifier les mises en production. Les fenêtres de déploiement étaient courtes en raison du risque en production. Il fallait des jours au lieu d’heures pour effectuer de petits changements de configuration. Le système fonctionnait, mais la vitesse de livraison était désalignée.",
'caseStudies.buildDeploy.context.p4': "Cette étude de cas montre comment nous avons automatisé le build et le déploiement d’une suite d’assureur santé basée sur le cloud. Cela a permis de publier de nouvelles versions plus rapidement tout en maintenant la sécurité, la stabilité et la conformité.",

// --- Challenge ---
'caseStudies.buildDeploy.challenge.label': 'Le Défi',
'caseStudies.buildDeploy.challenge.title': 'Les processus manuels créaient un risque de livraison, pas de fiabilité',
'caseStudies.buildDeploy.challenge.p1': "Le principal problème n’était pas l’infrastructure ni les compétences en ingénierie ; c’était la manière dont les builds et les déploiements étaient réalisés.",
'caseStudies.buildDeploy.challenge.p2': 'Voici certains des plus grands problèmes :',
'caseStudies.buildDeploy.challenge.item1': 'Construire et déployer manuellement dans différents environnements',
'caseStudies.buildDeploy.challenge.item2': 'Forte dépendance aux ingénieurs de release',
'caseStudies.buildDeploy.challenge.item3': 'Configurations incohérentes entre staging et production',
'caseStudies.buildDeploy.challenge.item4': 'Capacité limitée de rollback',
'caseStudies.buildDeploy.challenge.item5': 'Crainte des déploiements en raison des risques de downtime et de conformité',
'caseStudies.buildDeploy.challenge.item6': 'Absence de pipeline de release standardisé pour tous les services.',
'caseStudies.buildDeploy.challenge.p3': "À mesure que la plateforme grandissait, chaque nouvelle version devenait plus difficile. Plus de fonctionnalités signifiaient plus de planification, plus de vérifications et plus de risques. Même si la demande augmentait, la vitesse diminuait.",

// --- Approach ---
'caseStudies.buildDeploy.approach.label': 'Notre Approche',
'caseStudies.buildDeploy.approach.title': 'Une automatisation conçue pour le contrôle, pas pour le chaos',

// Phase 1
'caseStudies.buildDeploy.approach.phase1.number': '1',
'caseStudies.buildDeploy.approach.phase1.title': 'Analyse des workflows de build et de déploiement',
'caseStudies.buildDeploy.approach.phase1.duration': 'Semaines 1–2',
'caseStudies.buildDeploy.approach.phase1.p1': "Nous avons cartographié l’ensemble du processus de release, du commit du code jusqu’au déploiement en production. Chaque étape manuelle, chaque barrière d’approbation et chaque dépendance ont été documentées.",
'caseStudies.buildDeploy.approach.phase1.p2': "L’audit a révélé que plus de 65% du travail de déploiement était répétitif et basé sur des règles. Cela le rendait idéal pour l’automatisation sans compromettre la conformité.",

// Phase 2
'caseStudies.buildDeploy.approach.phase2.number': '2',
'caseStudies.buildDeploy.approach.phase2.title': 'Mise en place des mêmes pipelines de build pour tous les services ',
'caseStudies.buildDeploy.approach.phase2.duration': 'Semaines 3–4',
'caseStudies.buildDeploy.approach.phase2.p1': "Nous avons créé des pipelines de build standardisés et réutilisables pour l’ensemble de la suite d’assureur santé.",
'caseStudies.buildDeploy.approach.phase2.p2': 'Parmi les changements les plus importants :',
'caseStudies.buildDeploy.approach.phase2.item1': 'Paramètres de build cohérents',
'caseStudies.buildDeploy.approach.phase2.item2': 'Parité des environnements entre développement, staging et production',
'caseStudies.buildDeploy.approach.phase2.item3': 'Versionnement automatique des artefacts',
'caseStudies.buildDeploy.approach.phase2.item4': 'Gestion sécurisée des secrets',
'caseStudies.buildDeploy.approach.phase2.p3': "Cela a éliminé les incohérences qui provoquaient auparavant des échecs de déploiement.",

// Phase 3
'caseStudies.buildDeploy.approach.phase3.number': '3',
'caseStudies.buildDeploy.approach.phase3.title': 'Déploiement automatisé avec garde-fous de conformité',
'caseStudies.buildDeploy.approach.phase3.duration': 'Semaines 5–7',
'caseStudies.buildDeploy.approach.phase3.p1': "Nous avons tenu compte des règles de santé lors de l’automatisation du déploiement. Les pipelines automatisés garantissaient :",
'caseStudies.buildDeploy.approach.phase3.item1': 'Vérifications de validation avant déploiement',
'caseStudies.buildDeploy.approach.phase3.item2': 'Approbations spécifiques à chaque environnement',
'caseStudies.buildDeploy.approach.phase3.item3': 'Journalisation d’audit pour chaque release',
'caseStudies.buildDeploy.approach.phase3.item4': 'Stratégies de mise en production contrôlées',
'caseStudies.buildDeploy.approach.phase3.p2': "Chaque déploiement suivait le même chemin sécurisé, ce qui rendait les processus plus rapides et moins risqués.",

// Phase 4
'caseStudies.buildDeploy.approach.phase4.number': '4',
'caseStudies.buildDeploy.approach.phase4.title': 'Supervision, rollbacks et visibilité des releases',
'caseStudies.buildDeploy.approach.phase4.duration': 'Semaines 8–10',
'caseStudies.buildDeploy.approach.phase4.p1': "Au lieu de suivre le statut manuellement, des tableaux de bord de déploiement en temps réel faisaient le travail. Les équipes pouvaient immédiatement voir :",
'caseStudies.buildDeploy.approach.phase4.item1': 'La progression du déploiement',
'caseStudies.buildDeploy.approach.phase4.item2': 'Les points potentiels de défaillance',
'caseStudies.buildDeploy.approach.phase4.item3': 'La préparation au rollback',
'caseStudies.buildDeploy.approach.phase4.item4': "L’état de santé de l’environnement",
'caseStudies.buildDeploy.approach.phase4.p2': "Les procédures de rollback automatisées garantissaient que les problèmes pouvaient être résolus en toute sécurité sans provoquer de longues périodes d’interruption.",

// --- Results ---
'caseStudies.buildDeploy.results.label': 'Les Résultats',
'caseStudies.buildDeploy.results.title': 'Des releases manuelles à une livraison prévisible et conforme',
'caseStudies.buildDeploy.results.card1.before': 'Lent',
'caseStudies.buildDeploy.results.card1.after': '55% plus rapide',
'caseStudies.buildDeploy.results.card1.label': 'Cycles de release',
'caseStudies.buildDeploy.results.card2.before': 'Sujet aux erreurs',
'caseStudies.buildDeploy.results.card2.after': '50%↓',
'caseStudies.buildDeploy.results.card2.label': 'Échecs de déploiement',
'caseStudies.buildDeploy.results.card3.before': 'Fragile',
'caseStudies.buildDeploy.results.card3.after': 'Stable',
'caseStudies.buildDeploy.results.card3.label': 'Fiabilité opérationnelle',
'caseStudies.buildDeploy.results.card4.before': 'Manuel',
'caseStudies.buildDeploy.results.card4.after': 'Gouverné',
'caseStudies.buildDeploy.results.card4.label': 'Releases prêtes pour la conformité',

// --- Testimonial ---
'caseStudies.buildDeploy.testimonial.quote': "Nos utilisateurs explorent désormais, interagissent et complètent des actions au lieu de quitter après quelques secondes. La refonte a complètement changé la façon dont les personnes interagissent avec notre plateforme.",
'caseStudies.buildDeploy.testimonial.authorName': 'Responsable Produit',
'caseStudies.buildDeploy.testimonial.authorTitle': 'Entreprise de plateforme numérique',

// --- CTA ---
'caseStudies.buildDeploy.cta.title': 'Vous souhaitez augmenter l’engagement sans plus de trafic ?',
'caseStudies.buildDeploy.cta.subtitle': "Nous aidons les plateformes numériques à transformer les visiteurs passifs en utilisateurs actifs grâce à une conception UX basée sur la recherche.",
'caseStudies.buildDeploy.cta.primary': 'Planifier une consultation',
'caseStudies.buildDeploy.cta.secondary': 'Voir plus d’études de cas',


// ========================================
// INSIGHT PAGE
// How to Evaluate & Choose the Right Web
// ========================================

// --- Hero ---
'insights.webPartner.hero.category': 'Services informatiques et conseil',
'insights.webPartner.hero.date': 'February 05, 2026',
'insights.webPartner.hero.title': 'How to Evaluate & Choose the Right Web Development Partner for Long-Term Success',
'insights.webPartner.hero.excerpt': 'Choosing the right web development partner is a strategic decision. This guide explains how to evaluate partners beyond short-term delivery and select one that supports long-term growth, scalability, and business outcomes.',
'insights.webPartner.hero.bgAlt': 'Insurance protection background',

// --- Body Intro ---
'insights.webPartner.body.p1': 'In today\'s digital world, a website or app serves more than just an online presence. It helps your business expand, spreads the word about your brand, and is a long-term asset. No matter if you\'re a startup growing quickly, a company that has been around for a while and is going through a digital transformation, or a major company that wants to make things better for customers, it\'s very crucial to choose the correct web development partner.',
'insights.webPartner.body.p2': 'There are many agencies, development companies, and freelancers to choose from, which can make it hard to choose the ideal partner. This lesson teaches you how to pick web development partners carefully, putting long-term value ahead of quick delivery.',

// --- Section 1 ---
'insights.webPartner.section1.title': '1. Why it\'s important to pick the right web development partner',
'insights.webPartner.section1.p1': 'Engineers A web development connection isn\'t just a one-time thing; it could last for years. The right partner will help you make digital tools that help you reach your business goals, finish projects on time and on budget, and grow your platforms as your firm grows. They help get your digital infrastructure ready for things like AI improvements, faster speeds, or new integrations in the future.',
'insights.webPartner.section1.p2': 'More than 85% of digital projects fail because the technology doesn\'t work with the partner or the partner isn\'t right, according to a study. A powerful growth partner is like a teammate. They provide you advice, help you deal with problems, and support your plan as you go.',

// --- Section 2 ---
'insights.webPartner.section2.title': '2. Set the needs and goals for your project',
'insights.webPartner.section2.p1': 'Before you talk to potential partners, you need to be clear. First, you need to know what issue you\'re trying to solve, who you\'re trying to reach, how much money you have to spend, how long you have to do it, and what success metrics are most important to you, like SEO performance, conversions, or speed. Determine whether you require a website, a web application, an e-commerce platform, or system integrations.',
'insights.webPartner.section2.p2': 'Include this in a Project Requirements Document (PRD). It\'s easier to check if offers are valid, negotiations go more smoothly, and suppliers can be compared fairly when there is a clear PRD.',
'insights.webPartner.section2.imageAlt': 'How to Evaluate & Choose the Right Web Development Partner for Long-Term Success',

// --- Section 3 ---
'insights.webPartner.section3.title': '3. What to Look for in a Partner for Web Development',

'insights.webPartner.section3.sub1.title': 'Technical Expertise and Technology Alignment',
'insights.webPartner.section3.sub1.p1': 'Check to see if the partner has worked with the tools, frameworks, CMS platforms, cloud infrastructure, and other technologies that your project needs to run. When technical alignment is strong, the risk goes down, and it is easier to keep things running over time.',

'insights.webPartner.section3.sub2.title': 'Industry Knowledge and Experience',
'insights.webPartner.section3.sub2.p1': 'Partners that have worked in the same field before know the rules, what consumers want, and what problems come up every day. You can make better decisions and get things done faster with this information.',

'insights.webPartner.section3.sub3.title': 'Portfolio and Case Studies',
'insights.webPartner.section3.sub3.p1': 'Look at previous work to see how useful it is, how effectively the UI/UX works, how quickly it responds, and how well it meets business goals. You can think strategically and solve problems, as evidenced by case studies.',

'insights.webPartner.section3.sub4.title': 'Communication and Collaboration Model',
'insights.webPartner.section3.sub4.p1': 'Effective communication prevents misunderstandings and excessive delays. Determine the frequency of updates, the tools utilized, and the presence of a project manager for oversight.',

'insights.webPartner.section3.sub5.title': 'Security, Scalability, and Delivery Process',
'insights.webPartner.section3.sub5.p1': 'You can trust partners who implement organized methods such as Agile, prioritize security and compliance, and plan for growth by monitoring performance and performing regular maintenance.',

'insights.webPartner.section3.sub6.title': 'Transparent Pricing and Long-Term Value',
'insights.webPartner.section3.sub6.p1': 'Instead of looking for the cheapest choice, look for the best value. Look for detailed cost breakdowns, realistic schedules, and choices for long-term help.',

// --- Key Takeaways ---
'insights.webPartner.keyTakeaways.title': 'Key Takeaways',
'insights.webPartner.keyTakeaways.item1': 'Web development partnerships are long-term strategic relationships',
'insights.webPartner.keyTakeaways.item2': 'Clear requirements enable better partner evaluation and alignment',
'insights.webPartner.keyTakeaways.item3': 'Industry experience and technical fit reduce delivery risk',
'insights.webPartner.keyTakeaways.item4': 'Transparency, security, and scalability matter more than short-term cost',

// --- Section 4 ---
'insights.webPartner.section4.title': '4. Final Partner Evaluation Checklist',
'insights.webPartner.section4.p1': 'Before making a final decision, confirm that you have:',
'insights.webPartner.section4.item1': 'Documented clear project goals and requirements',
'insights.webPartner.section4.item2': 'Reviewed portfolios and validated references',
'insights.webPartner.section4.item3': 'Evaluated communication and delivery processes',
'insights.webPartner.section4.item4': 'Confirmed security, compliance, and scalability plans',
'insights.webPartner.section4.item5': 'Reviewed pricing and long-term support models',

// --- Conclusion ---
'insights.webPartner.conclusion.title': 'Conclusion',
'insights.webPartner.conclusion.p1': 'Choosing the right web development partner is a critical business decision that directly impacts your organization’s digital success. By prioritizing alignment, governance, and long-term value, you can build a partnership that supports sustainable growth and continuous improvement.',
'insights.webPartner.conclusion.p2': 'The right partner does more than deliver software - they help you build a resilient digital foundation that evolves with your business.',

// --- Sidebar ---
'insights.webPartner.sidebar.toc.title': 'In This Article',
'insights.webPartner.sidebar.toc.item1': '1. Why Partner Choice Matters',
'insights.webPartner.sidebar.toc.item2': '2. Define Project Needs',
'insights.webPartner.sidebar.toc.item3': '3. What to Look for in a Partner',
'insights.webPartner.sidebar.toc.item4': '4. Final Evaluation Checklist',
'insights.webPartner.sidebar.toc.item5': '5. Conclusion',

'insights.webPartner.sidebar.share.title': 'Share This Article',
'insights.webPartner.sidebar.share.copied': 'Link copied!',


// ========================================
// CASE STUDY PAGE
// How We Deliver High-Performance Web Platforms
// ========================================

// --- Hero ---
'caseStudies.highPerformance.hero.tag1': 'Performance Web',
'caseStudies.highPerformance.hero.tag2': 'Architecture de Plateforme',
'caseStudies.highPerformance.hero.industry': 'Plateforme Digitale',
'caseStudies.highPerformance.hero.title': 'How We Deliver High-Performance Web Platforms',
'caseStudies.highPerformance.hero.subtitle': 'Un aperçu réel de livraison montrant comment une architecture axée sur la performance a amélioré la vitesse,\n                l’engagement et l’évolutivité sans reconstruire l’infrastructure.',
'caseStudies.highPerformance.hero.bgAlt': 'Insurance protection background',

// --- Metrics ---
'caseStudies.highPerformance.metrics.item1.value': '50%↓',
'caseStudies.highPerformance.metrics.item1.label': 'Temps de chargement des pages',
'caseStudies.highPerformance.metrics.item2.value': '40%↓',
'caseStudies.highPerformance.metrics.item2.label': 'Taux de rebond',
'caseStudies.highPerformance.metrics.item3.value': '30%↑',
'caseStudies.highPerformance.metrics.item3.label': 'Engagement des utilisateurs',
'caseStudies.highPerformance.metrics.item4.value': '0',
'caseStudies.highPerformance.metrics.item4.label': 'Reconstructions d’infrastructure',

// --- Context ---
'caseStudies.highPerformance.context.label': 'Le Contexte',
'caseStudies.highPerformance.context.title': 'La plateforme était freinée par la performance',
'caseStudies.highPerformance.context.p1': 'La plateforme n’était pas cassée, mais elle aurait pu être meilleure. Il y avait beaucoup de trafic, de nouvelles fonctionnalités étaient ajoutées en permanence, et les utilisateurs étaient toujours très intéressés. Mais en coulisses, des problèmes de performance détérioraient lentement l’expérience utilisateur et l’évolutivité.',
'caseStudies.highPerformance.context.p2': 'Lorsqu’il y avait beaucoup de personnes sur le site, les pages mettaient longtemps à se charger. Il arrivait que de nouvelles fonctionnalités aggravent la situation. Les développeurs passaient plus de temps à corriger des problèmes qu’à améliorer le produit. Ces problèmes n’étaient pas trop graves, mais ils ralentissaient les choses.',
'caseStudies.highPerformance.context.p3': 'Cette étude de cas montre comment nous avons créé une plateforme en ligne haute performance en changeant la façon dont elle était planifiée, en améliorant la manière dont elle était livrée, et en intégrant la performance à chaque étape du processus.',

// --- Challenge ---
'caseStudies.highPerformance.challenge.label': 'Le Défi',
'caseStudies.highPerformance.challenge.title': 'Le problème n’était pas la technologie - c’était la méthodologie de livraison',
'caseStudies.highPerformance.challenge.p1': 'Le problème principal n’était pas le manque de compétences ou d’outils ; c’était la manière dont la performance était gérée.',
'caseStudies.highPerformance.challenge.p2': 'Certains des plus grands problèmes étaient :',
'caseStudies.highPerformance.challenge.item1': 'L’amélioration de la performance intervient trop tard dans le cycle de vie.',
'caseStudies.highPerformance.challenge.item2': 'Des équipes qui travaillent uniquement sur le front-end et le back-end',
'caseStudies.highPerformance.challenge.item3': 'Il n’y a pas de règles fixes sur la manière dont les choses devraient fonctionner.',
'caseStudies.highPerformance.challenge.item4': 'Tests manuels et correction des problèmes au fur et à mesure',
'caseStudies.highPerformance.challenge.item5': 'Nous étions incapables de voir comment les utilisateurs réels performaient.',
'caseStudies.highPerformance.challenge.p3': 'À chaque nouvelle version, le risque augmentait à mesure que davantage de personnes utilisaient le produit. La plateforme devenait plus grande, mais elle ne s’améliorait pas dans ce qu’elle faisait.',

// --- Approach ---
'caseStudies.highPerformance.approach.label': 'Notre Approche',
'caseStudies.highPerformance.approach.title': 'Concevoir pour la performance dès le premier jour',

// Phase 1
'caseStudies.highPerformance.approach.phase1.number': '1',
'caseStudies.highPerformance.approach.phase1.title': 'Définir des bases de performance',
'caseStudies.highPerformance.approach.phase1.duration': 'Semaines 1–2',
'caseStudies.highPerformance.approach.phase1.p1': 'Nous avons commencé par examiner les niveaux frontend, backend et infrastructure de la plateforme. Nous avons sélectionné des indicateurs clés comme le temps de chargement, la réponse API et les Core Web Vitals comme références afin d’avoir un point de départ clair.',
'caseStudies.highPerformance.approach.phase1.p2': 'Cela a rapidement montré où les problèmes de performance avaient le plus grand impact sur l’entreprise.',

// Phase 2
'caseStudies.highPerformance.approach.phase2.number': '2',
'caseStudies.highPerformance.approach.phase2.title': 'Architecture Web axée sur la performance ',
'caseStudies.highPerformance.approach.phase2.duration': 'Semaines 3–4',
'caseStudies.highPerformance.approach.phase2.p1': 'Nous n’avons pas seulement fait de petits ajustements ; nous avons réécrit des éléments importants du système en utilisant des principes axés sur la performance :',
'caseStudies.highPerformance.approach.phase2.item1': 'Éléments frontend modulables',
'caseStudies.highPerformance.approach.phase2.item2': 'Meilleures réponses API',
'caseStudies.highPerformance.approach.phase2.item3': 'Stratégies de cache efficaces',
'caseStudies.highPerformance.approach.phase2.item4': 'Infrastructure cloud évolutive',
'caseStudies.highPerformance.approach.phase2.p2': 'Cela a garanti que la plateforme web puisse évoluer sans maintenance constante.',

// Phase 3
'caseStudies.highPerformance.approach.phase3.number': '3',
'caseStudies.highPerformance.approach.phase3.title': 'Pipelines de livraison avec contrôles automatisés de performance',
'caseStudies.highPerformance.approach.phase3.duration': 'Semaines 5–7',
'caseStudies.highPerformance.approach.phase3.p1': 'Nous avons intégré les tests de performance directement dans le processus de production et de distribution. Avant la mise en ligne, chaque version était automatiquement vérifiée pour s’assurer qu’elle respectait les normes de performance.',
'caseStudies.highPerformance.approach.phase3.p2': 'Cette procédure a éliminé les régressions et rendu les tests manuels inutiles.',

// Phase 4
'caseStudies.highPerformance.approach.phase4.number': '4',
'caseStudies.highPerformance.approach.phase4.title': 'Surveillance et amélioration en temps réel',
'caseStudies.highPerformance.approach.phase4.duration': 'Semaines 8–10',
'caseStudies.highPerformance.approach.phase4.p1': 'Des tableaux de bord de surveillance en direct ont montré comment les utilisateurs réels performaient. Les équipes pouvaient identifier immédiatement les problèmes, y compris les ralentissements, les pics de trafic ou les erreurs, sans attendre que les utilisateurs se plaignent.',

// --- Results ---
'caseStudies.highPerformance.results.label': 'Les Résultats',
'caseStudies.highPerformance.results.title': 'La performance est devenue un avantage concurrentiel',
'caseStudies.highPerformance.results.card1.before': 'Lent',
'caseStudies.highPerformance.results.card1.after': '50%↓',
'caseStudies.highPerformance.results.card1.label': 'Chargement des pages plus rapide',
'caseStudies.highPerformance.results.card2.before': 'Élevé',
'caseStudies.highPerformance.results.card2.after': '40%↓',
'caseStudies.highPerformance.results.card2.label': 'Taux de rebond réduit',
'caseStudies.highPerformance.results.card3.before': 'Faible',
'caseStudies.highPerformance.results.card3.after': '30%↑',
'caseStudies.highPerformance.results.card3.label': 'Engagement utilisateur augmenté',
'caseStudies.highPerformance.results.card4.before': 'Risque',
'caseStudies.highPerformance.results.card4.after': 'Stable',
'caseStudies.highPerformance.results.card4.label': 'Versions plus rapides avec moins de retours en arrière',

// --- Testimonial ---
'caseStudies.highPerformance.testimonial.quote': 'Our users now explore, interact, and complete actions instead of leaving after a few seconds. The redesign completely changed how people engage with our platform.',
'caseStudies.highPerformance.testimonial.authorName': 'Head of Product',
'caseStudies.highPerformance.testimonial.authorTitle': 'Digital Platform Company',

// --- CTA ---
'caseStudies.highPerformance.cta.title': 'Want to Increase Engagement Without More Traffic?',
'caseStudies.highPerformance.cta.subtitle': 'We help digital platforms turn passive visitors into active users through research-driven UX design.',
'caseStudies.highPerformance.cta.primary': 'Schedule a Consultation',
'caseStudies.highPerformance.cta.secondary': 'View More Case Studies',


// ========================================
// INSIGHT PAGE
// The Connection Between Web Architecture, SEO & Digital Growth
// ========================================

// --- Hero ---
'insights.webArchitecture.hero.category': 'Architecture Web & SEO',
'insights.webArchitecture.hero.date': '06 février 2026',
'insights.webArchitecture.hero.title': 'Le Lien Entre l’Architecture Web, le SEO et la Croissance Digitale',
'insights.webArchitecture.hero.excerpt': 'L’architecture web constitue la base technique du SEO et de la croissance digitale à long terme. Cet article explique comment la structure, la performance et l’évolutivité influencent directement la visibilité dans les moteurs de recherche, l’expérience utilisateur et les résultats commerciaux.',
'insights.webArchitecture.hero.bgAlt': 'Arrière-plan de protection d’assurance',

// --- Body ---
'insights.webArchitecture.body.p1': 'Dans le monde numérique actuel, un site web est plus qu’une simple belle image. C’est également une base technique qui influence la facilité avec laquelle il peut être trouvé dans les moteurs de recherche, la qualité de son fonctionnement pour les utilisateurs et la performance de l’entreprise à long terme. Au cœur de cette base se trouve l’architecture web. La manière dont les moteurs de recherche analysent, indexent et classent votre site web est extrêmement importante. L’architecture web et le SEO travaillent ensemble pour construire un moteur solide qui aide à réussir en ligne sur le long terme.',

// Section 1
'insights.webArchitecture.section1.title': '1. Que signifie avoir une architecture web ?',
'insights.webArchitecture.section1.p1': 'La séquence des pages, la structure des URL, le maillage interne, la navigation et la configuration technologique font tous partie de l’architecture web. Une structure soigneusement pensée permet aux visiteurs et aux moteurs de recherche de comprendre et d’utiliser facilement le site.',
'insights.webArchitecture.section1.p2': 'Lorsque l’architecture est mauvaise, le site fonctionne lentement, les liens échouent, le contenu se duplique et l’exploration devient difficile. Tous ces facteurs nuisent au SEO et à l’utilisation du site par les visiteurs.',

// Section 2
'insights.webArchitecture.section2.title': '2. Comment la structure d’un site influence le SEO',
'insights.webArchitecture.section2.p1': 'Les moteurs de recherche exigent que votre site web ait une structure claire. Lorsque la conception est claire et logique, les robots des moteurs de recherche peuvent explorer et indexer le contenu correctement. Vous pouvez répartir l’autorité des liens en utilisant efficacement les catégories, en assurant la clarté de vos URL et en reliant correctement les pages pertinentes.',
'insights.webArchitecture.section2.p2': 'La vitesse du site et son bon fonctionnement sur mobile sont deux facteurs architecturaux très importants qui influencent le classement. Un code léger, des ressources efficaces et une infrastructure évolutive contribuent aux temps de chargement et réduisent le taux de rebond. Tous ces éléments ont un impact sur les classements dans les moteurs de recherche.',
'insights.webArchitecture.section2.p3': 'Une navigation structurée aide également les utilisateurs à trouver les informations plus rapidement, ce qui les incite à rester plus longtemps sur le site et réduit le pogo-sticking. Ces deux éléments sont bénéfiques pour le SEO.',

// Section 3
'insights.webArchitecture.section3.title': '3. Comment le SEO soutient la croissance digitale',
'insights.webArchitecture.section3.p1': 'Le SEO ne consiste pas uniquement à obtenir de bons classements ; il s’agit également d’attirer un trafic susceptible de se transformer en ventes. Lorsque la conception web suit les meilleures pratiques SEO, les entreprises bénéficient d’un trafic organique accru, d’une meilleure expérience utilisateur et de taux de conversion plus élevés.',
'insights.webArchitecture.section3.p2': 'Une conception évolutive permet aux entreprises d’ajouter davantage de contenu, de services et de marchés sans compromettre leur positionnement dans les moteurs de recherche. Ce niveau de flexibilité est essentiel pour une croissance digitale à long terme.',

// Section 4
'insights.webArchitecture.section4.title': '4. L’architecture web comme base pour évoluer',
'insights.webArchitecture.section4.p1': 'Les entreprises qui mettent en place une architecture web efficace dès le départ évitent des corrections coûteuses par la suite. Une conception optimisée pour le SEO soutient le marketing de contenu, facilite la découverte du site par les utilisateurs et renforce la crédibilité de l’entreprise. À mesure que le trafic organique augmente, le besoin en publicité payante diminue, ce qui conduit à un meilleur retour sur investissement au fil du temps.',
'insights.webArchitecture.section4.p2': 'À l’inverse, négliger la conception de votre architecture peut freiner la croissance, même si vous disposez d’un excellent contenu et d’un bon marketing.',

// --- Key Takeaways ---
'insights.webArchitecture.takeaways.title': 'Points Clés',
'insights.webArchitecture.takeaways.item1': 'L’architecture web est la base de la performance SEO',
'insights.webArchitecture.takeaways.item2': 'Une structure claire améliore l’exploration et l’indexation',
'insights.webArchitecture.takeaways.item3': 'La performance et l’optimisation mobile influencent directement les classements',
'insights.webArchitecture.takeaways.item4': 'Une architecture évolutive soutient la croissance digitale à long terme',

// --- Conclusion ---
'insights.webArchitecture.conclusion.title': 'Conclusion',
'insights.webArchitecture.conclusion.p1': 'L’architecture web, le SEO et la croissance digitale sont étroitement liés. Un site bien structuré facilite la découverte de votre contenu par les moteurs de recherche, améliore l’expérience utilisateur et offre à votre entreprise une plateforme capable d’évoluer avec elle. En veillant à ce que l’architecture du site et la stratégie SEO fonctionnent ensemble, les entreprises peuvent bâtir une base digitale solide qui leur permet de rester visibles, d’engager les clients et de réussir sur le long terme.',

// --- Sidebar ---
'insights.webArchitecture.sidebar.tocTitle': 'Dans Cet Article',
'insights.webArchitecture.sidebar.item1': '1. Que signifie avoir une architecture web ?',
'insights.webArchitecture.sidebar.item2': '2. Comment la structure influence le SEO',
'insights.webArchitecture.sidebar.item3': '3. Comment le SEO soutient la croissance digitale',
'insights.webArchitecture.sidebar.item4': '4. Architecture pour évoluer',
'insights.webArchitecture.sidebar.item5': '5. Conclusion',
'insights.webArchitecture.sidebar.shareTitle': 'Partager Cet Article',
'insights.webArchitecture.sidebar.copyFeedback': 'Lien copié !',


// ========================================
// CASE STUDY PAGE
// Automating Lead Follow-Ups for a Plumbing Business
// ========================================

// --- Hero ---
'caseStudies.plumbing.hero.tag1': 'Automatisation',
'caseStudies.plumbing.hero.tag2': 'Gestion des Leads',
'caseStudies.plumbing.hero.industry': 'Services Locaux',
'caseStudies.plumbing.hero.title': 'Automatisation du Suivi des Leads pour une Entreprise de Plomberie',
'caseStudies.plumbing.hero.subtitle': 'Comment une entreprise locale de plomberie a augmenté ses réservations et ses revenus en automatisant le suivi des leads sans augmenter les dépenses publicitaires ni les effectifs.',
'caseStudies.plumbing.hero.bgAlt': 'Arrière-plan de protection d’assurance',

// --- Metrics ---
'caseStudies.plumbing.metrics.item1.value': '80%↓',
'caseStudies.plumbing.metrics.item1.label': 'Temps de Réponse',
'caseStudies.plumbing.metrics.item2.value': '47%↑',
'caseStudies.plumbing.metrics.item2.label': 'Interventions Réservées',
'caseStudies.plumbing.metrics.item3.value': '35%↑',
'caseStudies.plumbing.metrics.item3.label': 'Revenus Mensuels',
'caseStudies.plumbing.metrics.item4.value': '0',
'caseStudies.plumbing.metrics.item4.label': 'Leads Manqués',

// --- Context ---
'caseStudies.plumbing.context.label': 'Le Contexte',
'caseStudies.plumbing.context.title': 'Volume élevé de leads, faible suivi',
'caseStudies.plumbing.context.p1': 'Une entreprise de plomberie de taille moyenne desservant une zone métropolitaine locale générait un flux constant de leads provenant de son site web, de Google Ads, des demandes de service d’urgence et des appels téléphoniques.',
'caseStudies.plumbing.context.p2': 'La demande était forte, mais les réservations étaient irrégulières. Le problème n’était pas le marketing - c’était le suivi lent et peu fiable des leads qui poussait les clients potentiels vers les concurrents.',
'caseStudies.plumbing.context.p3': 'Cette étude de cas explique comment l’automatisation du suivi des leads a transformé les délais de réponse, augmenté les conversions et permis une croissance des revenus sans dépenses marketing supplémentaires.',

// --- Challenge ---
'caseStudies.plumbing.challenge.label': 'Le Défi',
'caseStudies.plumbing.challenge.title': 'Le suivi manuel coûtait des revenus',
'caseStudies.plumbing.challenge.p1': 'Avant l’automatisation, une petite équipe administrative traitait manuellement chaque lead. Cette approche créait une pression opérationnelle et des opportunités perdues.',
'caseStudies.plumbing.challenge.item1': 'Les leads étaient contactés des heures plus tard ou le lendemain',
'caseStudies.plumbing.challenge.item2': 'Les leads en dehors des heures de travail et pendant les périodes chargées étaient complètement manqués',
'caseStudies.plumbing.challenge.item3': 'Messages incohérents et absence de suivi structuré',
'caseStudies.plumbing.challenge.item4': 'Les leads choisissaient souvent des concurrents qui répondaient plus rapidement',
'caseStudies.plumbing.challenge.p2': 'Dans les situations d’urgence en plomberie, la rapidité détermine la confiance. Les réponses tardives se traduisaient directement par des interventions perdues.',

// --- Approach ---
'caseStudies.plumbing.approach.label': 'Notre Approche',
'caseStudies.plumbing.approach.title': 'Un suivi automatisé, rapide et centré sur l’humain',

// Phase 1
'caseStudies.plumbing.approach.phase1.number': '1',
'caseStudies.plumbing.approach.phase1.title': 'Capture Centralisée des Leads',
'caseStudies.plumbing.approach.phase1.duration': 'Semaine 1',
'caseStudies.plumbing.approach.phase1.p1': 'Tous les leads provenant des formulaires du site web, des publicités, des demandes d’urgence et des appels étaient dirigés vers un CRM unique. Cela garantissait visibilité, responsabilité et aucune perte de lead.',

// Phase 2
'caseStudies.plumbing.approach.phase2.number': '2',
'caseStudies.plumbing.approach.phase2.title': 'Réponses Automatisées Immédiates',
'caseStudies.plumbing.approach.phase2.duration': 'Semaine 2',
'caseStudies.plumbing.approach.phase2.p1': 'Dans les 60 secondes suivant l’envoi d’un formulaire ou d’une demande, les prospects recevaient :',
'caseStudies.plumbing.approach.phase2.item1': 'Un message SMS personnalisé confirmant la réception de leur demande',
'caseStudies.plumbing.approach.phase2.item2': 'Un e-mail contenant des informations sur le service et les prochaines étapes',
'caseStudies.plumbing.approach.phase2.item3': 'Cette réponse rapide donnait aux clients le sentiment que l’aide était en route.',

// Phase 3
'caseStudies.plumbing.approach.phase3.number': '3',
'caseStudies.plumbing.approach.phase3.title': 'Séquences de Suivi Intelligentes',
'caseStudies.plumbing.approach.phase3.duration': 'Semaine 3',
'caseStudies.plumbing.approach.phase3.p1': 'Si un lead ne réservait pas immédiatement, le système déclenchait des relances programmées après deux heures, un jour et trois jours - maintenant l’élan sans être intrusif.',

// Phase 4
'caseStudies.plumbing.approach.phase4.number': '4',
'caseStudies.plumbing.approach.phase4.title': 'Planification & Alertes d’Équipe',
'caseStudies.plumbing.approach.phase4.duration': 'Semaine 4',
'caseStudies.plumbing.approach.phase4.p1': 'Les leads pouvaient réserver des rendez-vous instantanément via des liens de planification, tandis que le personnel administratif recevait des alertes en temps réel concernant les réponses, les réservations et les mots-clés à forte intention.',

// --- Results ---
'caseStudies.plumbing.results.label': 'Les Résultats',
'caseStudies.plumbing.results.title': 'L’automatisation a généré une croissance mesurable',
'caseStudies.plumbing.results.card1.before': 'Heures',
'caseStudies.plumbing.results.card1.after': '< 1 min',
'caseStudies.plumbing.results.card1.label': 'Temps de réponse réduit',
'caseStudies.plumbing.results.card2.before': 'Faible',
'caseStudies.plumbing.results.card2.after': '47%↑',
'caseStudies.plumbing.results.card2.label': 'Plus de leads convertis en interventions',
'caseStudies.plumbing.results.card3.before': 'Stable',
'caseStudies.plumbing.results.card3.after': '35%↑',
'caseStudies.plumbing.results.card3.label': 'Croissance mensuelle des revenus',
'caseStudies.plumbing.results.card4.before': 'Manuel',
'caseStudies.plumbing.results.card4.after': 'Automatisé',
'caseStudies.plumbing.results.card4.label': 'Zéro lead manqué',

// --- Testimonial ---
'caseStudies.plumbing.testimonial.quote': 'Nos utilisateurs explorent désormais, interagissent et accomplissent des actions au lieu de partir après quelques secondes. La refonte a complètement changé la façon dont les personnes interagissent avec notre plateforme.',
'caseStudies.plumbing.testimonial.authorName': 'Responsable Produit',
'caseStudies.plumbing.testimonial.authorTitle': 'Entreprise de Plateforme Digitale',

// --- CTA ---
'caseStudies.plumbing.cta.title': 'Vous souhaitez augmenter l’engagement sans plus de trafic ?',
'caseStudies.plumbing.cta.subtitle': 'Nous aidons les plateformes digitales à transformer des visiteurs passifs en utilisateurs actifs grâce à un design UX basé sur la recherche.',
'caseStudies.plumbing.cta.primary': 'Planifier une Consultation',
'caseStudies.plumbing.cta.secondary': 'Voir Plus d’Études de Cas',

// ========================================
// CONTACT PAGE
// Book a Discovery Call
// ========================================

// --- Hero ---
'contact.discovery.hero.title': 'Réserver un Appel Découverte',
'contact.discovery.hero.subtitle': 'Une conversation structurée sur vos opérations — sans argumentaire commercial. Choisissez un créneau qui vous convient.',
'contact.discovery.hero.bgAlt': 'Arrière-plan de protection d’assurance',

// ========================================
// INSIGHTS ARTICLE
// AI Adoption Roadmap (Full Literal Extraction)
// ========================================

// --- Hero ---
'insights.aiAdoption.hero.image.alt': 'Arrière-plan de protection d’assurance',
'insights.aiAdoption.hero.category': 'Stratégie d’IA',
'insights.aiAdoption.hero.date': '26 février 2026',
'insights.aiAdoption.hero.title': 'Feuille de route pour l’adoption de l’IA dans les entreprises de taille moyenne',
'insights.aiAdoption.hero.excerpt': 'L’IA n’est plus réservée aux géants de la technologie. Les entreprises de taille moyenne peuvent désormais déployer des systèmes d’IA gouvernés et évolutifs - à condition de suivre une feuille de route structurée alignée sur les résultats commerciaux.',

// --- Body Intro ---
'insights.aiAdoption.body.intro.p1': 'Les entreprises technologiques n’ont plus le monopole de l’intelligence artificielle. Aujourd’hui, les entreprises de taille moyenne peuvent utiliser des outils d’IA puissants pour optimiser leurs opérations, réduire leurs dépenses et trouver de nouvelles sources de revenus. Mais le succès de l’adoption de l’IA ne doit rien au hasard. Il nécessite une feuille de route bien planifiée qui relie la technologie à la stratégie commerciale, établit des bases de données solides et se développe de manière intelligente.',
'insights.aiAdoption.body.intro.p2': 'Voici un guide réaliste, étape par étape, pour aider votre entreprise de taille moyenne à se lancer dans l’IA.',

// --- Section 1 ---
'insights.aiAdoption.body.businessGoals.title': '1. Définissez des objectifs commerciaux clairs',
'insights.aiAdoption.body.businessGoals.p1': 'L’IA ne devrait jamais commencer par : "Essayons quelque chose de cool". La première question doit être : "Quel problème essayons-nous de résoudre ?"',
'insights.aiAdoption.body.businessGoals.p2': 'Identifiez les domaines qui auront un impact majeur, tels que :',
'insights.aiAdoption.body.businessGoals.item1': 'Accélérer le temps de réponse du service client',
'insights.aiAdoption.body.businessGoals.item2': 'Améliorer l’efficacité opérationnelle',
'insights.aiAdoption.body.businessGoals.item3': 'Accroître la précision des prévisions de ventes',
'insights.aiAdoption.body.businessGoals.item4': 'Optimiser l’allocation des ressources',
'insights.aiAdoption.body.businessGoals.p3': 'Concentrez-vous sur les cas d’usage ayant un effet direct sur les revenus, les économies ou la satisfaction client. Il est plus facile de quantifier la performance lorsque l’objectif commercial est clair.',

// --- Section 2 ---
'insights.aiAdoption.body.readiness.title': '2. Évaluez votre niveau de préparation à l’IA',
'insights.aiAdoption.body.readiness.p1': 'Avant d’acheter des outils d’IA, analysez vos capacités actuelles. Les recherches du MIT CISR montrent que de nombreuses entreprises rencontrent des difficultés parce qu’elles déploient l’IA sans connaître leur niveau de maturité.',
'insights.aiAdoption.body.readiness.p2': 'Éléments clés à examiner :',
'insights.aiAdoption.body.readiness.item1': 'Qualité des données : Les données sont-elles propres, structurées et fiables ?',
'insights.aiAdoption.body.readiness.item2': 'Infrastructure : Vos systèmes peuvent-ils supporter des charges de travail d’IA évolutives ?',
'insights.aiAdoption.body.readiness.item3': 'Talents et compétences : Vos équipes internes possèdent-elles une culture des données et des compétences en supervision de l’IA ?',
'insights.aiAdoption.body.readiness.item4': 'Gouvernance : Les cadres de conformité, de confidentialité et de sécurité sont-ils établis ?',
'insights.aiAdoption.body.readiness.p3': 'Cette évaluation permet d’éliminer les erreurs coûteuses et de fixer des objectifs raisonnables.',

// --- Image ---
'insights.aiAdoption.body.image.alt': 'Feuille de route pour l’adoption de l’IA pour les entreprises de taille moyenne',

// --- Section 3 ---
'insights.aiAdoption.body.dataFoundation.title': '3. Bâtissez une base de données solide',
'insights.aiAdoption.body.dataFoundation.p1': 'La donnée est le carburant de l’IA. Vos projets d’IA s’arrêteront si vos données sont dispersées entre les départements ou bloquées dans des systèmes obsolètes.',
'insights.aiAdoption.body.dataFoundation.p2': 'Les entreprises de taille moyenne devraient prioriser les points suivants :',
'insights.aiAdoption.body.dataFoundation.item1': 'Stockage centralisé des données, comme les lacs de données (data lakes) ou les plateformes unifiées',
'insights.aiAdoption.body.dataFoundation.item2': 'Nettoyage et standardisation des données',
'insights.aiAdoption.body.dataFoundation.item3': 'Politiques claires de propriété et de gouvernance des données',
'insights.aiAdoption.body.dataFoundation.p3': 'Des plateformes comme Databricks permettent aux entreprises de regrouper données et analyses en un seul endroit, ce qui réduit les silos et facilite la collaboration.',
'insights.aiAdoption.body.dataFoundation.p4': 'Même les meilleurs modèles d’IA ne fonctionneront pas s’ils n’ont pas accès à des données précises.',

// --- Section 4 ---
'insights.aiAdoption.body.pilots.title': '4. Commencez par des projets pilotes à fort impact',
'insights.aiAdoption.body.pilots.p1': 'Au lieu de vouloir transformer toute l’entreprise d’un coup, commencez par de petits projets pilotes.',
'insights.aiAdoption.body.pilots.p2': 'Les caractéristiques d’un bon projet pilote sont :',
'insights.aiAdoption.body.pilots.item1': 'Un périmètre clairement défini',
'insights.aiAdoption.body.pilots.item2': 'Des indicateurs de succès mesurables',
'insights.aiAdoption.body.pilots.item3': 'Un parrainage solide de la part de la direction',
'insights.aiAdoption.body.pilots.item4': 'Des mécanismes de suivi du ROI définis',
'insights.aiAdoption.body.pilots.p3': 'Par exemple, l’utilisation d’un chatbot IA pour le support client ou l’analyse prédictive pour la gestion des stocks.',
'insights.aiAdoption.body.pilots.p4': 'IBM et d’autres soulignent l’importance de commencer petit tout en prévoyant la croissance dès le départ. Les premiers succès renforcent la confiance interne et justifient les investissements futurs.',

// --- Section 5 ---
'insights.aiAdoption.body.governance.title': '5. Établissez une gestion des risques et une gouvernance',
'insights.aiAdoption.body.governance.p1': 'La gouvernance devient cruciale à mesure que les systèmes d’IA prennent des décisions.',
'insights.aiAdoption.body.governance.p2': 'Les entreprises de taille moyenne doivent établir des règles concernant :',
'insights.aiAdoption.body.governance.item1': 'La confidentialité des données et la conformité réglementaire',
'insights.aiAdoption.body.governance.item2': 'La transparence et l’explicabilité des modèles',
'insights.aiAdoption.body.governance.item3': 'La détection des biais et les normes d’utilisation éthique',
'insights.aiAdoption.body.governance.item4': 'Le suivi des performances et l’auditabilité',
'insights.aiAdoption.body.governance.p3': 'Les organismes de conseil comme Gartner recommandent d’équilibrer l’innovation avec la gestion des risques pour éviter les problèmes réglementaires et de réputation.',
'insights.aiAdoption.body.governance.p4': 'Une gouvernance solide génère de la confiance auprès des clients, des employés et des parties prenantes.',

// --- Section 6 ---
'insights.aiAdoption.body.talent.title': '6. Créez une culture de l’IA et développez les talents',
'insights.aiAdoption.body.talent.p1': 'La transformation par l’IA est autant culturelle que technique.',
'insights.aiAdoption.body.talent.p2': 'Les organisations devraient :',
'insights.aiAdoption.body.talent.item1': 'Former le personnel à la culture des données et aux bases de l’IA',
'insights.aiAdoption.body.talent.item2': 'Encourager la collaboration interfonctionnelle',
'insights.aiAdoption.body.talent.item3': 'Faire appel à des experts externes pour les besoins spécialisés',
'insights.aiAdoption.body.talent.item4': 'Communiquer sur la façon dont l’IA améliore les rôles plutôt que de les remplacer',
'insights.aiAdoption.body.talent.p3': 'L’adoption s’accélère lorsque les utilisateurs métier - et pas seulement les équipes informatiques - sont habilités à utiliser les outils d’IA de manière responsable.',

// --- Section 7 ---
'insights.aiAdoption.body.workflow.title': '7. Intégrez l’IA dans les flux de travail principaux',
'insights.aiAdoption.body.workflow.p1': 'L’IA apporte de la valeur lorsqu’elle est intégrée directement dans les systèmes opérationnels, et non isolée sur un tableau de bord.',
'insights.aiAdoption.body.workflow.p2': 'Cela inclut :',
'insights.aiAdoption.body.workflow.item1': 'L’intégration des résultats de l’IA dans le CRM, l’ERP et les systèmes financiers',
'insights.aiAdoption.body.workflow.item2': 'L’automatisation des décisions de routine avec des contrôles de supervision humaine',
'insights.aiAdoption.body.workflow.item3': 'L’ajustement continu des modèles basé sur les retours opérationnels',
'insights.aiAdoption.body.workflow.p3': 'L’IA doit soutenir la prise de décision en temps réel au sein des flux de travail quotidiens.',

// --- Section 8 ---
'insights.aiAdoption.body.scaling.title': '8. Passez à l’échelle avec une architecture structurée',
'insights.aiAdoption.body.scaling.p1': 'Une fois que les projets pilotes ont démontré un impact mesurable, le passage à l’échelle doit être délibéré et non fragmenté.',
'insights.aiAdoption.body.scaling.p2': 'Le passage à l’échelle nécessite :',
'insights.aiAdoption.body.scaling.item1': 'Des plateformes standardisées et des environnements de données partagés',
'insights.aiAdoption.body.scaling.item2': 'Une supervision centralisée de la gouvernance',
'insights.aiAdoption.body.scaling.item3': 'De la documentation et des guides opérationnels',
'insights.aiAdoption.body.scaling.item4': 'Une mesure continue des performances',
'insights.aiAdoption.body.scaling.p3': 'Évitez les silos d’IA par département. Construisez un écosystème unifié capable d’une fiabilité opérationnelle à long terme.',

// --- Section 9 ---
'insights.aiAdoption.body.continuous.title': '9. Mesurez et améliorez en continu',
'insights.aiAdoption.body.continuous.p1': 'L’adoption de l’IA n’est pas une mise en œuvre ponctuelle, c’est une capacité en constante évolution.',
'insights.aiAdoption.body.continuous.p2': 'Les entreprises doivent surveiller :',
'insights.aiAdoption.body.continuous.item1': 'Le retour sur investissement (ROI)',
'insights.aiAdoption.body.continuous.item2': 'Les gains d’efficacité opérationnelle',
'insights.aiAdoption.body.continuous.item3': 'Les indicateurs de satisfaction client',
'insights.aiAdoption.body.continuous.item4': 'La précision et la stabilité des modèles',
'insights.aiAdoption.body.continuous.item5': 'Les indicateurs de conformité et d’audit',
'insights.aiAdoption.body.continuous.p3': 'Un ajustement continu garantit que les systèmes d’IA restent alignés sur l’évolution des objectifs commerciaux.',

// --- Key Takeaways ---
'insights.aiAdoption.body.takeaways.title': 'Points clés à retenir',
'insights.aiAdoption.body.takeaways.item1': 'L’adoption de l’IA doit commencer par des objectifs commerciaux mesurables',
'insights.aiAdoption.body.takeaways.item2': 'La préparation des données détermine la fiabilité opérationnelle',
'insights.aiAdoption.body.takeaways.item3': 'La gouvernance doit être intégrée dès le premier jour',
'insights.aiAdoption.body.takeaways.item4': 'Les projets pilotes valident le passage à l’échelle de l’entreprise',
'insights.aiAdoption.body.takeaways.item5': 'La mesure continue garantit un ROI durable',

// --- Conclusion ---
'insights.aiAdoption.body.conclusion.title': 'Conclusion',
'insights.aiAdoption.body.conclusion.p1': 'Pour les entreprises de taille moyenne, l’adoption de l’IA représente à la fois une opportunité stratégique et un impératif opérationnel.',
'insights.aiAdoption.body.conclusion.p2': 'Les organisations qui réussissent :',
'insights.aiAdoption.body.conclusion.item1': 'Alignent l’IA sur des objectifs commerciaux clairs',
'insights.aiAdoption.body.conclusion.item2': 'Établissent des bases de données solides',
'insights.aiAdoption.body.conclusion.item3': 'Lancent des projets pilotes contrôlés à fort impact',
'insights.aiAdoption.body.conclusion.item4': 'Intègrent tôt la gouvernance et la conformité',
'insights.aiAdoption.body.conclusion.item5': 'Passent à l’échelle grâce à une architecture unifiée',
'insights.aiAdoption.body.conclusion.item6': 'S’engagent dans une optimisation continue',
'insights.aiAdoption.body.conclusion.p3': 'L’IA ne consiste pas à suivre les modes. Il s’agit de bâtir des systèmes gouvernés qui convertissent les données de l’entreprise en décisions fiables et mesurables.',
'insights.aiAdoption.body.conclusion.p4': 'Commencez délibérément. Bâtissez des bases solides. Passez à l’échelle avec détermination.',

// --- Sidebar ---
'insights.aiAdoption.sidebar.tocTitle': 'Dans cet article',
'insights.aiAdoption.sidebar.toc.item1': '1. Définir des objectifs clairs',
'insights.aiAdoption.sidebar.toc.item2': '2. Évaluer la préparation de l’organisation',
'insights.aiAdoption.sidebar.toc.item3': '3. Bâtir une base de données solide',
'insights.aiAdoption.sidebar.toc.item4': '4. Lancer des projets pilotes à fort impact',
'insights.aiAdoption.sidebar.toc.item5': '5. Intégrer la gouvernance et les risques',
'insights.aiAdoption.sidebar.toc.item6': '6. Développer les talents et la culture IA',
'insights.aiAdoption.sidebar.toc.item7': '7. Intégrer l’IA aux flux de travail',
'insights.aiAdoption.sidebar.toc.item8': '8. Passer à l’échelle via l’architecture',
'insights.aiAdoption.sidebar.toc.item9': '9. Mesurer et améliorer en continu',
'insights.aiAdoption.sidebar.toc.item10': '10. Conclusion',

'insights.aiAdoption.sidebar.shareTitle': 'Partager cet article',
'insights.aiAdoption.sidebar.share.linkedin': 'Partager sur LinkedIn',
'insights.aiAdoption.sidebar.share.twitter': 'Partager sur Twitter',
'insights.aiAdoption.sidebar.share.facebook': 'Partager sur Facebook',
'insights.aiAdoption.sidebar.share.copy': 'Copier le lien',
'insights.aiAdoption.sidebar.copyFeedback': 'Lien copié !',


// ========================================
// INSIGHTS ARTICLE
// From Data to Decisions
// ========================================

// --- Hero ---
'insights.fromDataToDecisions.hero.image.alt': 'Arrière-plan de protection d’assurance',
'insights.fromDataToDecisions.hero.category': 'Stratégie d’IA et Architecture d’Entreprise',
'insights.fromDataToDecisions.hero.date': '24 février 2026',
'insights.fromDataToDecisions.hero.title': 'Des données aux décisions : Construire un écosystème d’IA prêt pour l’entreprise',
'insights.fromDataToDecisions.hero.excerpt': 'En 2026, l’IA d’entreprise n’est plus une question d’expérimentation. Il s’agit de bâtir des écosystèmes évolutifs et gouvernés qui transforment les données en décisions commerciales fiables.',

// --- Body Intro ---
'insights.fromDataToDecisions.body.intro.p1': 'En 2026, construire un écosystème d’IA prêt pour l’entreprise ne consiste pas à tester les derniers outils à la mode. Il s’agit de créer un système capable de croître, fiable et accessible à tous dans votre entreprise, tout en soutenant vos objectifs commerciaux. Il y a une différence majeure entre tester quelques programmes d’IA et faire de l’IA une partie intégrante du fonctionnement quotidien de votre entreprise.',

// --- Section 1 ---
'insights.fromDataToDecisions.body.enterpriseMeaning.title': '1. Ce que signifie réellement "l’IA prête pour l’entreprise"',
'insights.fromDataToDecisions.body.enterpriseMeaning.p1': 'Pensez à la différence entre un prototype de voiture et une voiture de série. Le prototype peut être magnifique, mais la voiture de série a subi de nombreux tests, est construite pour durer et conçue pour un usage quotidien. Le modèle de série, c’est l’IA prête pour les affaires.',
'insights.fromDataToDecisions.body.enterpriseMeaning.p2': 'Elle doit :',
'insights.fromDataToDecisions.body.enterpriseMeaning.item1': 'Évoluer à mesure que le nombre d’utilisateurs et de données augmente.',
'insights.fromDataToDecisions.body.enterpriseMeaning.item2': 'S’intégrer aux systèmes actuels tels que le CRM, l’ERP et les plateformes de chaîne d’approvisionnement.',
'insights.fromDataToDecisions.body.enterpriseMeaning.item3': 'Être honnête, disposer de données précises et prendre des décisions explicables.',
'insights.fromDataToDecisions.body.enterpriseMeaning.item4': 'Tenir compte de son environnement et de vos flux de travail spécifiques.',
'insights.fromDataToDecisions.body.enterpriseMeaning.p3': 'Databricks et d’autres entreprises soulignent que l’IA d’entreprise ne consiste pas seulement à mener des essais isolés. Elle nécessite un environnement unifié où les données circulent librement et où l’automatisation intelligente est un élément normal de l’activité.',

// --- Section 2 ---
'insights.fromDataToDecisions.body.infrastructure.title': '2. Pourquoi l’infrastructure est importante',
'insights.fromDataToDecisions.body.infrastructure.p1': 'Il est facile de brancher un outil d’IA et de penser qu’il va fonctionner. Mais c’est l’infrastructure qui fait la différence entre des tests à court terme et un changement durable.',
'insights.fromDataToDecisions.body.infrastructure.p2': 'Sans les bonnes fondations :',
'insights.fromDataToDecisions.body.infrastructure.item1': 'Chaque département crée des solutions d’IA qui ne communiquent pas entre elles.',
'insights.fromDataToDecisions.body.infrastructure.item2': 'Les données restent dispersées sur différentes plateformes.',
'insights.fromDataToDecisions.body.infrastructure.item3': 'L’automatisation est bloquée par des processus manuels.',
'insights.fromDataToDecisions.body.infrastructure.item4': 'Le passage à l’échelle devient incontrôlable.',
'insights.fromDataToDecisions.body.infrastructure.item5': 'Les risques de sécurité et de conformité augmentent.',
'insights.fromDataToDecisions.body.infrastructure.p3': 'Une infrastructure solide permet la fusion des données, c’est-à-dire le regroupement des données clients, ventes et produits en une base unique. Elle facilite également la prise de décision autonome, permettant à l’IA de gérer seule des tâches comme les approbations de routine, l’orientation des clients ou l’optimisation des stocks.',
'insights.fromDataToDecisions.body.infrastructure.p4': 'L’infrastructure garantit également le respect des règles et de la gouvernance dans les secteurs réglementés. Vous ne pourrez pas sortir du mode pilote si vous sautez cette étape.',
'insights.fromDataToDecisions.body.infrastructure.image.alt': 'Pourquoi la stratégie d’IA échoue sans des fondations informatiques solides',

// --- Section 3 ---
'insights.fromDataToDecisions.body.maturity.title': '3. Les quatre niveaux de maturité de l’IA',
'insights.fromDataToDecisions.body.maturity.item1': 'Adoption initiale : Pilotes limités avec un impact opérationnel minimal',
'insights.fromDataToDecisions.body.maturity.item2': 'Croissance fragmentée : Expérimentation au niveau départemental',
'insights.fromDataToDecisions.body.maturity.item3': 'Intégration d’entreprise : Plateformes unifiées et gouvernance',
'insights.fromDataToDecisions.body.maturity.item4': 'IA transformationnelle : L’IA intégrée aux processus compétitifs de base',
'insights.fromDataToDecisions.body.maturity.p1': 'L’IA d’entreprise transformatrice consiste à intégrer l’IA dans les opérations clés pour vous donner un avantage sur vos concurrents.',
'insights.fromDataToDecisions.body.maturity.p2': 'La plupart des entreprises se situent aujourd’hui entre les étapes deux et trois. Ce cadre vous montre comment croître de manière planifiée plutôt que désordonnée.',

// --- Section 4 ---
'insights.fromDataToDecisions.body.dataReadiness.title': '4. Qu’est-ce qui rend les données prêtes pour l’IA ?',
'insights.fromDataToDecisions.body.dataReadiness.p1': 'Toutes les données ne sont pas exploitables par l’IA. Les données prêtes pour l’IA doivent répondre à trois critères :',
'insights.fromDataToDecisions.body.dataReadiness.item1': 'Qualité : Données propres, cohérentes et validées',
'insights.fromDataToDecisions.body.dataReadiness.item2': 'Accessibilité : Structurées et disponibles pour les systèmes et les décideurs',
'insights.fromDataToDecisions.body.dataReadiness.item3': 'Confiance : Gouvernées, sécurisées et respectueuses de la confidentialité',
'insights.fromDataToDecisions.body.dataReadiness.p2': 'Les modèles d’IA entraînés sur des données incohérentes ou fragmentées généreront des résultats peu fiables. Les architectures de données centralisées transforment les informations dispersées en actifs structurés de qualité décisionnelle.',
'insights.fromDataToDecisions.body.dataReadiness.p3': 'Des données d’entrée médiocres créent des résultats instables. Des bases de données solides permettent une automatisation fiable.',

// --- Section 5 ---
'insights.fromDataToDecisions.body.roadmap.title': '5. Concevoir une feuille de route stratégique pour l’IA',
'insights.fromDataToDecisions.body.roadmap.p1': 'La technologie seule ne garantit pas le succès de l’IA d’entreprise. Une feuille de route stratégique doit aborder :',
'insights.fromDataToDecisions.body.roadmap.item1': 'Modernisation de l’architecture des données',
'insights.fromDataToDecisions.body.roadmap.item2': 'Interopérabilité des systèmes',
'insights.fromDataToDecisions.body.roadmap.item3': 'Cadres de gestion des risques et de gouvernance',
'insights.fromDataToDecisions.body.roadmap.item4': 'Alignement opérationnel',
'insights.fromDataToDecisions.body.roadmap.item5': 'Développement des talents et des compétences',
'insights.fromDataToDecisions.body.roadmap.item6': 'Processus d’innovation évolutifs',
'insights.fromDataToDecisions.body.roadmap.p2': 'Les organisations performantes équilibrent les victoires rapides avec une planification architecturale à long terme. Le déploiement de l’IA doit être progressif, gouverné et aligné sur des objectifs commerciaux mesurables.',

// --- Section 6 ---
'insights.fromDataToDecisions.body.trends.title': '6. Les tendances de l’IA d’entreprise en 2026',
'insights.fromDataToDecisions.body.trends.p1': 'Plusieurs tendances accélèrent l’adoption de l’IA en entreprise :',
'insights.fromDataToDecisions.body.trends.item1': 'Modernisation du cloud et plateformes de données évolutives',
'insights.fromDataToDecisions.body.trends.item2': 'Démocratisation des outils d’IA pour les utilisateurs métier',
'insights.fromDataToDecisions.body.trends.item3': 'Systèmes d’IA multimodaux (texte, image, audio, vidéo)',
'insights.fromDataToDecisions.body.trends.item4': 'Modèles opérationnels intégrés pour les données et l’IA',
'insights.fromDataToDecisions.body.trends.item5': 'Cadres d’évaluation de la maturité',
'insights.fromDataToDecisions.body.trends.p2': 'Les organisations mesurent de plus en plus les progrès de l’IA par rapport aux normes de gouvernance et aux indicateurs de performance opérationnelle plutôt qu’au simple volume d’expérimentation.',

// --- Section 7 ---
'insights.fromDataToDecisions.body.risks.title': '7. Risques à gérer',
'insights.fromDataToDecisions.body.risks.p1': 'L’IA d’entreprise introduit des risques mesurables. Les défis courants incluent :',
'insights.fromDataToDecisions.body.risks.item1': 'Biais des modèles causés par une mauvaise qualité des données',
'insights.fromDataToDecisions.body.risks.item2': 'Barrières à l’intégration des systèmes hérités (legacy)',
'insights.fromDataToDecisions.body.risks.item3': 'Exposition aux risques de conformité et de gouvernance',
'insights.fromDataToDecisions.body.risks.item4': 'Échecs du passage à l’échelle après des pilotes réussis',
'insights.fromDataToDecisions.body.risks.item5': 'Pénurie de talents spécialisés en IA',
'insights.fromDataToDecisions.body.risks.p2': 'Atténuer ces risques nécessite une surveillance proactive, des mécanismes d’IA explicable et des cadres de supervision structurés.',

// --- Conclusion ---
'insights.fromDataToDecisions.body.conclusion.title': '8. Conclusion',
'insights.fromDataToDecisions.body.conclusion.p1': 'En 2026, une IA prête pour l’entreprise n’est pas optionnelle. Elle devient le fondement de la compétitivité opérationnelle.',
'insights.fromDataToDecisions.body.conclusion.p2': 'Les organisations qui réussissent :',
'insights.fromDataToDecisions.body.conclusion.item1': 'S’appuient sur des bases de données gouvernées et de haute qualité',
'insights.fromDataToDecisions.item2': 'Adoptent des stratégies de croissance basées sur la maturité',
'insights.fromDataToDecisions.body.conclusion.item3': 'Alignent les initiatives d’IA sur des objectifs commerciaux mesurables',
'insights.fromDataToDecisions.body.conclusion.item4': 'Modernisent l’infrastructure avant de généraliser l’automatisation',
'insights.fromDataToDecisions.body.conclusion.item5': 'Favorisent une culture d’amélioration continue',
'insights.fromDataToDecisions.body.conclusion.p3': 'L’IA n’est pas une initiative isolée. C’est un écosystème interconnecté intégré au cœur des opérations de l’entreprise.',
'insights.fromDataToDecisions.body.conclusion.p4': 'Commencez délibérément. Bâtissez des fondations solides. Évoluez avec détermination.',
'insights.fromDataToDecisions.body.conclusion.p5': 'L’objectif n’est pas simplement de déployer l’IA. L’objectif est de bâtir des systèmes gouvernés qui convertissent les données en décisions fiables de niveau entreprise.',

// --- Key Takeaways ---
'insights.fromDataToDecisions.body.takeaways.title': 'Points clés à retenir',
'insights.fromDataToDecisions.body.takeaways.item1': 'L’IA d’entreprise exige une infrastructure, pas de l’expérimentation',
'insights.fromDataToDecisions.body.takeaways.item2': 'La préparation des données détermine la fiabilité des décisions',
'insights.fromDataToDecisions.body.takeaways.item3': 'Les modèles de maturité guident un passage à l’échelle structuré',
'insights.fromDataToDecisions.body.takeaways.item4': 'La gouvernance et la sécurité doivent être intégrées dès le départ',
'insights.fromDataToDecisions.body.takeaways.item5': 'Les écosystèmes d’IA doivent s’aligner sur des résultats commerciaux mesurables',

// --- Sidebar ---
'insights.fromDataToDecisions.sidebar.tocTitle': 'Dans cet article',
'insights.fromDataToDecisions.sidebar.toc.item1': '1. Qu’est-ce que "l’IA prête pour l’entreprise"',
'insights.fromDataToDecisions.sidebar.toc.item2': '2. L’importance de l’infrastructure',
'insights.fromDataToDecisions.sidebar.toc.item3': '3. Quatre niveaux de maturité de l’IA',
'insights.fromDataToDecisions.sidebar.toc.item4': '4. Des données prêtes pour l’IA ?',
'insights.fromDataToDecisions.sidebar.toc.item5': '5. Feuille de route stratégique',
'insights.fromDataToDecisions.sidebar.toc.item6': '6. Tendances de l’IA en 2026',
'insights.fromDataToDecisions.sidebar.toc.item7': '7. Risques à gérer',
'insights.fromDataToDecisions.sidebar.toc.item8': '8. Conclusion',

'insights.fromDataToDecisions.sidebar.shareTitle': 'Partager cet article',
'insights.fromDataToDecisions.sidebar.share.linkedin': 'Partager sur LinkedIn',
'insights.fromDataToDecisions.sidebar.share.twitter': 'Partager sur Twitter',
'insights.fromDataToDecisions.sidebar.share.facebook': 'Partager sur Facebook',
'insights.fromDataToDecisions.sidebar.share.copy': 'Copier le lien',
'insights.fromDataToDecisions.sidebar.copyFeedback': 'Lien copié !',


// ========================================
// INSIGHTS ARTICLE
// Why AI Strategy Fails Without Strong IT Foundations
// ========================================

// --- Hero ---
'insights.whyAIStrategyFails.hero.image.alt': 'Arrière-plan de protection d’assurance',
'insights.whyAIStrategyFails.hero.category': 'Stratégie d’IA et Architecture Informatique',
'insights.whyAIStrategyFails.hero.date': '23 février 2026',
'insights.whyAIStrategyFails.hero.title': 'Pourquoi la stratégie d’IA échoue sans des fondations informatiques solides',
'insights.whyAIStrategyFails.hero.excerpt': 'L’IA échoue lorsqu’elle est bâtie sur des fondations informatiques fragiles. Une infrastructure évolutive et des données gouvernées sont essentielles pour des résultats durables.',

// --- Body Intro ---
'insights.whyAIStrategyFails.body.intro.p1': 'L’intelligence artificielle n’est plus seulement un test. Les entreprises de nombreux domaines dépensent beaucoup d’argent dans des projets d’IA, de l’analyse prédictive à l’automatisation générative. Mais même avec des fonds plus importants et le soutien des dirigeants, de nombreux projets d’IA cessent de fonctionner, ne font pas ce qu’ils sont censés faire ou échouent purement et simplement.',
'insights.whyAIStrategyFails.body.intro.p2': 'La raison n’est pas de mauvais algorithmes.',
'insights.whyAIStrategyFails.body.intro.p3': 'Les fondamentaux informatiques sont médiocres.',

// --- Section 1 ---
'insights.whyAIStrategyFails.body.notSimple.title': '1. L’IA n’est pas une solution simple',
'insights.whyAIStrategyFails.body.notSimple.p1': 'Les entreprises considèrent généralement l’IA comme un complément à leurs logiciels, quelque chose qui peut être ajouté aux systèmes existants sans apporter de grands changements. L’IA a besoin de beaucoup d’infrastructure pour fonctionner. Elle nécessite une architecture évolutive, des pipelines de données propres, un environnement sécurisé et des flux de travail pour une intégration continue.',
'insights.whyAIStrategyFails.body.notSimple.p2': 'L’IA devient peu fiable, coûteuse et difficile à mettre à l’échelle sans fondations informatiques actuelles.',
'insights.whyAIStrategyFails.body.notSimple.p3': 'Avant d’utiliser des modèles avancés, les entreprises doivent vérifier si leur infrastructure peut bien gérer les charges de travail de l’IA.',

// --- Section 2 ---
'insights.whyAIStrategyFails.body.legacy.title': '2. Les anciens systèmes causent des problèmes structurels',
'insights.whyAIStrategyFails.body.legacy.p1': 'De nombreuses entreprises utilisent encore des structures monolithiques et des bases de données fragmentées. Ces systèmes n’ont jamais été conçus pour effectuer des analyses en temps réel, des processus d’apprentissage automatique ou pour traiter de grandes quantités de données.',
'insights.whyAIStrategyFails.body.legacy.p2': 'Lorsque des outils d’IA sont ajoutés à d’anciens systèmes, certains problèmes surviennent souvent :',
'insights.whyAIStrategyFails.body.legacy.item1': 'Les silos de données rendent impossible l’entraînement d’un modèle unique.',
'insights.whyAIStrategyFails.body.legacy.item2': 'Les systèmes lents rendent difficile l’obtention d’analyses.',
'insights.whyAIStrategyFails.body.legacy.item3': 'L’automatisation est bloquée par des processus manuels.',
'insights.whyAIStrategyFails.body.legacy.item4': 'Les coûts d’intégration augmentent de manière inattendue',
'insights.whyAIStrategyFails.body.legacy.p3': 'Des systèmes natifs du cloud, pilotés par API et évolutifs sont nécessaires pour l’IA moderne. Les projets d’IA ont du mal à dépasser l’étape de la preuve de concept sans modernisation.',
'insights.whyAIStrategyFails.body.legacy.image.alt': 'Pourquoi la stratégie d’IA échoue sans des fondations informatiques solides',

// --- Section 3 ---
'insights.whyAIStrategyFails.body.dataQuality.title': '3. La qualité des données affecte le fonctionnement de l’IA.',
'insights.whyAIStrategyFails.body.dataQuality.p1': 'Les systèmes d’IA ne peuvent fonctionner qu’aussi bien que les données qu’ils utilisent. Une mauvaise gouvernance des données, des formats incohérents, des informations manquantes et des enregistrements en double peuvent rendre les performances très mauvaises.',
'insights.whyAIStrategyFails.body.dataQuality.p2': 'Les entreprises ne réalisent souvent pas tout le travail nécessaire pour :',
'insights.whyAIStrategyFails.body.dataQuality.item1': 'Uniformiser les sources de données',
'insights.whyAIStrategyFails.body.dataQuality.item2': 'S’assurer que vos pipelines de données fonctionnent.',
'insights.whyAIStrategyFails.body.dataQuality.item3': 'Mettre en place des cadres pour la validation des données',
'insights.whyAIStrategyFails.body.dataQuality.item4': 'S’assurer de suivre les règles',
'insights.whyAIStrategyFails.body.dataQuality.p3': 'Des fondations informatiques solides créent des architectures de données centralisées et des structures de gouvernance qui rendent l’IA sûre et fiable.',

// --- Section 4 ---
'insights.whyAIStrategyFails.body.scalability.title': '4. Ne pas supposer que l’évolutivité est une nécessité',
'insights.whyAIStrategyFails.body.scalability.p1': 'De nombreux pilotes d’IA ont montré de bonnes performances précoces. Mais lorsque les entreprises essaient d’utiliser ces solutions dans toute l’entreprise, elles commencent à voir des problèmes avec leur infrastructure.',
'insights.whyAIStrategyFails.body.scalability.p2': 'Les limitations sur le calcul, le stockage et les problèmes de performance deviennent immédiatement clairs.',
'insights.whyAIStrategyFails.body.scalability.p3': 'Amazon Web Services, Microsoft Azure et Google Cloud sont des exemples de plateformes natives du cloud qui permettent une mise à l’échelle élastique. Cependant, cela ne fonctionne que si les systèmes sont conçus pour en tirer parti.',
'insights.whyAIStrategyFails.body.scalability.p4': 'Concevoir pour l’échelle dès le départ est important pour que l’IA fonctionne.',

// --- Section 5 ---
'insights.whyAIStrategyFails.body.security.title': '5. N’oubliez pas la sécurité et la gouvernance',
'insights.whyAIStrategyFails.body.security.p1': 'L’IA ajoute de nouveaux niveaux de risque, tels que les inquiétudes concernant la confidentialité des données, les biais dans les modèles, l’exposition aux réglementations et les points faibles de la cybersécurité.',
'insights.whyAIStrategyFails.body.security.p2': 'Les entreprises qui n’ont pas une bonne gouvernance informatique risquent des échecs de conformité et des dommages à leur réputation.',
'insights.whyAIStrategyFails.body.security.p3': 'Une infrastructure solide doit comporter :',
'insights.whyAIStrategyFails.body.security.item1': 'La gestion des identités et des accès',
'insights.whyAIStrategyFails.body.security.item2': 'Des protocoles de chiffrement',
'insights.whyAIStrategyFails.body.security.item3': 'Des pistes d’audit',
'insights.whyAIStrategyFails.body.security.item4': 'Des systèmes de surveillance des modèles',
'insights.whyAIStrategyFails.body.security.p4': 'Une feuille de route d’IA planifiée doit fonctionner avec les cadres de sécurité de l’entreprise, pas contre eux.',

// --- Section 6 ---
'insights.whyAIStrategyFails.body.itFirst.title': '6. La stratégie informatique passe en premier dans la stratégie d’IA',
'insights.whyAIStrategyFails.body.itFirst.p1': 'Les entreprises qui réussissent avec l’IA l’utilisent de diverses manières. D’abord, elles investissent de l’argent dans :',
'insights.whyAIStrategyFails.body.itFirst.item1': 'La modernisation du cloud',
'insights.whyAIStrategyFails.body.itFirst.item2': 'L’automatisation et le DevOps',
'insights.whyAIStrategyFails.body.itFirst.item3': 'L’ingénierie des données',
'insights.whyAIStrategyFails.body.itFirst.item4': 'L’interopérabilité des systèmes',
'insights.whyAIStrategyFails.body.itFirst.p2': 'Elles voient l’IA comme un outil qui peut être utilisé au-dessus d’une infrastructure numérique robuste, et non comme un moyen d’accélérer l’innovation.',
'insights.whyAIStrategyFails.body.itFirst.p3': 'Nous pensons la stratégie d’IA chez Synexum Labs comme une extension de l’architecture informatique. Avant de mettre en service des systèmes intelligents, nous nous assurons que les entreprises ont les bonnes structures en place pour les soutenir dans le temps.',
'insights.whyAIStrategyFails.body.itFirst.p4': 'L’IA n’échoue pas parce qu’elle ne le veut pas.',
'insights.whyAIStrategyFails.body.itFirst.p5': 'Quand la base en dessous n’est pas assez solide pour la soutenir, elle échoue.',

// --- Key Takeaways ---
'insights.whyAIStrategyFails.body.takeaways.title': 'Points clés à retenir',
'insights.whyAIStrategyFails.body.takeaways.item1': 'Les initiatives d’IA échouent principalement en raison d’une infrastructure informatique fragile',
'insights.whyAIStrategyFails.body.takeaways.item2': 'Les systèmes hérités limitent l’évolutivité et l’intégration',
'insights.whyAIStrategyFails.body.takeaways.item3': 'La gouvernance des données est essentielle à la fiabilité de l’IA',
'insights.whyAIStrategyFails.body.takeaways.item4': 'La sécurité et la conformité doivent être intégrées dès le départ',
'insights.whyAIStrategyFails.body.takeaways.item5': 'Une architecture informatique moderne doit précéder le déploiement de l’IA',

// --- Conclusion ---
'insights.whyAIStrategyFails.body.conclusion.title': 'Conclusion',
'insights.whyAIStrategyFails.body.conclusion.p1': 'L’intelligence artificielle est puissante, mais elle n’est pas autonome. Une transformation durable de l’IA nécessite une infrastructure moderne, des environnements de données gouvernés et une architecture évolutive.',
'insights.whyAIStrategyFails.body.conclusion.p2': 'Les organisations qui privilégient la modernisation informatique avant le déploiement de l’IA se positionnent pour une fiabilité opérationnelle à long terme et un impact mesurable.',
'insights.whyAIStrategyFails.body.conclusion.p3': 'Sans fondations solides, même la stratégie d’IA la plus avancée aura du mal à apporter de la valeur à l’entreprise.',

// --- Sidebar ---
'insights.whyAIStrategyFails.sidebar.tocTitle': 'Dans cet article',
'insights.whyAIStrategyFails.sidebar.toc.item1': '1. L’IA n’est pas un simple ajout',
'insights.whyAIStrategyFails.sidebar.toc.item2': '2. Contraintes des systèmes hérités',
'insights.whyAIStrategyFails.sidebar.toc.item3': '3. Données et gouvernance',
'insights.whyAIStrategyFails.sidebar.toc.item4': '4. Exigences d’évolutivité',
'insights.whyAIStrategyFails.sidebar.toc.item5': '5. Sécurité et gouvernance',
'insights.whyAIStrategyFails.sidebar.toc.item6': '6. L’informatique avant l’IA',
'insights.whyAIStrategyFails.sidebar.toc.item7': '7. Conclusion',

'insights.whyAIStrategyFails.sidebar.shareTitle': 'Partager cet article',
'insights.whyAIStrategyFails.sidebar.share.linkedin': 'Partager sur LinkedIn',
'insights.whyAIStrategyFails.sidebar.share.twitter': 'Partager sur Twitter',
'insights.whyAIStrategyFails.sidebar.share.facebook': 'Partager sur Facebook',
'insights.whyAIStrategyFails.sidebar.share.copy': 'Copier le lien',
'insights.whyAIStrategyFails.sidebar.copyFeedback': 'Lien copié !',









    },
    es: {

        // ========================================
// HOMEPAGE
// ========================================

// --- Hero ---
'home.hero.eyebrow': 'Estrategia que se ejecuta',
'home.hero.title.line1': 'El Sistema Operativo para',
'home.hero.title.highlight': 'Transformación Digital',
'home.hero.subtitle': 'Construimos sistemas gobernados, escalables y sostenibles que cierran la brecha entre estrategia y ejecución. Infraestructura de decisión que hace a su organización más inteligente, más rápida y más responsable.',
'home.hero.cta.primary': 'Reservar Llamada de Descubrimiento',
'home.hero.cta.secondary': 'Descargar Resumen de Capacidades',
'home.hero.trust.title': 'Con la confianza de organizaciones institucionales',
'home.hero.trust.item1': 'Servicios Financieros',
'home.hero.trust.item2': 'Salud',
'home.hero.trust.item3': 'Empresarial',
'home.hero.trust.item4': 'Gobierno',

// --- Client Fit Section ---
'home.clientFit.title': 'Construido para Organizaciones que Exigen Más',
'home.clientFit.subtitle': 'Trabajamos con clientes institucionales que necesitan soluciones confiables, gobernadas y medibles de IA y automatización.',

'home.clientFit.card1.title': 'Operaciones Institucionales',
'home.clientFit.card1.desc': 'Organizaciones con procesos complejos y de alto impacto que requieren precisión y control.',

'home.clientFit.card2.title': 'Entornos con Prioridad en el Cumplimiento',
'home.clientFit.card2.desc': 'Equipos que operan bajo estrictos requisitos regulatorios y obligaciones de auditoría.',

'home.clientFit.card3.title': 'Flujos de Trabajo Intensivos en Datos',
'home.clientFit.card3.desc': 'Operaciones que generan datos significativos que pueden aprovecharse para la automatización.',

'home.clientFit.card4.title': 'Desafíos de Escalabilidad',
'home.clientFit.card4.desc': 'Organizaciones en crecimiento donde los procesos manuales crean cuellos de botella.',

'home.clientFit.card5.title': 'Resultados Medibles Requeridos',
'home.clientFit.card5.desc': 'Líderes responsables de un ROI demostrable y mejoras operativas.',

// --- Capabilities Section ---
'home.capabilities.title': 'Nuestro Modelo de Servicio Integrado',
'home.capabilities.subtitle': 'Construido sobre nuestra arquitectura Core/Grid + Células Modulares, cada solución es tanto escalable como gobernada - desde arquitectura de sistemas vivos hasta sostenimiento de grado institucional.',

// Capability 1
'home.capabilities.card1.title': 'Modelo de Entrega Gobernado',
'home.capabilities.card1.problem.label': 'Problema:',
'home.capabilities.card1.problem': 'Equipos fragmentados y brechas de cumplimiento',
'home.capabilities.card1.solution.label': 'Solución:',
'home.capabilities.card1.solution': 'Marco de entrega unificado con propiedad clara de decisiones',
'home.capabilities.card1.outcome.label': 'Resultado:',
'home.capabilities.card1.outcome': 'Objetivos estratégicos alcanzados con ejecución de nivel institucional',

// Capability 2
'home.capabilities.card2.title': 'Arquitectura de Sistemas Vivos',
'home.capabilities.card2.problem.label': 'Problema:',
'home.capabilities.card2.problem': 'Datos, decisiones y ejecución desconectados',
'home.capabilities.card2.solution.label': 'Solución:',
'home.capabilities.card2.solution': 'Capa de inteligencia que observa, aprende y se adapta',
'home.capabilities.card2.outcome.label': 'Resultado:',
'home.capabilities.card2.outcome': 'Sistemas sostenibles que acumulan valor con el tiempo',

// Capability 3
'home.capabilities.card3.title': 'Ingeniería de Plataformas Escalables',
'home.capabilities.card3.problem.label': 'Problema:',
'home.capabilities.card3.problem': 'Despliegue lento y stack tecnológico fragmentado',
'home.capabilities.card3.solution.label': 'Solución:',
'home.capabilities.card3.solution': 'Desarrollo full-stack, IA/ML, DevOps y servicios de QA',
'home.capabilities.card3.outcome.label': 'Resultado:',
'home.capabilities.card3.outcome': 'Despliegue rápido sostenido a través de zonas horarias con gobernanza',

// Capability 4
'home.capabilities.card4.title': 'Desarrollo de Células Modulares',
'home.capabilities.card4.problem.label': 'Problema:',
'home.capabilities.card4.problem': 'Escalar sacrifica control y cumplimiento',
'home.capabilities.card4.solution.label': 'Solución:',
'home.capabilities.card4.solution': 'Unidades de ejecución específicas por dominio que heredan gobernanza del Core/Grid',
'home.capabilities.card4.outcome.label': 'Resultado:',
'home.capabilities.card4.outcome': 'Escalar con autonomía y velocidad sin sacrificar control',

// Capability 5
'home.capabilities.card5.title': 'Sostenimiento de Grado Institucional',
'home.capabilities.card5.problem.label': 'Problema:',
'home.capabilities.card5.problem': 'Inestabilidad y desviación después del lanzamiento',
'home.capabilities.card5.solution.label': 'Solución:',
'home.capabilities.card5.solution': 'Soporte operativo continuo y gestión del sistema',
'home.capabilities.card5.outcome.label': 'Resultado:',
'home.capabilities.card5.outcome': 'Los sistemas permanecen estables, cumplen normativas y continúan acumulando valor',

'home.capabilities.cta': 'Ver Todas las Capacidades',

// --- Process Section ---
'home.process.title': 'Cómo Trabajamos',
'home.process.subtitle': 'Un enfoque estructurado y gobernado que entrega resultados predecibles con total visibilidad operativa.',

'home.process.step1.title': 'Descubrir',
'home.process.step1.desc': 'Evaluamos sus operaciones actuales, restricciones y objetivos. Sin evaluaciones genéricas — análisis específico de sus sistemas, datos y procesos.',
'home.process.step1.tag1': 'Auditoría operativa',
'home.process.step1.tag2': 'Revisión del panorama de datos',
'home.process.step1.tag3': 'Priorización de oportunidades',

'home.process.step2.title': 'Diseñar',
'home.process.step2.desc': 'Arquitectura y diseño de soluciones alineados con sus requisitos de seguridad, cumplimiento y operación. Especificaciones claras antes de comenzar cualquier desarrollo.',
'home.process.step2.tag1': 'Arquitectura de solución',
'home.process.step2.tag2': 'Especificaciones de integración',
'home.process.step2.tag3': 'Marco de gobernanza',

'home.process.step3.title': 'Construir',
'home.process.step3.desc': 'Desarrollo iterativo con visibilidad continua para los stakeholders. Sin cajas negras — usted ve el progreso y puede ajustar el rumbo en todo momento.',
'home.process.step3.tag1': 'Componentes funcionales del sistema',
'home.process.step3.tag2': 'Documentación',
'home.process.step3.tag3': 'Materiales de formación',

'home.process.step4.title': 'Operar',
'home.process.step4.desc': 'Gestión continua del sistema, monitoreo y optimización. No solo entregamos y desaparecemos — aseguramos un rendimiento sostenido.',
'home.process.step4.tag1': 'Monitoreo del sistema',
'home.process.step4.tag2': 'Optimización del rendimiento',
'home.process.step4.tag3': 'Mejora continua',

'home.process.cta': 'Conozca Más Sobre Nuestro Proceso',

// --- Proof Section ---
'home.proof.title': 'Impacto Medible',
'home.proof.subtitle': 'Resultados reales de implementaciones reales. Medimos el éxito en mejoras operativas, no en la finalización del proyecto.',

'home.proof.metric1.label': 'Reducción en el tiempo de procesamiento',
'home.proof.metric1.context': 'Promedio en proyectos de automatización',

'home.proof.metric2.label': 'Tasa de precisión',
'home.proof.metric2.context': 'Comparado con una línea base manual del 94%',

'home.proof.metric3.label': 'Mejora en el rendimiento',
'home.proof.metric3.context': 'Sin personal adicional',

'home.proof.metric4.label': 'Cronograma típico de ROI',
'home.proof.metric4.context': 'Tiempo hasta retorno positivo',

// --- Case Studies ---
'home.caseStudies.card1.tag': 'Automatización de Procesos',
'home.caseStudies.card1.title': 'Reemplazando Trabajo Administrativo con Automatización',
'home.caseStudies.card1.desc': 'Una configuración real de Go High Level que muestra cómo la automatización reemplazó la coordinación manual y la carga administrativa - sin contratar más personal.',
'home.caseStudies.card1.metric1': '60%+ tareas administrativas automatizadas',
'home.caseStudies.card1.metric2': '↓45% coordinación manual',
'home.caseStudies.card1.metric3': '↑35% velocidad operativa',
'home.caseStudies.card1.metric4': '0 nuevas contrataciones administrativas',

'home.caseStudies.card2.tag': 'Diseño UI / UX',
'home.caseStudies.card2.title': 'Rediseño UX para Aumentar el Compromiso',
'home.caseStudies.card2.desc': 'Transformó visitantes pasivos en usuarios activos mediante mejoras UX basadas en comportamiento - aumentando el compromiso sin gasto adicional en tráfico.',
'home.caseStudies.card2.metric1': '↓42% tasa de rebote',
'home.caseStudies.card2.metric2': '↑65% duración de sesión',
'home.caseStudies.card2.metric3': '↑78% interacciones CTA',
'home.caseStudies.card2.metric4': '4–5 acciones por visita',

'home.caseStudies.card3.tag': 'Servicios Financieros',
'home.caseStudies.card3.title': 'Informes de Cumplimiento Automatizados',
'home.caseStudies.card3.desc': 'Transformó un proceso manual semanal de 40 horas en un sistema automatizado en tiempo real con registros de auditoría integrados.',
'home.caseStudies.card3.metric1': '92% reducción de tiempo',
'home.caseStudies.card3.metric2': 'Cero brechas de cumplimiento',
'home.caseStudies.card3.metric3': 'Visibilidad en tiempo real',

'home.caseStudies.cta': 'Ver Todos los Estudios de Caso',

// --- Final CTA ---
'home.finalCta.title': '¿Interesado en Trabajar Juntos?',
'home.finalCta.desc': 'Complete sus datos y nuestro equipo se pondrá en contacto en breve para continuar la conversación. Desde allí, exploraremos cómo nuestras soluciones podrían alinearse con las necesidades y prioridades de su organización.',
'home.finalCta.emailLabel': '¿Prefiere correo electrónico?',
'home.finalCta.emailText': 'Contáctenos en support@synexumlabs.com',
'home.finalCta.formTitle': 'Iniciar la Conversación',
'home.finalCta.note': 'Respondemos dentro de un día hábil',



        //HEADER

        'nav.capabilities': 'Capacidades',
        'nav.caseStudies': 'Casos de Estudio',
        'nav.howWeWork': 'Cómo Trabajamos',
        'nav.insights': 'Perspectivas',
        'nav.about': 'Acerca de',

        'nav.capabilities.governed': 'Modelo de Entrega Gobernado',
        'nav.capabilities.governed.desc': 'Gobernanza unificada de la entrega',

        'nav.capabilities.living': 'Arquitectura de Sistema Evolutiva',
        'nav.capabilities.living.desc': 'Inteligencia conectada y adaptativa',

        'nav.capabilities.scalable': 'Ingeniería de Plataformas Escalables',
        'nav.capabilities.scalable.desc': 'Plataformas de IA full-stack',

        'nav.capabilities.modular': 'Desarrollo Modular Autónomo',
        'nav.capabilities.modular.desc': 'Unidades autónomas y gobernadas',

        'nav.capabilities.viewAll': 'Ver Todas las Capacidades →',

        'nav.cta.discovery': 'Agendar Llamada de Descubrimiento',

        'nav.capabilities.mobile': 'CAPACIDADES',

        'nav.language': 'Idioma',

        // SYNEXUM ABOUT PAGE (ES)

        'about.hero.title': 'El puente entre estrategia y ejecución',
        'about.hero.desc': 'Synexum Labs nació de una realización compartida: las organizaciones fracasan en la transformación digital no por falta de estrategia, sino por la incapacidad de ejecutar entre equipos fragmentados, sistemas aislados y entornos regulatorios complejos. El problema es estructural: la brecha entre la visión estratégica y la realidad operativa.',

        'about.story.title': 'Nuestra historia',

        'about.story.p1': 'Reconocimos que esta brecha existe porque el mercado carece de un enfoque unificado. Las organizaciones necesitan claridad estratégica y gobernanza institucional por un lado, combinadas con capacidad de ejecución, velocidad y escalabilidad por el otro. Ninguno de los dos es suficiente por sí solo. Se necesita un puente: un modelo operativo unificado que haga la estrategia ejecutable y la ejecución gobernada.',

        'about.story.p2': 'Synexum Labs es ese puente. Somos el modelo operativo unificado donde la dirección estratégica se convierte en un sistema ejecutable y la capacidad de ingeniería se transforma en un motor de entrega controlado y de nivel institucional.',

        'about.story.p3': 'Nuestro concepto central es que la transformación digital no es software, es infraestructura de decisiones.',

        'about.story.p4': 'Construimos "sistemas vivos" que observan, deciden, activan acciones y aprenden de los resultados, manteniendo siempre la gobernanza. Esta es la base de nuestro enfoque: claridad estratégica unificada con ejecución escalable a través del sistema operativo Synexum.',

        'about.mission.title': 'Nuestra misión',

        'about.mission.p1': 'Resolvemos la paradoja del crecimiento: aumentar la capacidad de ejecución sin perder gobernanza, responsabilidad ni coherencia institucional.',

        'about.mission.p2': 'Junto con Coigne Capital, ofrecemos un puente fluido — desde la visión estratégica confiable de Coigne hasta la sólida ejecución técnica de Synexum.',

        'about.values.precision.title': 'Precisión',
        'about.values.precision.desc': 'Medimos el éxito en resultados, no en actividad.',

        'about.values.transparency.title': 'Transparencia',
        'about.values.transparency.desc': 'Sin cajas negras. Tienes visibilidad total de nuestros procesos y sistemas.',

        'about.values.governance.title': 'Gobernanza Primero',
        'about.values.governance.desc': 'Seguridad, cumplimiento y control son fundamentales, no añadidos posteriores.',

        'about.leadership.title': 'Equipo de liderazgo',
        'about.leadership.subtitle': 'Operadores experimentados que han construido y liderado organizaciones tecnológicas a gran escala en industrias reguladas.',

        'about.standards.title': 'Nuestros estándares',
        'about.standards.desc': 'Operamos con estándares institucionales porque nuestros clientes lo exigen — y porque es la forma correcta de construir sistemas que realmente importan.',

        'about.coigne.title': 'Parte de Coigne Capital',
        'about.coigne.link': 'Conoce más sobre Coigne Capital',

        'about.cta.title': 'Hablemos de tus operaciones',
        'about.cta.desc': 'Agenda una llamada de descubrimiento para explorar cómo Synexum Labs puede transformar tus operaciones con automatización inteligente.',
        'about.cta.button': 'Agendar llamada de descubrimiento',

        // SYNEXUM CAPABILITIES PAGE (ES)

// --- Hero ---
'cap.hero.title': 'Construye y gestiona tu sistema operativo institucional',
'cap.hero.desc': 'Nuestra suite integrada de servicios se basa en nuestra arquitectura Core/Grid + Células Modulares, garantizando que cada solución sea escalable y gobernada.',

// --- Governed Delivery Model ---
'cap.governed.title': 'Modelo de Entrega Gobernado',
'cap.governed.desc': 'Implementamos y gestionamos un marco de entrega unificado que garantiza que tus objetivos estratégicos se cumplan con ejecución de nivel institucional. Esto incluye propiedad clara de decisiones, gestión de cumplimiento transfronterizo e integración de herramientas fragmentadas en un sistema coherente.',

'cap.governed.highlight1': 'Propiedad de decisiones',
'cap.governed.highlight2': 'Cumplimiento transfronterizo',
'cap.governed.highlight3': 'Integración de herramientas',
'cap.governed.highlight4': 'Marcos de gobernanza',

// --- Living Systems Architecture ---
'cap.living.title': 'Arquitectura de Sistemas Vivos',
'cap.living.desc': 'Diseñamos y construimos la capa de inteligencia que conecta tus datos, decisiones y ejecución. No solo aplicaciones, sino sistemas sostenibles que observan, aprenden y se adaptan a tu entorno operativo.',

'cap.living.highlight1': 'Observar y decidir',
'cap.living.highlight2': 'Activar y aprender',
'cap.living.highlight3': 'Integración de IA',
'cap.living.highlight4': 'Controles de gobernanza',

// --- Scalable Platform Engineering ---
'cap.scalable.title': 'Ingeniería de Plataformas Escalables',
'cap.scalable.desc': 'Desarrollo full-stack, integración IA/ML, DevOps y QA. Nuestra capacidad global de ejecución garantiza despliegue rápido y entrega sostenida dentro de nuestro marco de gobernanza.',

'cap.scalable.highlight1': 'Desarrollo full-stack',
'cap.scalable.highlight2': 'Integración IA/ML',
'cap.scalable.highlight3': 'DevOps y QA',
'cap.scalable.highlight4': 'Capacidad global',

// --- Modular Cell Development ---
'cap.modular.title': 'Desarrollo de Células Modulares',
'cap.modular.desc': 'Unidades de ejecución especializadas ("Células") para Finanzas, Operaciones, Analítica y más. Cada célula opera con autonomía y velocidad, heredando la gobernanza del Core/Grid.',

'cap.modular.highlight1': 'Arquitectura Core/Grid',
'cap.modular.highlight2': 'Células de dominio',
'cap.modular.highlight3': 'Herencia de gobernanza',
'cap.modular.highlight4': 'Control escalable',

// --- Institutional-Grade Sustainment ---
'cap.sustain.title': 'Sostenimiento de Nivel Institucional',
'cap.sustain.desc': 'Nuestro compromiso no termina en el lanzamiento. Brindamos soporte operativo continuo para garantizar que tus sistemas permanezcan estables, cumplan con la normativa y continúen generando valor con el tiempo.',

'cap.sustain.highlight1': 'Monitoreo 24/7',
'cap.sustain.highlight2': 'Mantenimiento proactivo',
'cap.sustain.highlight3': 'Sostenimiento de cumplimiento',
'cap.sustain.highlight4': 'Mejora continua',

// --- CTA ---
'cap.cta.title': '¿Listo para transformar tus operaciones?',
'cap.cta.desc': 'Conversemos sobre cómo nuestras capacidades se alinean con tus objetivos. Te ayudaremos a identificar las oportunidades de mayor impacto.',
'cap.cta.primary': 'Agendar llamada de descubrimiento',
'cap.cta.secondary': 'Ver casos de estudio',

// SYNEXUM CONTACT PAGE (ES)

// --- Hero ---
'contact.hero.title': 'Iniciemos la conversación',
'contact.hero.desc': 'Agenda una llamada de descubrimiento para analizar las necesidades de tu organización y explorar cómo podemos impulsar tu transformación digital.',

// --- Booking Column ---
'contact.booking.title': 'Agendar llamada de descubrimiento',
'contact.booking.intro': 'Una videollamada de 30 minutos para comprender tus desafíos y explorar cómo la automatización inteligente puede generar mejoras medibles.',

'contact.booking.detail1.title': '30 minutos',
'contact.booking.detail1.desc': 'Sesión de descubrimiento enfocada',

'contact.booking.detail2.title': 'Videoconferencia',
'contact.booking.detail2.desc': 'Google Meet o Zoom',

'contact.booking.detail3.title': 'Horario flexible',
'contact.booking.detail3.desc': 'Elige el horario que mejor te funcione',

'contact.booking.button': 'Programar tu llamada de descubrimiento',
'contact.booking.note': 'Sin discurso de ventas — una conversación estructurada sobre tus operaciones',

// --- What to Expect ---
'contact.expect.title': 'Qué esperar',
'contact.expect.item1': 'Analizaremos tus desafíos actuales y objetivos operativos',
'contact.expect.item2': 'Exploraremos oportunidades de IA y automatización',
'contact.expect.item3': 'Definiremos los próximos pasos recomendados',

// --- Contact Info ---
'contact.info.title': 'Ponte en contacto',
'contact.info.intro': '¿Prefieres contactarnos directamente? Estamos aquí para ayudarte.',

'contact.info.email': 'Envíanos un correo',
'contact.info.phone': 'Llámanos',
'contact.info.address.title': 'Ubicación de la oficina',

'contact.response': 'Normalmente respondemos dentro de un día hábil',

// --- Coigne ---
'contact.coigne.title': 'Parte de Coigne Capital',
'contact.coigne.link': 'Conoce más sobre Coigne Capital',

// --- Case Studies Hero ---
'casestudies.hero.title': 'Casos de Estudio',
'casestudies.hero.desc': 'Resultados reales de implementaciones reales. Descubre cómo hemos ayudado a organizaciones institucionales a transformar sus operaciones con resultados medibles.',

// --- Featured Section ---
'casestudies.featured.title': 'Proyectos Destacados',

'casestudies.featured.project1.title': 'Rediseño UX para Aumentar la Participación',
'casestudies.featured.project1.client': 'Empresa de Plataforma Digital',
'casestudies.featured.project1.summary': 'Transformamos visitantes pasivos en usuarios activos mediante mejoras estratégicas de UX sin aumentar el gasto en tráfico.',
'casestudies.featured.project1.metric1.value': '↓42%',
'casestudies.featured.project1.metric1.label': 'Tasa de Rebote',
'casestudies.featured.project1.metric2.value': '↑65%',
'casestudies.featured.project1.metric2.label': 'Tiempo de Sesión',
'casestudies.featured.project1.metric3.value': '↑78%',
'casestudies.featured.project1.metric3.label': 'Clics en CTA',

'casestudies.featured.project2.title': 'Informes de Cumplimiento Automatizados',
'casestudies.featured.project2.client': 'Firma Regional de Servicios Financieros',
'casestudies.featured.project2.summary': 'Transformación de un proceso manual de 40 horas semanales en un sistema automatizado en tiempo real con registros de auditoría integrados.',
'casestudies.featured.project2.metric1.value': '92%',
'casestudies.featured.project2.metric1.label': 'Reducción de Tiempo',
'casestudies.featured.project2.metric2.value': '99.8%',
'casestudies.featured.project2.metric2.label': 'Precisión',
'casestudies.featured.project2.metric3.value': '4 meses',
'casestudies.featured.project2.metric3.label': 'Plazo de ROI',

// --- All Case Studies Section ---
'casestudies.all.title': 'Todos los Casos de Estudio',

'casestudies.all.study1.industry': 'Servicios Locales',
'casestudies.all.study1.title': 'Automatización del Seguimiento de Leads para una Empresa de Plomería',
'casestudies.all.study1.client': 'Empresa Regional de Servicios de Plomería',
'casestudies.all.study1.metric.value': '80%',
'casestudies.all.study1.metric.label': 'Tiempo de Respuesta Más Rápido',

'casestudies.all.study2.industry': 'Salud',
'casestudies.all.study2.title': 'Automatización de Build y Despliegue para una Suite de Pagador de Salud',
'casestudies.all.study2.client': 'Plataforma en la Nube para Pagador de Salud',
'casestudies.all.study2.metric.value': '55%↑',
'casestudies.all.study2.metric.label': 'Velocidad de Lanzamiento',

'casestudies.all.study3.industry': 'Plataforma Digital',
'casestudies.all.study3.title': 'Cómo Entregamos Plataformas Web de Alto Rendimiento',
'casestudies.all.study3.client': 'Empresa de Servicios Digitales de Alto Tráfico',
'casestudies.all.study3.metric.value': '50%',
'casestudies.all.study3.metric.label': 'Carga Más Rápida',

'casestudies.all.study4.industry': 'Automatización de Procesos',
'casestudies.all.study4.title': 'Reemplazando Trabajo Administrativo con Automatización',
'casestudies.all.study4.client': 'Empresa de Servicios Digitales',
'casestudies.all.study4.metric.value': '60%+',
'casestudies.all.study4.metric.label': 'Tareas Administrativas Automatizadas',

'casestudies.all.study5.industry': 'Plataforma Digital',
'casestudies.all.study5.title': 'Rediseño UX para Aumentar la Participación',
'casestudies.all.study5.client': 'Empresa de Plataforma Digital',
'casestudies.all.study5.metric.value': '↑78%',
'casestudies.all.study5.metric.label': 'Clics en CTA',

'casestudies.all.study6.industry': 'Servicios Financieros',
'casestudies.all.study6.title': 'Informes de Cumplimiento Automatizados',
'casestudies.all.study6.client': 'Firma Regional de Servicios Financieros',
'casestudies.all.study6.metric.value': '92%',
'casestudies.all.study6.metric.label': 'Reducción de Tiempo',

// --- CTA Section ---
'casestudies.cta.title': '¿Listo para Ver Resultados Similares?',
'casestudies.cta.desc': 'Cada organización es diferente. Hablemos de tus desafíos específicos y exploremos cómo podemos generar mejoras medibles.',
'casestudies.cta.button': 'Agendar una Llamada de Descubrimiento',


// --- Footer Brand ---
'footer.tagline': 'Transformaciones Digitales • Software • IA • Automatización',
'footer.taglineSmall': 'Synexum Labs es una submarca de Coigne Capital Inc.',
'footer.newsletter.title': 'Suscribirse a Insights',

// --- Footer Columns ---
'footer.capabilities.title': 'Capacidades',
'footer.capabilities.link1': 'Modelo de Entrega Gobernado',
'footer.capabilities.link2': 'Arquitectura de Sistema Vivo',
'footer.capabilities.link3': 'Ingeniería de Plataforma Escalable',
'footer.capabilities.link4': 'Desarrollo Modular por Células',
'footer.capabilities.link5': 'Sostenimiento de Nivel Institucional',

'footer.company.title': 'Empresa',
'footer.company.link1': 'Acerca de',
'footer.company.link2': 'Casos de Estudio',
'footer.company.link3': 'Insights',
'footer.company.link4': 'Contacto',

'footer.resources.title': 'Recursos',
'footer.resources.link1': 'Informe de Capacidades',

// --- Footer Bottom ---
'footer.copyright': '© Coigne Capital Inc. — Synexum Labs',
'footer.legal.privacy': 'Política de Privacidad',
'footer.legal.terms': 'Términos del Servicio',
'footer.legal.disclaimer': 'Aviso Legal',
'footer.legal.coigne': 'Una empresa de Coigne Capital',


// --- Hero ---
'hww.hero.title': 'Cómo Trabajamos',
'hww.hero.description': 'Un enfoque estructurado y gobernado que ofrece resultados predecibles con total visibilidad operativa. Sin sorpresas, sin cajas negras — solo resultados medibles.',

// --- Principles ---
'hww.principles.title': 'Nuestros Principios Rectores',
'hww.principles.description': 'Cada proyecto se guía por estos principios fundamentales para garantizar resultados exitosos.',

'hww.principle1.title': 'Gobernanza Primero',
'hww.principle1.desc': 'La seguridad, el cumplimiento y los requisitos de auditoría se integran desde el primer día.',

'hww.principle2.title': 'Transparencia Total',
'hww.principle2.desc': 'Visibilidad completa sobre progreso, decisiones y entregables.',

'hww.principle3.title': 'Alineación de Stakeholders',
'hww.principle3.desc': 'Trabajamos con tus equipos, no alrededor de ellos.',

'hww.principle4.title': 'Resultados Medibles',
'hww.principle4.desc': 'Cada iniciativa está vinculada a objetivos de negocio medibles.',

// --- Framework ---
'hww.framework.title': 'Nuestro Marco de Entrega',
'hww.framework.description': 'Metodología comprobada en cuatro fases que garantiza una entrega exitosa.',

// Step 1
'hww.step1.title': 'Descubrir',
'hww.step1.timeline': 'Semanas 1-2',
'hww.step1.desc': 'Evaluamos operaciones, limitaciones y objetivos para identificar oportunidades de alto impacto.',
'hww.step1.deliverables.title': 'Entregables',
'hww.step1.outcomes.title': 'Resultados',
'hww.step1.deliverable1': 'Auditoría operativa',
'hww.step1.deliverable2': 'Revisión del entorno de datos',
'hww.step1.deliverable3': 'Priorización de oportunidades',
'hww.step1.deliverable4': 'Entrevistas con stakeholders',
'hww.step1.outcome1': 'Comprensión clara del estado actual',
'hww.step1.outcome2': 'Hoja de ruta priorizada',
'hww.step1.outcome3': 'Mapa de riesgos y dependencias',

// Step 2
'hww.step2.title': 'Diseñar',
'hww.step2.timeline': 'Semanas 3-4',
'hww.step2.desc': 'Diseño de arquitectura alineado con requisitos de seguridad y cumplimiento.',
'hww.step2.deliverables.title': 'Entregables',
'hww.step2.outcomes.title': 'Resultados',
'hww.step2.deliverable1': 'Arquitectura de solución',
'hww.step2.deliverable2': 'Especificaciones de integración',
'hww.step2.deliverable3': 'Marco de gobernanza',
'hww.step2.deliverable4': 'Revisión de seguridad',
'hww.step2.outcome1': 'Diseño técnico aprobado',
'hww.step2.outcome2': 'Alcance y hitos claros',
'hww.step2.outcome3': 'Plan de mitigación de riesgos',

// Step 3
'hww.step3.title': 'Construir',
'hww.step3.timeline': 'Semanas 5-10',
'hww.step3.desc': 'Desarrollo iterativo con visibilidad continua.',
'hww.step3.deliverables.title': 'Entregables',
'hww.step3.outcomes.title': 'Resultados',
'hww.step3.deliverable1': 'Componentes funcionales',
'hww.step3.deliverable2': 'Documentación',
'hww.step3.deliverable3': 'Materiales de formación',
'hww.step3.deliverable4': 'Resultados de pruebas',
'hww.step3.outcome1': 'Sistema listo para despliegue',
'hww.step3.outcome2': 'Equipo capacitado',
'hww.step3.outcome3': 'Documentación completa',

// Step 4
'hww.step4.title': 'Operar',
'hww.step4.timeline': 'Continuo',
'hww.step4.desc': 'Gestión, monitoreo y optimización continua del sistema.',
'hww.step4.deliverables.title': 'Entregables',
'hww.step4.outcomes.title': 'Resultados',
'hww.step4.deliverable1': 'Monitoreo del sistema',
'hww.step4.deliverable2': 'Optimización del rendimiento',
'hww.step4.deliverable3': 'Mejora continua',
'hww.step4.deliverable4': 'Reportes regulares',
'hww.step4.outcome1': 'Rendimiento confiable',
'hww.step4.outcome2': 'Resultados de negocio medibles',
'hww.step4.outcome3': 'Capacidades en evolución',

// --- CTA ---
'hww.cta.title': '¿Listo para Comenzar?',
'hww.cta.description': 'Hablemos de tus objetivos y exploremos cómo nuestra metodología puede generar resultados medibles.',
'hww.cta.primary': 'Reservar Llamada de Descubrimiento',
'hww.cta.secondary': 'Ver Casos de Estudio',

// ========================================
// Capabilities — Governed Delivery Model
// ========================================


// --- Hero ---
'capabilities.gdm.hero.title': 'Modelo de Entrega Gobernado',
'capabilities.gdm.hero.description': 'Un marco de entrega unificado que garantiza que tus objetivos estratégicos se cumplan con ejecución de nivel institucional.',

// --- Overview ---
'capabilities.gdm.overview.title': 'Resumen',
'capabilities.gdm.overview.description': 'Implementamos y gestionamos un marco de entrega unificado que conecta la visión estratégica con la realidad operativa. Esto incluye definir responsabilidades claras de decisión, gestionar el cumplimiento transfronterizo e integrar herramientas fragmentadas en un sistema coherente. Nuestro modelo de entrega gobernado asegura que cada iniciativa mantenga credibilidad institucional mientras avanza a la velocidad que tu organización requiere.',

// --- What We Deliver ---
'capabilities.gdm.deliverables.title': 'Qué Entregamos',

'capabilities.gdm.deliverables.decision.title': 'Marco de Responsabilidad de Decisiones',
'capabilities.gdm.deliverables.decision.desc': 'Estructuras claras de responsabilidad que definen quién toma cada decisión, con rutas de escalamiento y puntos de control de gobernanza.',

'capabilities.gdm.deliverables.compliance.title': 'Gestión de Cumplimiento Transfronterizo',
'capabilities.gdm.deliverables.compliance.desc': 'Marcos para gestionar requisitos regulatorios en múltiples jurisdicciones manteniendo la velocidad de entrega.',

'capabilities.gdm.deliverables.tooling.title': 'Integración y Consolidación de Herramientas',
'capabilities.gdm.deliverables.tooling.desc': 'Integración de herramientas fragmentadas en un ecosistema coherente y gobernado que mejora la visibilidad y el control.',

'capabilities.gdm.deliverables.playbooks.title': 'Playbooks de Ejecución',
'capabilities.gdm.deliverables.playbooks.desc': 'Procesos estandarizados que garantizan una entrega consistente y de alta calidad en todas las iniciativas.',

'capabilities.gdm.deliverables.dashboard.title': 'Panel de Gobernanza',
'capabilities.gdm.deliverables.dashboard.desc': 'Visibilidad en tiempo real del estado de entrega, métricas de cumplimiento y auditoría de decisiones.',

'capabilities.gdm.deliverables.risk.title': 'Protocolos de Gestión de Riesgos',
'capabilities.gdm.deliverables.risk.desc': 'Identificación y mitigación proactiva de riesgos con procedimientos claros de escalamiento.',

// --- Integrations ---
'capabilities.gdm.integrations.title': 'Integraciones Típicas',
'capabilities.gdm.integrations.intro': 'Trabajamos con tu stack tecnológico existente e integramos de forma fluida con plataformas estándar del sector.',

// --- Example Deliverables ---
'capabilities.gdm.examples.title': 'Entregables de Ejemplo',
'capabilities.gdm.examples.item1': 'Documentación del marco de gobernanza de entrega',
'capabilities.gdm.examples.item2': 'Matriz de derechos de decisión y diagramas RACI',
'capabilities.gdm.examples.item3': 'Paneles de seguimiento y reporte de cumplimiento',
'capabilities.gdm.examples.item4': 'Especificaciones de arquitectura de herramientas integradas',
'capabilities.gdm.examples.item5': 'Protocolos de comunicación con stakeholders',
'capabilities.gdm.examples.item6': 'Puertas de calidad y flujos de aprobación',



// ========================================
// PÁGINA INSIGHTS
// ========================================

'insights.hero.title': 'Insights',
'insights.hero.description': 'Perspectivas sobre IA, automatización y excelencia operativa para organizaciones institucionales. Marcos prácticos, sin exageraciones.',

'insights.featured.badge': 'Destacado',
'insights.featured.category': 'Diseño UI/UX',
'insights.featured.title': 'Técnicas de Diseño UI/UX Centrado en el Usuario para Aumentar la Participación y Retención',
'insights.featured.excerpt': 'Los productos digitales de alto rendimiento crean claridad, confianza y conexión emocional.',
'insights.featured.date': '2 de Febrero de 2026',

'insights.latest.title': 'Artículos Recientes',

'insights.article1.category': 'Arquitectura Web y SEO',
'insights.article1.title': 'La Conexión Entre Arquitectura Web, SEO y Crecimiento Digital',
'insights.article1.excerpt': 'La arquitectura web es la base técnica del SEO y del crecimiento digital sostenible.',
'insights.article1.date': '06 de Febrero de 2026',

'insights.article2.category': 'Servicios IT y Consultoría',
'insights.article2.title': 'Cómo Evaluar y Elegir el Socio Adecuado de Desarrollo Web',
'insights.article2.excerpt': 'Elegir el socio correcto es una decisión estratégica a largo plazo.',
'insights.article2.date': '05 de Febrero de 2026',

'insights.article3.category': 'Servicios IT y Consultoría',
'insights.article3.title': 'Diseñando Pipelines CI/CD para Equipos de Alta Velocidad',
'insights.article3.excerpt': 'Los equipos modernos dependen de pipelines CI/CD sólidos.',
'insights.article3.date': '04 de Febrero de 2026',

'insights.article4.category': 'Servicios IT y Consultoría',
'insights.article4.title': 'Fundamentos IT Modernos: Requisito para IA Escalable',
'insights.article4.excerpt': 'La IA escalable requiere fundamentos tecnológicos sólidos.',
'insights.article4.date': '03 de Febrero de 2026',

'insights.article5.category': 'Diseño UI/UX',
'insights.article5.title': 'Técnicas UI/UX Centrado en el Usuario',
'insights.article5.excerpt': 'El diseño centrado en el usuario impulsa la participación sostenida.',
'insights.article5.date': '02 de Febrero de 2026',

'insights.article6.category': 'Estrategia de IA',
'insights.article6.title': 'Preparación para IA en Operaciones Institucionales',
'insights.article6.excerpt': 'El éxito en IA depende de fundamentos organizacionales sólidos.',
'insights.article6.date': '15 de Enero de 2026',


// ========================================
// CASE STUDY PAGE
// ========================================
// Automating Fund Administration
// ========================================

// --- Hero ---
'caseStudy.fundAdmin.meta.tag1': 'Automatización de Procesos',
'caseStudy.fundAdmin.meta.tag2': 'Integración de Sistemas',
'caseStudy.fundAdmin.meta.tag3': 'Gestor de Activos Alternativos',
'caseStudy.fundAdmin.title': 'Automatización de la Administración de Fondos para un Gestor de Activos Alternativos de $12B',
'caseStudy.fundAdmin.subtitle': 'Cómo redujimos el tiempo de cierre trimestral en un 60% y eliminamos los errores de conciliación manual mediante la automatización inteligente de flujos de trabajo.',

// --- Metrics Bar ---
'caseStudy.fundAdmin.metrics.item1.value': '60%',
'caseStudy.fundAdmin.metrics.item1.label': 'Reducción en el Tiempo de Cierre',
'caseStudy.fundAdmin.metrics.item2.value': '100%',
'caseStudy.fundAdmin.metrics.item2.label': 'Eliminación de Errores',
'caseStudy.fundAdmin.metrics.item3.value': '$1.2M',
'caseStudy.fundAdmin.metrics.item3.label': 'Ahorros Anuales',
'caseStudy.fundAdmin.metrics.item4.value': '14 Semanas',
'caseStudy.fundAdmin.metrics.item4.label': 'Tiempo hasta Generar Valor',

// --- Context ---
'caseStudy.fundAdmin.context.label': 'El Contexto',
'caseStudy.fundAdmin.context.title': 'Un Fondo en Crecimiento con Problemas de Crecimiento',
'caseStudy.fundAdmin.context.p1': 'Un gestor de activos alternativos del segmento mid-market con $12B en AUM estaba experimentando una presión operativa significativa. Sus procesos de administración de fondos—construidos sobre hojas de cálculo y flujos de trabajo manuales durante una década—no podían seguir el ritmo de su trayectoria de crecimiento.',
'caseStudy.fundAdmin.context.p2': 'Con planes para lanzar tres nuevos vehículos de fondos en los próximos 18 meses, la dirección reconoció que escalar sus procesos actuales requeriría aumentos proporcionales de personal e introduciría niveles de riesgo inaceptables.',

// --- Challenge ---
'caseStudy.fundAdmin.challenge.label': 'El Desafío',
'caseStudy.fundAdmin.challenge.title': 'Procesos Manuales a Escala Institucional',
'caseStudy.fundAdmin.challenge.intro': 'El equipo de administración de fondos enfrentaba múltiples desafíos interconectados que se acumulaban cada trimestre:',

'caseStudy.fundAdmin.challenge.item1': 'Fragmentación de datos: Los datos de los inversionistas estaban distribuidos en 7 sistemas diferentes sin una única fuente de verdad, generando pesadillas de conciliación.',
'caseStudy.fundAdmin.challenge.item2': 'Llamadas de capital manuales: Cada llamada de capital requería más de 40 horas de preparación manual de datos, validación y distribución.',
'caseStudy.fundAdmin.challenge.item3': 'Reportes propensos a errores: Los estados trimestrales para inversionistas promediaban entre 3 y 5 errores por ciclo, dañando las relaciones con los LP y requiriendo una extensa remediación.',
'caseStudy.fundAdmin.challenge.item4': 'Exposición a auditoría: La falta de documentación de procesos y trazabilidad generaba riesgo de cumplimiento y extendía los ciclos de auditoría en un 30%.',

// --- Approach ---
'caseStudy.fundAdmin.approach.label': 'Nuestro Enfoque',
'caseStudy.fundAdmin.approach.title': 'Automatización por Fases con Gobernanza Integrada',
'caseStudy.fundAdmin.approach.intro': 'Diseñamos un proyecto de 14 semanas estructurado en torno a victorias rápidas y cambios sostenibles, no una transformación multianual que perdería impulso.',

// Phase 1
'caseStudy.fundAdmin.phase1.title': 'Descubrimiento y Mapeo de Procesos',
'caseStudy.fundAdmin.phase1.duration': 'Semanas 1-2',
'caseStudy.fundAdmin.phase1.desc': 'Análisis profundo de los flujos de trabajo existentes, el panorama de sistemas y los puntos críticos. Entrevistamos a 12 stakeholders y documentamos 47 pasos de proceso distintos a lo largo del ciclo de vida de la administración de fondos.',
'caseStudy.fundAdmin.phase1.deliverables.title': 'Entregables',
'caseStudy.fundAdmin.phase1.deliverables.item1': 'Mapas de procesos del estado actual',
'caseStudy.fundAdmin.phase1.deliverables.item2': 'Auditoría de integración de sistemas',
'caseStudy.fundAdmin.phase1.deliverables.item3': 'Matriz de oportunidades de automatización',
'caseStudy.fundAdmin.phase1.deliverables.item4': 'Evaluación de riesgos',

// Phase 2
'caseStudy.fundAdmin.phase2.title': 'Arquitectura e Integración de Datos',
'caseStudy.fundAdmin.phase2.duration': 'Semanas 3-6',
'caseStudy.fundAdmin.phase2.desc': 'Construimos una capa de datos unificada que conectó los 7 sistemas fuente. Implementamos sincronización en tiempo real con resolución de conflictos y establecimos la única fuente de verdad que el equipo necesitaba urgentemente.',
'caseStudy.fundAdmin.phase2.deliverables.title': 'Entregables',
'caseStudy.fundAdmin.phase2.deliverables.item1': 'Arquitectura de integración',
'caseStudy.fundAdmin.phase2.deliverables.item2': 'Reglas de validación de datos',
'caseStudy.fundAdmin.phase2.deliverables.item3': 'Panel de monitoreo de sincronización',
'caseStudy.fundAdmin.phase2.deliverables.item4': 'Procedimientos de reversión',

// Phase 3
'caseStudy.fundAdmin.phase3.title': 'Automatización de Flujos de Trabajo',
'caseStudy.fundAdmin.phase3.duration': 'Semanas 7-11',
'caseStudy.fundAdmin.phase3.desc': 'Implementamos automatización inteligente para llamadas de capital, distribuciones y reportes a inversionistas. Incorporamos puntos de control humanos para decisiones de alto valor mientras automatizábamos validaciones rutinarias.',
'caseStudy.fundAdmin.phase3.deliverables.title': 'Entregables',
'caseStudy.fundAdmin.phase3.deliverables.item1': 'Motor automatizado de llamadas de capital',
'caseStudy.fundAdmin.phase3.deliverables.item2': 'Calculadora de distribuciones',
'caseStudy.fundAdmin.phase3.deliverables.item3': 'Generador de estados',
'caseStudy.fundAdmin.phase3.deliverables.item4': 'Flujos de manejo de excepciones',

// Phase 4
'caseStudy.fundAdmin.phase4.title': 'Gobernanza y Transferencia',
'caseStudy.fundAdmin.phase4.duration': 'Semanas 12-14',
'caseStudy.fundAdmin.phase4.desc': 'Establecimos manuales operativos, capacitamos a los equipos internos e implementamos paneles de monitoreo. Aseguramos que el cliente pudiera mantener y ampliar la solución de forma independiente.',
'caseStudy.fundAdmin.phase4.deliverables.title': 'Entregables',
'caseStudy.fundAdmin.phase4.deliverables.item1': 'Manual operativo',
'caseStudy.fundAdmin.phase4.deliverables.item2': 'Sesiones de capacitación del equipo',
'caseStudy.fundAdmin.phase4.deliverables.item3': 'Paneles de KPI',
'caseStudy.fundAdmin.phase4.deliverables.item4': 'Procedimientos de escalamiento',

// --- Results ---
'caseStudy.fundAdmin.results.label': 'Los Resultados',
'caseStudy.fundAdmin.results.title': 'Impacto Medible, Valor Sostenido',

'caseStudy.fundAdmin.results.item1.before': '12 días',
'caseStudy.fundAdmin.results.item1.after': '5 días',
'caseStudy.fundAdmin.results.item1.label': 'Tiempo de cierre trimestral reducido en un 60%',

'caseStudy.fundAdmin.results.item2.before': '3-5 errores',
'caseStudy.fundAdmin.results.item2.after': '0 errores',
'caseStudy.fundAdmin.results.item2.label': 'Cero errores en estados durante 4 trimestres consecutivos',

'caseStudy.fundAdmin.results.item3.before': '40+ horas',
'caseStudy.fundAdmin.results.item3.after': '4 horas',
'caseStudy.fundAdmin.results.item3.label': 'Tiempo de preparación de llamadas de capital reducido en un 90%',

'caseStudy.fundAdmin.results.item4.before': '6 FTEs',
'caseStudy.fundAdmin.results.item4.after': '2 FTEs',
'caseStudy.fundAdmin.results.item4.label': 'El equipo se reenfocó en relaciones estratégicas con inversionistas',

// --- Testimonial ---
'caseStudy.fundAdmin.testimonial.quote': 'Synexum no solo automatizó nuestros procesos, nos ayudó a reinventar cómo debería funcionar la administración de fondos. El equipo que liberamos ahora se enfoca en relaciones con LP en lugar de conciliación en hojas de cálculo.',
'caseStudy.fundAdmin.testimonial.authorName': 'Director de Operaciones',
'caseStudy.fundAdmin.testimonial.authorTitle': 'Gestor de Activos Alternativos',

// --- CTA ---
'caseStudy.fundAdmin.cta.title': '¿Enfrenta Desafíos Similares?',
'caseStudy.fundAdmin.cta.desc': 'Conversemos sobre cómo la automatización inteligente puede transformar sus flujos operativos y liberar a su equipo para enfocarse en lo que realmente importa.',
'caseStudy.fundAdmin.cta.primary': 'Programar una Consulta',
'caseStudy.fundAdmin.cta.secondary': 'Ver Más Casos de Estudio',

// ========================================
// INSIGHTS ARTICLE
// AI Readiness
// ========================================

// --- Hero ---
'insights.aiReadiness.hero.category': 'Estrategia de IA',
'insights.aiReadiness.hero.date': '15 de Enero de 2026',
'insights.aiReadiness.hero.title': 'Preparación para la IA en Operaciones Institucionales: Un Marco Práctico',
'insights.aiReadiness.hero.excerpt': 'La mayoría de las iniciativas de IA fracasan no por limitaciones tecnológicas, sino porque las organizaciones carecen de los elementos fundamentales para una adopción exitosa. Aquí explicamos cómo evaluar y construir una verdadera preparación para la IA.',

// --- Body Intro ---
'insights.aiReadiness.body.intro.p1': 'El ciclo de entusiasmo por la IA ha alcanzado su punto máximo, pero el trabajo real apenas comienza. Después de años de experimentación, las organizaciones institucionales están pasando de pruebas de concepto a producción, y descubren que la tecnología rara vez es el principal obstáculo. Las organizaciones que tienen éxito con la IA comparten algo en común: invirtieron en preparación antes de apresurarse a la implementación.',

// --- Section: Why Initiatives Fail ---
'insights.aiReadiness.body.fail.title': 'Por Qué la Mayoría de las Iniciativas de IA Fracasan',
'insights.aiReadiness.body.fail.p1': 'Según investigaciones recientes del sector, aproximadamente el 85% de los proyectos de IA nunca llegan a producción. Las razones son notablemente consistentes en distintas industrias y tamaños de organización:',
'insights.aiReadiness.body.fail.item1.title': 'Problemas de calidad de datos:',
'insights.aiReadiness.body.fail.item1.desc': 'Los sistemas de IA solo son tan buenos como los datos con los que se entrenan. Datos fragmentados, inconsistentes o incompletos generan modelos que no pueden ser confiables para decisiones críticas.',
'insights.aiReadiness.body.fail.item2.title': 'Falta de responsabilidad clara:',
'insights.aiReadiness.body.fail.item2.desc': 'Cuando las iniciativas de IA se sitúan entre TI y las unidades de negocio, surgen vacíos de responsabilidad. Los proyectos se estancan esperando decisiones que nadie se siente autorizado a tomar.',
'insights.aiReadiness.body.fail.item3.title': 'Complejidad de integración:',
'insights.aiReadiness.body.fail.item3.desc': 'Las herramientas de IA aisladas que no se conectan con los flujos de trabajo existentes generan fricción. Los usuarios vuelven a procesos conocidos en lugar de adoptar nuevos.',
'insights.aiReadiness.body.fail.item4.title': 'Vacíos de gobernanza:',
'insights.aiReadiness.body.fail.item4.desc': 'Sin políticas claras para el uso de la IA, las organizaciones enfrentan riesgos de cumplimiento y resultados inconsistentes entre equipos.',

// --- Quote ---
'insights.aiReadiness.body.quote': 'Las organizaciones que tienen éxito con la IA la tratan como una capacidad operativa, no como un proyecto tecnológico. Construyen primero la base y luego escalan lo que funciona.',

// --- Section: Four Pillars ---
'insights.aiReadiness.body.pillars.title': 'Los Cuatro Pilares de la Preparación para la IA',
'insights.aiReadiness.body.pillars.p1': 'La verdadera preparación para la IA no es una lista de verificación, sino una capacidad continua que evoluciona junto con la organización. Hemos desarrollado un marco basado en el trabajo con decenas de clientes institucionales que se centra en cuatro pilares interconectados:',

// --- Pillar 1 ---
'insights.aiReadiness.body.data.title': '1. Base de Datos',
'insights.aiReadiness.body.data.p1': 'Antes de cualquier iniciativa de IA, las organizaciones necesitan claridad sobre su ecosistema de datos. Esto implica comprender no solo qué datos existen, sino su calidad, accesibilidad y gobernanza. Preguntas clave:',
'insights.aiReadiness.body.data.q1': '¿Dónde residen los datos operativos críticos y quién es responsable de ellos?',
'insights.aiReadiness.body.data.q2': '¿Qué problemas de calidad de datos existen y qué tan significativos son?',
'insights.aiReadiness.body.data.q3': '¿Se puede acceder a los datos de forma programática o se requiere extracción manual?',
'insights.aiReadiness.body.data.q4': '¿Qué restricciones de privacidad y cumplimiento se aplican a los distintos conjuntos de datos?',

// --- Callout ---
'insights.aiReadiness.body.callout.title': 'Evaluación Rápida: Base de Datos',
'insights.aiReadiness.body.callout.item1': '¿Puede generar un inventario completo de fuentes de datos operativos en 24 horas?',
'insights.aiReadiness.body.callout.item2': '¿Cuenta con métricas documentadas de calidad de datos para los sistemas críticos?',
'insights.aiReadiness.body.callout.item3': '¿Existe un único responsable de la gobernanza de datos a nivel empresarial?',

// --- Pillar 2 ---
'insights.aiReadiness.body.process.title': '2. Claridad de Procesos',
'insights.aiReadiness.body.process.p1': 'La IA complementa los flujos de trabajo humanos; no los reemplaza por completo. Las organizaciones necesitan procesos documentados y estandarizados antes de poder automatizarlos o mejorarlos eficazmente. Sin claridad de procesos, las implementaciones de IA generan nuevas variaciones en lugar de mejoras consistentes.',
'insights.aiReadiness.body.process.p2': 'Las iniciativas de IA más exitosas se enfocan en procesos que son:',
'insights.aiReadiness.body.process.item1': 'Bien documentados con entradas y salidas claras',
'insights.aiReadiness.body.process.item2': 'Ejecutados con la frecuencia suficiente para generar datos de entrenamiento',
'insights.aiReadiness.body.process.item3': 'Lo suficientemente valiosos como para justificar la inversión en automatización',
'insights.aiReadiness.body.process.item4': 'Lo suficientemente estables como para que la IA no requiera reentrenamiento constante',

// --- Pillar 3 ---
'insights.aiReadiness.body.alignment.title': '3. Alineación Organizacional',
'insights.aiReadiness.body.alignment.p1': 'Las iniciativas de IA que permanecen en silos de TI rara vez tienen éxito. La adopción sostenible de la IA requiere alineación entre tecnología, operaciones, riesgo y liderazgo empresarial. Esto implica establecer:',
'insights.aiReadiness.body.alignment.item1.title': 'Patrocinio ejecutivo:',
'insights.aiReadiness.body.alignment.item1.desc': 'Un líder senior responsable de los resultados de la IA, no solo de las actividades',
'insights.aiReadiness.body.alignment.item2.title': 'Gobernanza transversal:',
'insights.aiReadiness.body.alignment.item2.desc': 'Estructuras de toma de decisiones que incluyan a todas las partes interesadas',
'insights.aiReadiness.body.alignment.item3.title': 'Desarrollo de habilidades:',
'insights.aiReadiness.body.alignment.item3.desc': 'Programas de formación que impulsen la alfabetización en IA en toda la organización',
'insights.aiReadiness.body.alignment.item4.title': 'Gestión del cambio:',
'insights.aiReadiness.body.alignment.item4.desc': 'Comunicación proactiva sobre cómo la IA afectará roles y flujos de trabajo',

// --- Pillar 4 ---
'insights.aiReadiness.body.infrastructure.title': '4. Infraestructura Técnica',
'insights.aiReadiness.body.infrastructure.p1': 'Finalmente, las organizaciones necesitan una base técnica para desarrollar, implementar y monitorear sistemas de IA. Esto no significa comprar las herramientas más recientes, sino contar con una infraestructura que permita experimentación, integración y gobernanza.',

// --- Key Takeaways ---
'insights.aiReadiness.body.takeaways.title': 'Conclusiones Clave',
'insights.aiReadiness.body.takeaways.item1': 'El 85% de los proyectos de IA fracasan, generalmente por brechas fundamentales y no por limitaciones tecnológicas',
'insights.aiReadiness.body.takeaways.item2': 'La preparación para la IA requiere inversión en datos, procesos, organización e infraestructura',
'insights.aiReadiness.body.takeaways.item3': 'Comience con una evaluación honesta de las capacidades actuales antes de seleccionar casos de uso de IA',
'insights.aiReadiness.body.takeaways.item4': 'Trate la IA como una capacidad operativa que evoluciona, no como un proyecto único',

// --- Getting Started ---
'insights.aiReadiness.body.gettingStarted.title': 'Cómo Empezar: La Evaluación de Preparación',
'insights.aiReadiness.body.gettingStarted.p1': 'Para las organizaciones que inician su camino en la IA — o que buscan reiniciar después de iniciativas fallidas — recomendamos comenzar con una evaluación estructurada de preparación. No se trata de compararse con un estándar arbitrario, sino de identificar las brechas específicas que descarrilarán sus iniciativas si no se abordan.',
'insights.aiReadiness.body.gettingStarted.p2': 'Una evaluación integral suele tomar de 2 a 3 semanas y produce una hoja de ruta priorizada para construir la preparación en IA. El resultado no es una recomendación tecnológica, sino una visión honesta de las capacidades organizacionales y un camino práctico a seguir.',
'insights.aiReadiness.body.gettingStarted.p3': 'Las organizaciones que invierten en preparación antes de apresurarse a implementar obtienen consistentemente mejores resultados: menor tiempo para generar valor, mayores tasas de adopción y resultados sostenibles que se potencian con el tiempo.',

// --- Sidebar ---
'insights.aiReadiness.sidebar.tocTitle': 'En Este Artículo',
'insights.aiReadiness.sidebar.shareTitle': 'Compartir Este Artículo',
'insights.aiReadiness.sidebar.copyFeedback': '¡Enlace copiado!',
'insights.aiReadiness.sidebar.share.linkedin': 'Compartir en LinkedIn',
'insights.aiReadiness.sidebar.share.twitter': 'Compartir en Twitter',
'insights.aiReadiness.sidebar.share.facebook': 'Compartir en Facebook',
'insights.aiReadiness.sidebar.share.copy': 'Copiar enlace',

// ========================================
// LEGAL PAGE
// Privacy Policy
// ========================================

// --- Header ---
'legal.privacy.hero.title': 'Política de Privacidad',
'legal.privacy.hero.lastUpdated': 'Última actualización: 28 de Enero de 2026',

// --- Effective Entity ---
'legal.privacy.entity.title': 'Entidad Responsable',
'legal.privacy.entity.description': 'Esta Política de Privacidad se aplica a Synexum Labs, operado por Coigne Capital Inc.',
'legal.privacy.entity.companyName': 'Coigne Capital Inc.',
'legal.privacy.entity.address': '555 Bd Dr.-Frederik-Philips, Saint-Laurent, Quebec, Canadá',
'legal.privacy.entity.emailLabel': 'Correo electrónico:',
'legal.privacy.entity.email': 'support@synexumlabs.com',
'legal.privacy.entity.phoneLabel': 'Teléfono:',
'legal.privacy.entity.phone': '+1 (514) 351-5101',

// --- Information We Collect ---
'legal.privacy.collection.title': 'Información que Recopilamos',
'legal.privacy.collection.item1': 'Información de contacto (nombre, correo electrónico, teléfono)',
'legal.privacy.collection.item2': 'Información de programación y reservas',
'legal.privacy.collection.item3': 'Suscripciones a boletines informativos',
'legal.privacy.collection.item4': 'Analítica web y cookies',
'legal.privacy.collection.item5': 'Datos empresariales del cliente durante la prestación de servicios (incluyendo código, credenciales y acceso a sistemas cuando sea necesario)',

// --- Purpose of Collection ---
'legal.privacy.purpose.title': 'Finalidad de la Recopilación',
'legal.privacy.purpose.intro': 'La información se recopila para:',
'legal.privacy.purpose.item1': 'Responder a consultas',
'legal.privacy.purpose.item2': 'Prestar los servicios contratados',
'legal.privacy.purpose.item3': 'Proporcionar actualizaciones de proyectos y comunicaciones',
'legal.privacy.purpose.item4': 'Mejorar los servicios y la funcionalidad del sitio web',
'legal.privacy.purpose.item5': 'Cumplir con obligaciones legales y contractuales',

// --- Data Storage & Transfers ---
'legal.privacy.storage.title': 'Almacenamiento y Transferencias de Datos',
'legal.privacy.storage.p1': 'Los datos pueden almacenarse y procesarse en Canadá y Estados Unidos, incluyendo infraestructura de Amazon Web Services (AWS).',
'legal.privacy.storage.p2': 'La información personal puede transferirse fuera de Canadá. Se implementan las salvaguardas apropiadas de acuerdo con las leyes de privacidad aplicables.',

// --- Data Retention ---
'legal.privacy.retention.title': 'Conservación de Datos',
'legal.privacy.retention.p1': 'Los datos personales y empresariales se conservan únicamente durante el tiempo necesario para cumplir con requisitos contractuales, legales u operativos.',

// --- Your Rights ---
'legal.privacy.rights.title': 'Sus Derechos',
'legal.privacy.rights.intro': 'Usted puede solicitar:',
'legal.privacy.rights.item1': 'Acceso a sus datos personales',
'legal.privacy.rights.item2': 'Corrección o eliminación de sus datos',
'legal.privacy.rights.item3': 'Retiro de su consentimiento',
'legal.privacy.rights.item4': 'Exclusión de comunicaciones de marketing',
'legal.privacy.rights.contactText': 'Las solicitudes pueden enviarse a:',
'legal.privacy.rights.email': 'support@synexumlabs.com',

// --- Privacy Officer ---
'legal.privacy.officer.title': 'Oficial de Privacidad',
'legal.privacy.officer.intro': 'Las consultas y solicitudes relacionadas con la privacidad deben dirigirse a:',
'legal.privacy.officer.name': 'Oficial de Privacidad – Coigne Capital Inc.',
'legal.privacy.officer.emailLabel': 'Correo electrónico:',
'legal.privacy.officer.email': 'support@synexumlabs.com',

// --- Electronic Communications ---
'legal.privacy.communications.title': 'Comunicaciones Electrónicas',
'legal.privacy.communications.p1': 'Synexum Labs y Coigne Capital Inc. pueden enviar comunicaciones electrónicas, incluyendo mensajes de marketing, boletines informativos y actualizaciones de proyectos.',
'legal.privacy.communications.p2': 'Todas las comunicaciones cumplen con la legislación canadiense contra el spam (CASL) y las regulaciones aplicables de Estados Unidos. Cada mensaje incluye la identificación del remitente y un mecanismo para cancelar la suscripción.',
'legal.privacy.communications.p3': 'Puede retirar su consentimiento en cualquier momento utilizando el enlace de cancelación de suscripción o contactándonos directamente.',

// ========================================
// LEGAL PAGE
// Terms of Service
// ========================================

// --- Header ---
'legal.terms.hero.title': 'Términos del Servicio',
'legal.terms.hero.lastUpdated': 'Última actualización: 28 de Enero de 2026',

// --- Governing Entity ---
'legal.terms.entity.title': 'Entidad Responsable',
'legal.terms.entity.p1': 'Todos los servicios proporcionados bajo la marca Synexum Labs son ofrecidos por Coigne Capital Inc., constituida en Quebec, Canadá.',

// --- Scope of Services ---
'legal.terms.scope.title': 'Alcance de los Servicios',
'legal.terms.scope.intro': 'Los servicios incluyen, entre otros:',
'legal.terms.scope.item1': 'Desarrollo de software personalizado',
'legal.terms.scope.item2': 'Aplicaciones web y en la nube',
'legal.terms.scope.item3': 'Sistemas de automatización y flujos de trabajo',
'legal.terms.scope.item4': 'Integración de inteligencia artificial',
'legal.terms.scope.item5': 'Analítica de datos y paneles de control',
'legal.terms.scope.item6': 'Infraestructura y soporte DevOps',
'legal.terms.scope.item7': 'Servicios de asesoría digital y técnica',

// --- No Guarantees ---
'legal.terms.noGuarantees.title': 'Sin Garantías',
'legal.terms.noGuarantees.p1': 'Synexum Labs no garantiza resultados, tiempo de actividad, métricas de rendimiento, disponibilidad del sistema ni resultados comerciales. Los acuerdos de nivel de servicio (SLA), cuando correspondan, se proporcionan exclusivamente mediante contrato escrito.',

// --- Hosting & Infrastructure ---
'legal.terms.infrastructure.title': 'Alojamiento e Infraestructura',
'legal.terms.infrastructure.p1': 'El trabajo de desarrollo puede alojarse temporalmente en infraestructura ubicada en los Estados Unidos durante las fases de desarrollo o realizarse directamente en entornos proporcionados por el cliente, según lo acordado contractualmente.',

// --- Intellectual Property ---
'legal.terms.ip.title': 'Propiedad Intelectual',
'legal.terms.ip.p1': 'La propiedad de los entregables, el código y la propiedad intelectual se rige exclusivamente por el acuerdo escrito aplicable. En ausencia de un acuerdo escrito, toda la propiedad intelectual seguirá siendo propiedad de Coigne Capital Inc.',

// --- Limitation of Liability ---
'legal.terms.liability.title': 'Limitación de Responsabilidad',
'legal.terms.liability.p1': 'En la máxima medida permitida por la ley, Coigne Capital Inc. y sus afiliados no serán responsables por daños indirectos, incidentales, consecuentes, especiales o punitivos.',

// --- Dispute Resolution ---
'legal.terms.dispute.title': 'Resolución de Disputas',
'legal.terms.dispute.p1': 'Cualquier disputa se resolverá primero mediante mediación de buena fe y posteriormente mediante arbitraje vinculante. La ley aplicable será la de la Provincia de Quebec y las leyes federales de Canadá aplicables, salvo que se acuerde lo contrario por escrito.',

// --- Contact Information ---
'legal.terms.contact.title': 'Información de Contacto',
'legal.terms.contact.intro': 'Si tiene preguntas sobre estos Términos del Servicio, contáctenos:',
'legal.terms.contact.company': 'Coigne Capital Inc.',
'legal.terms.contact.address': '555 Bd Dr.-Frederik-Philips, Saint-Laurent, Quebec, Canadá',
'legal.terms.contact.emailLabel': 'Correo electrónico:',
'legal.terms.contact.email': 'info@synexumlabs.com',
'legal.terms.contact.phoneLabel': 'Teléfono:',
'legal.terms.contact.phone': '+1 (514) 351-5101',
'legal.terms.contact.generalInquiries': 'Consultas generales:',
'legal.terms.contact.contactForm': 'Formulario de contacto',

// ========================================
// LEGAL PAGE
// Legal Disclaimer
// ========================================

// --- Header ---
'legal.disclaimer.hero.title': 'Aviso Legal',
'legal.disclaimer.hero.lastUpdated': 'Última actualización: 28 de Enero de 2026',

// --- Relationship Disclosure ---
'legal.disclaimer.relationship.title': 'Divulgación de Relación',
'legal.disclaimer.relationship.p1': 'Synexum Labs es una sub-marca de tecnología y transformación digital de Coigne Capital Inc., una corporación constituida bajo las leyes de Canadá y registrada en la Provincia de Quebec.',
'legal.disclaimer.relationship.p2': 'Synexum Labs opera como una división dedicada a la transformación digital, desarrollo de software y automatización dentro del ecosistema de Coigne Capital. Los servicios prestados bajo la marca Synexum Labs son contratados a través de Coigne Capital Inc., salvo que se indique expresamente lo contrario por escrito.',
'legal.disclaimer.relationship.p3': 'Synexum Labs opera conforme a un acuerdo formal de desarrollo comercial y estratégico entre Coigne Capital Inc. y Happy People AI, bajo el cual Happy People AI actúa como colaborador tecnológico estratégico y socio de desarrollo.',
'legal.disclaimer.relationship.p4': 'El modelo de desarrollo y entrega de Synexum Labs es descentralizado e incluye miembros del equipo y colaboradores ubicados en Canadá, Estados Unidos, India y determinadas jurisdicciones de América Latina.',
'legal.disclaimer.relationship.p5': 'Cada entidad dentro de este ecosistema opera de forma independiente. Nada en este sitio web deberá interpretarse como la creación de una sociedad, empresa conjunta, relación fiduciaria o relación de agencia más allá de lo expresamente definido en acuerdos escritos.',

// --- Professional & Regulatory Disclaimer ---
'legal.disclaimer.professional.title': 'Aviso Profesional y Regulatorio',
'legal.disclaimer.professional.p1': 'Synexum Labs es el brazo de transformación digital y prestación tecnológica de Coigne Capital Inc. Los servicios incluyen desarrollo de software personalizado, aplicaciones web, sistemas de automatización, integración de IA, analítica de datos, soporte de infraestructura y servicios de asesoría digital.',
'legal.disclaimer.professional.p2': 'Ni Synexum Labs ni Coigne Capital Inc. son asesores de inversión registrados, corredores, distribuidores o intermediarios de valores. Ningún contenido de este sitio constituye asesoramiento legal, fiscal, contable, de inversión ni una solicitud de productos o servicios financieros regulados.',
'legal.disclaimer.professional.p3': 'Los servicios tecnológicos pueden apoyar a empresas que operan en sectores regulados o críticos; sin embargo, el cumplimiento normativo, la interpretación legal y el riesgo operativo siguen siendo responsabilidad exclusiva del cliente.',
'legal.disclaimer.professional.caps': 'NO SE OTORGAN GARANTÍAS—EXPRESAS O IMPLÍCITAS—INCLUYENDO, SIN LIMITACIÓN, GARANTÍAS DE COMERCIABILIDAD, IDONEIDAD PARA UN PROPÓSITO PARTICULAR, EXACTITUD O DISPONIBILIDAD ININTERRUMPIDA.',

// --- Contact Information ---
'legal.disclaimer.contact.title': 'Información de Contacto',
'legal.disclaimer.contact.intro': 'Para preguntas sobre este Aviso Legal, contáctenos:',
'legal.disclaimer.contact.company': 'Coigne Capital Inc.',
'legal.disclaimer.contact.address': '555 Bd Dr.-Frederik-Philips, Saint-Laurent, Quebec, Canadá',
'legal.disclaimer.contact.emailLabel': 'Correo electrónico:',
'legal.disclaimer.contact.email': 'info@synexumlabs.com',
'legal.disclaimer.contact.phoneLabel': 'Teléfono:',
'legal.disclaimer.contact.phone': '+1 (514) 351-5101',

// ========================================
// CAPABILITY BRIEF PAGE
// Synexum Labs – Capability Brief
// ========================================

// --- Meta ---
'capabilityBrief.meta.title': 'Synexum Labs – Informe de Capacidades',

// --- Top Bar ---
'capabilityBrief.top.back': '← Volver al sitio web',
'capabilityBrief.top.print': 'Imprimir / Guardar como PDF',
'capabilityBrief.top.download': 'Descargar PDF',

// --- Header ---
'capabilityBrief.header.title': 'Informe de Capacidades',
'capabilityBrief.header.subtitle': 'Sistemas Inteligentes para Operaciones Institucionales',
'capabilityBrief.header.logoAlt': 'Logo de Synexum Labs',
'capabilityBrief.header.logoAria': 'Synexum Labs - Inicio',

// --- Executive Summary ---
'capabilityBrief.executive.title': 'Resumen Ejecutivo',
'capabilityBrief.executive.p1': 'Synexum Labs diseña, desarrolla y opera sistemas inteligentes de IA y automatización que reducen los ciclos operativos, mejoran el control y generan resultados medibles para organizaciones institucionales.',

// --- Core Capabilities ---
'capabilityBrief.capabilities.title': 'Capacidades Principales',

'capabilityBrief.capabilities.governed.title': 'Modelo de Entrega Gobernado',
'capabilityBrief.capabilities.governed.desc': 'Ejecución de nivel institucional con propiedad clara, control de cumplimiento e integración de herramientas.',

'capabilityBrief.capabilities.architecture.title': 'Arquitectura de Sistemas Evolutiva',
'capabilityBrief.capabilities.architecture.desc': 'Sistemas adaptativos que conectan datos, decisiones y ejecución bajo un marco de gobernanza.',

'capabilityBrief.capabilities.platform.title': 'Ingeniería de Plataforma Escalable',
'capabilityBrief.capabilities.platform.desc': 'Ingeniería full-stack habilitada con IA entregada mediante un modelo global gobernado.',

'capabilityBrief.capabilities.modular.title': 'Desarrollo en Células Modulares',
'capabilityBrief.capabilities.modular.desc': 'Unidades autónomas que operan dentro de un marco de gobernanza centralizado.',

'capabilityBrief.capabilities.sustainment.title': 'Soporte de Nivel Institucional',
'capabilityBrief.capabilities.sustainment.desc': 'Monitoreo continuo, soporte de cumplimiento y mejora operativa constante.',

// --- Methodology ---
'capabilityBrief.methodology.title': 'Nuestra Metodología',

'capabilityBrief.methodology.step1': 'Descubrir',
'capabilityBrief.methodology.step2': 'Diseñar',
'capabilityBrief.methodology.step3': 'Construir',
'capabilityBrief.methodology.step4': 'Operar',

// --- Proven Results ---
'capabilityBrief.results.title': 'Resultados Comprobados',

'capabilityBrief.results.item1.value': '92%',
'capabilityBrief.results.item1.label': 'Reducción de Tiempo',

'capabilityBrief.results.item2.value': '99.8%',
'capabilityBrief.results.item2.label': 'Precisión',

'capabilityBrief.results.item3.value': '4 meses',
'capabilityBrief.results.item3.label': 'Plazo de ROI',

// --- Industries ---
'capabilityBrief.industries.title': 'Industrias que Atendemos',
'capabilityBrief.industries.item1': 'Servicios Financieros',
'capabilityBrief.industries.item2': 'Salud',
'capabilityBrief.industries.item3': 'Empresas',
'capabilityBrief.industries.item4': 'Gobierno',

// --- Get Started ---
'capabilityBrief.cta.title': 'Comenzar',
'capabilityBrief.cta.p1': 'Programe una llamada de descubrimiento para explorar cómo Synexum Labs puede transformar sus operaciones.',
'capabilityBrief.cta.websiteLabel': 'Sitio web:',
'capabilityBrief.cta.website': 'synexumlabs.com',
'capabilityBrief.cta.emailLabel': 'Correo electrónico:',
'capabilityBrief.cta.email': 'support@synexumlabs.com',

// --- Footer ---
'capabilityBrief.footer.copyright': '© Coigne Capital Inc. — Synexum Labs',
'capabilityBrief.footer.confidential': 'Confidencial – Destinado únicamente a clientes potenciales.',

// ========================================
// CAPABILITIES PAGE
// Living Systems Architecture
// ========================================

// --- Hero ---
'capabilities.livingSystems.hero.title': 'Arquitectura de Sistemas Evolutivos',
'capabilities.livingSystems.hero.subtitle': 'La capa de inteligencia que conecta tus datos, decisiones y ejecución - sistemas que observan, aprenden y se adaptan.',
'capabilities.livingSystems.hero.bgAlt': 'Fondo de protección de seguros',

// --- Overview ---
'capabilities.livingSystems.overview.title': 'Descripción General',
'capabilities.livingSystems.overview.p1': 'Diseñamos y desarrollamos la capa de inteligencia que conecta tus datos, decisiones y ejecución. No se trata solo de crear aplicaciones; se trata de construir un sistema sostenible que observa lo que sucede, determina qué es relevante, activa acciones y aprende de los resultados - todo bajo un marco de gobernanza. Estos “sistemas evolutivos” forman la infraestructura de decisión que hace que tu organización sea más inteligente, ágil y responsable.',

// --- What We Deliver ---
'capabilities.livingSystems.deliver.title': 'Lo Que Entregamos',

'capabilities.livingSystems.deliver.observe.title': 'Capa de Observación',
'capabilities.livingSystems.deliver.observe.desc': 'Infraestructura de recopilación y detección de datos que captura señales operativas en tiempo real en toda tu organización.',

'capabilities.livingSystems.deliver.decide.title': 'Capa de Decisión',
'capabilities.livingSystems.deliver.decide.desc': 'Motores de decisión impulsados por IA que evalúan condiciones, aplican reglas de negocio y determinan las acciones óptimas.',

'capabilities.livingSystems.deliver.trigger.title': 'Capa de Activación',
'capabilities.livingSystems.deliver.trigger.desc': 'Orquestación de ejecución que inicia flujos de trabajo, notificaciones y respuestas automatizadas basadas en decisiones.',

'capabilities.livingSystems.deliver.learn.title': 'Capa de Aprendizaje',
'capabilities.livingSystems.deliver.learn.desc': 'Bucles de retroalimentación y componentes de aprendizaje automático que mejoran continuamente el rendimiento del sistema.',

'capabilities.livingSystems.deliver.governance.title': 'Controles de Gobernanza',
'capabilities.livingSystems.deliver.governance.desc': 'Registros de auditoría integrados, explicabilidad y puntos de control humano para decisiones críticas.',

'capabilities.livingSystems.deliver.integration.title': 'Arquitectura de Integración',
'capabilities.livingSystems.deliver.integration.desc': 'Estructura de conexión que vincula los sistemas evolutivos con tu ecosistema tecnológico existente.',

// --- Integrations ---
'capabilities.livingSystems.integrations.title': 'Integraciones Típicas',
'capabilities.livingSystems.integrations.intro': 'Trabajamos con tu stack tecnológico existente e integramos de manera fluida con plataformas estándar de la industria.',

'capabilities.livingSystems.integrations.azure': 'Azure AI',
'capabilities.livingSystems.integrations.aws': 'AWS SageMaker',
'capabilities.livingSystems.integrations.google': 'Google Cloud AI',
'capabilities.livingSystems.integrations.openai': 'OpenAI',
'capabilities.livingSystems.integrations.anthropic': 'Anthropic',
'capabilities.livingSystems.integrations.databricks': 'Databricks',
'capabilities.livingSystems.integrations.snowflake': 'Snowflake',
'capabilities.livingSystems.integrations.kafka': 'Apache Kafka',
'capabilities.livingSystems.integrations.kubernetes': 'Kubernetes',
'capabilities.livingSystems.integrations.custom': 'Pipelines de ML personalizados',

// --- Example Deliverables ---
'capabilities.livingSystems.examples.title': 'Ejemplos de Entregables',

'capabilities.livingSystems.examples.item1': 'Plano de arquitectura de sistemas evolutivos',
'capabilities.livingSystems.examples.item2': 'Diseños de flujos Observe-Decide-Trigger-Learn (ODTL)',
'capabilities.livingSystems.examples.item3': 'Especificaciones de modelos de IA y planes de entrenamiento',
'capabilities.livingSystems.examples.item4': 'Documentación de arquitectura de integración',
'capabilities.livingSystems.examples.item5': 'Marcos de gobernanza y explicabilidad',
'capabilities.livingSystems.examples.item6': 'Paneles de monitoreo de rendimiento',

// ========================================
// CAPABILITIES PAGE
// Scalable Platform Engineering
// ========================================

// --- Hero ---
'capabilities.platformEngineering.hero.title': 'Ingeniería de Plataforma Escalable',
'capabilities.platformEngineering.hero.subtitle': 'Desarrollo full-stack, integración de IA/ML, DevOps y servicios de QA con capacidad de ejecución global.',
'capabilities.platformEngineering.hero.bgAlt': 'Fondo de protección de seguros',

// --- Overview ---
'capabilities.platformEngineering.overview.title': 'Descripción General',
'capabilities.platformEngineering.overview.p1': 'Ofrecemos desarrollo full-stack, integración de IA/ML, DevOps y servicios de aseguramiento de calidad. Nuestra capacidad de ejecución global garantiza despliegues rápidos y una entrega sostenible en múltiples zonas horarias, todo dentro del marco de gobernanza del modelo Synexum. Ya sea que necesites crear nuevas aplicaciones, modernizar sistemas heredados o ampliar tu capacidad de ingeniería, entregamos con calidad y velocidad de nivel institucional.',

// --- What We Deliver ---
'capabilities.platformEngineering.deliver.title': 'Lo Que Entregamos',

'capabilities.platformEngineering.deliver.fullstack.title': 'Desarrollo Full-Stack',
'capabilities.platformEngineering.deliver.fullstack.desc': 'Desarrollo integral de aplicaciones para web, móvil y plataformas empresariales utilizando stacks tecnológicos modernos.',

'capabilities.platformEngineering.deliver.aiml.title': 'Integración de IA/ML',
'capabilities.platformEngineering.deliver.aiml.desc': 'Integración de capacidades de inteligencia artificial y aprendizaje automático en tus aplicaciones y flujos de trabajo.',

'capabilities.platformEngineering.deliver.devops.title': 'DevOps e Infraestructura en la Nube',
'capabilities.platformEngineering.deliver.devops.desc': 'Pipelines CI/CD, infraestructura como código y arquitectura en la nube para despliegues confiables y escalables.',

'capabilities.platformEngineering.deliver.qa.title': 'Aseguramiento de Calidad',
'capabilities.platformEngineering.deliver.qa.desc': 'Estrategias integrales de pruebas que incluyen pruebas automatizadas, pruebas de rendimiento y evaluaciones de seguridad.',

'capabilities.platformEngineering.deliver.api.title': 'Desarrollo de APIs',
'capabilities.platformEngineering.deliver.api.desc': 'Diseño e implementación de APIs RESTful y GraphQL para una integración de sistemas fluida.',

'capabilities.platformEngineering.deliver.legacy.title': 'Modernización de Sistemas Heredados',
'capabilities.platformEngineering.deliver.legacy.desc': 'Migración estratégica y modernización de sistemas heredados manteniendo la continuidad del negocio.',

// --- Integrations ---
'capabilities.platformEngineering.integrations.title': 'Integraciones Típicas',
'capabilities.platformEngineering.integrations.intro': 'Trabajamos con tu stack tecnológico existente e integramos de manera fluida con plataformas estándar de la industria.',

'capabilities.platformEngineering.integrations.aws': 'AWS',
'capabilities.platformEngineering.integrations.azure': 'Azure',
'capabilities.platformEngineering.integrations.google': 'Google Cloud',
'capabilities.platformEngineering.integrations.kubernetes': 'Kubernetes',
'capabilities.platformEngineering.integrations.docker': 'Docker',
'capabilities.platformEngineering.integrations.terraform': 'Terraform',
'capabilities.platformEngineering.integrations.github': 'GitHub Actions',
'capabilities.platformEngineering.integrations.jenkins': 'Jenkins',
'capabilities.platformEngineering.integrations.react': 'React',
'capabilities.platformEngineering.integrations.node': 'Node.js',
'capabilities.platformEngineering.integrations.python': 'Python',
'capabilities.platformEngineering.integrations.dotnet': '.NET',

// --- Example Deliverables ---
'capabilities.platformEngineering.examples.title': 'Ejemplos de Entregables',

'capabilities.platformEngineering.examples.item1': 'Aplicaciones y microservicios listos para producción',
'capabilities.platformEngineering.examples.item2': 'Configuraciones de pipelines CI/CD',
'capabilities.platformEngineering.examples.item3': 'Arquitectura de infraestructura en la nube',
'capabilities.platformEngineering.examples.item4': 'Documentación y especificaciones de APIs',
'capabilities.platformEngineering.examples.item5': 'Suites de pruebas automatizadas',
'capabilities.platformEngineering.examples.item6': 'Informes de optimización de rendimiento',

// ========================================
// CAPABILITIES PAGE
// Modular Cell Development
// ========================================

// --- Hero ---
'capabilities.modularCell.hero.title': 'Desarrollo de Células Modulares',
'capabilities.modularCell.hero.subtitle': 'Unidades de ejecución específicas por dominio que operan con autonomía y velocidad mientras heredan la gobernanza del Core/Grid.',
'capabilities.modularCell.hero.bgAlt': 'Fondo de protección de seguros',

// --- Overview ---
'capabilities.modularCell.overview.title': 'Descripción General',
'capabilities.modularCell.overview.p1': "Construimos unidades de ejecución específicas por dominio ('Células') para funciones como Finanzas, Operaciones y Analítica. Cada Célula opera con autonomía y velocidad, pero hereda sus estándares de gobernanza y cumplimiento del 'Core/Grid' central, lo que te permite escalar sin sacrificar el control. Esta arquitectura resuelve la paradoja de la escalabilidad: cómo aumentar la capacidad de ejecución sin perder gobernanza, responsabilidad ni coherencia institucional.",

// --- What We Deliver ---
'capabilities.modularCell.deliver.title': 'Lo Que Entregamos',

'capabilities.modularCell.deliver.core.title': 'Arquitectura Core/Grid',
'capabilities.modularCell.deliver.core.desc': 'Capa central de gobernanza que define estándares, políticas y requisitos de cumplimiento heredados por todas las Células.',

'capabilities.modularCell.deliver.cells.title': 'Células Específicas por Dominio',
'capabilities.modularCell.deliver.cells.desc': 'Unidades de ejecución autónomas adaptadas a funciones específicas como Finanzas, Operaciones, RR. HH. o Analítica.',

'capabilities.modularCell.deliver.inheritance.title': 'Herencia de Gobernanza de las Células',
'capabilities.modularCell.deliver.inheritance.desc': 'Mecanismos que garantizan que cada Célula herede y aplique automáticamente los estándares de gobernanza del Core/Grid.',

'capabilities.modularCell.deliver.communication.title': 'Comunicación Inter-Células',
'capabilities.modularCell.deliver.communication.desc': 'Interfaces seguras y gobernadas para el intercambio de datos y flujos de trabajo entre Células.',

'capabilities.modularCell.deliver.monitoring.title': 'Monitoreo del Rendimiento de las Células',
'capabilities.modularCell.deliver.monitoring.desc': 'Paneles e indicadores que supervisan el rendimiento, cumplimiento y salud operativa de las Células.',

'capabilities.modularCell.deliver.scaling.title': 'Guías de Escalado',
'capabilities.modularCell.deliver.scaling.desc': 'Procesos documentados para crear nuevas Células o expandir las existentes manteniendo la gobernanza.',

// --- Integrations ---
'capabilities.modularCell.integrations.title': 'Integraciones Típicas',
'capabilities.modularCell.integrations.intro': 'Trabajamos con tu stack tecnológico existente e integramos de manera fluida con plataformas estándar de la industria.',

'capabilities.modularCell.integrations.kubernetes': 'Kubernetes',
'capabilities.modularCell.integrations.docker': 'Docker',
'capabilities.modularCell.integrations.kafka': 'Apache Kafka',
'capabilities.modularCell.integrations.rabbitmq': 'RabbitMQ',
'capabilities.modularCell.integrations.terraform': 'Terraform',
'capabilities.modularCell.integrations.consul': 'Consul',
'capabilities.modularCell.integrations.vault': 'Vault',
'capabilities.modularCell.integrations.prometheus': 'Prometheus',
'capabilities.modularCell.integrations.grafana': 'Grafana',
'capabilities.modularCell.integrations.custom': 'Orquestación Personalizada',

// --- Example Deliverables ---
'capabilities.modularCell.examples.title': 'Ejemplos de Entregables',

'capabilities.modularCell.examples.item1': 'Especificaciones de la arquitectura Core/Grid',
'capabilities.modularCell.examples.item2': 'Planos de Células para cada dominio',
'capabilities.modularCell.examples.item3': 'Documentación de herencia de gobernanza',
'capabilities.modularCell.examples.item4': 'Contratos de API inter-Células',
'capabilities.modularCell.examples.item5': 'Configuraciones de monitoreo y alertas',
'capabilities.modularCell.examples.item6': 'Runbooks de escalado y despliegue de Células',


// ========================================
// CAPABILITIES PAGE
// Institutional-Grade Sustainment
// ========================================

// --- Hero ---
'capabilities.sustainment.hero.title': 'Sostenimiento de Nivel Institucional',
'capabilities.sustainment.hero.subtitle': 'Soporte operativo continuo que garantiza que tus sistemas permanezcan estables, cumplan con las normativas y sigan generando valor con el tiempo.',
'capabilities.sustainment.hero.bgAlt': 'Fondo de protección de seguros',

// --- Overview ---
'capabilities.sustainment.overview.title': 'Descripción General',
'capabilities.sustainment.overview.p1': 'Nuestro compromiso no termina con el lanzamiento. Proporcionamos soporte operativo continuo para garantizar que tus sistemas permanezcan estables, cumplan con las normativas y continúen generando valor con el tiempo. Gestionamos el sistema para que puedas enfocarte en tu negocio. Este sostenimiento de nivel institucional asegura que tus inversiones digitales no se deterioren, sino que mejoren continuamente y se adapten a las necesidades cambiantes del negocio.',

// --- What We Deliver ---
'capabilities.sustainment.deliver.title': 'Lo Que Entregamos',

'capabilities.sustainment.deliver.monitoring.title': 'Monitoreo de Operaciones 24/7',
'capabilities.sustainment.deliver.monitoring.desc': 'Monitoreo continuo de la salud, el rendimiento y la seguridad del sistema con respuesta inmediata ante incidentes.',

'capabilities.sustainment.deliver.maintenance.title': 'Mantenimiento Proactivo',
'capabilities.sustainment.deliver.maintenance.desc': 'Actualizaciones programadas, parches y optimizaciones que previenen problemas antes de que afecten las operaciones.',

'capabilities.sustainment.deliver.compliance.title': 'Sostenimiento de Cumplimiento',
'capabilities.sustainment.deliver.compliance.desc': 'Monitoreo continuo del cumplimiento y adaptación a requisitos regulatorios en evolución.',

'capabilities.sustainment.deliver.performance.title': 'Optimización del Rendimiento',
'capabilities.sustainment.deliver.performance.desc': 'Ajustes y mejoras continuas para garantizar que los sistemas sigan cumpliendo los objetivos de rendimiento.',

'capabilities.sustainment.deliver.capacity.title': 'Gestión de Capacidad',
'capabilities.sustainment.deliver.capacity.desc': 'Escalado proactivo y gestión de recursos para manejar el crecimiento y las fluctuaciones de demanda.',

'capabilities.sustainment.deliver.improvement.title': 'Mejora Continua',
'capabilities.sustainment.deliver.improvement.desc': 'Revisiones y mejoras periódicas que evolucionan tus sistemas basadas en aprendizajes operativos.',

// --- Integrations ---
'capabilities.sustainment.integrations.title': 'Integraciones Típicas',
'capabilities.sustainment.integrations.intro': 'Nos integramos dentro de tu ecosistema tecnológico existente y nos alineamos con plataformas empresariales y cadenas de herramientas de entrega de nivel corporativo.',

'capabilities.sustainment.integrations.pagerduty': 'PagerDuty',
'capabilities.sustainment.integrations.datadog': 'Datadog',
'capabilities.sustainment.integrations.newrelic': 'New Relic',
'capabilities.sustainment.integrations.splunk': 'Splunk',
'capabilities.sustainment.integrations.servicenow': 'ServiceNow',
'capabilities.sustainment.integrations.jira': 'Jira Service Management',
'capabilities.sustainment.integrations.cloudwatch': 'AWS CloudWatch',
'capabilities.sustainment.integrations.azuremonitor': 'Azure Monitor',
'capabilities.sustainment.integrations.prometheus': 'Prometheus',
'capabilities.sustainment.integrations.grafana': 'Grafana',

// --- Example Deliverables ---
'capabilities.sustainment.examples.title': 'Ejemplos de Entregables',

'capabilities.sustainment.examples.item1': 'Acuerdos de nivel de servicio (SLAs)',
'capabilities.sustainment.examples.item2': 'Configuraciones de monitoreo y alertas',
'capabilities.sustainment.examples.item3': 'Playbooks de respuesta a incidentes',
'capabilities.sustainment.examples.item4': 'Informes mensuales de operaciones',
'capabilities.sustainment.examples.item5': 'Documentación de auditoría de cumplimiento',
'capabilities.sustainment.examples.item6': 'Hojas de ruta de mejora continua',


// ========================================
// CASE STUDIES PAGE
// Replacing Admin Work With Automation
// ========================================

// --- Hero ---
'caseStudies.adminAutomation.hero.title': 'Reemplazando el Trabajo Administrativo con Automatización: Desglose Real de una Implementación en Go High Level',
'caseStudies.adminAutomation.hero.subtitle': 'Un desglose real de una implementación en Go High Level que muestra cómo la automatización reemplazó tareas administrativas repetitivas sin contratar más personal.',
'caseStudies.adminAutomation.hero.tag1': 'Automatización de Procesos',
'caseStudies.adminAutomation.hero.tag2': 'Operaciones',
'caseStudies.adminAutomation.hero.tag3': 'Empresa de Servicios Digitales',
'caseStudies.adminAutomation.hero.bgAlt': 'Fondo de protección de seguros',

// --- Metrics ---
'caseStudies.adminAutomation.metrics.item1.value': '60%+',
'caseStudies.adminAutomation.metrics.item1.label': 'Tareas Administrativas Automatizadas',

'caseStudies.adminAutomation.metrics.item2.value': '45%↓',
'caseStudies.adminAutomation.metrics.item2.label': 'Coordinación Manual',

'caseStudies.adminAutomation.metrics.item3.value': '35%↑',
'caseStudies.adminAutomation.metrics.item3.label': 'Velocidad Operativa',

'caseStudies.adminAutomation.metrics.item4.value': '0',
'caseStudies.adminAutomation.metrics.item4.label': 'Nuevas Contrataciones Administrativas',

// --- Context ---
'caseStudies.adminAutomation.context.label': 'El Contexto',
'caseStudies.adminAutomation.context.title': 'El trabajo administrativo estaba frenando el crecimiento.',
'caseStudies.adminAutomation.context.p1': 'El negocio no estaba disminuyendo.',
'caseStudies.adminAutomation.context.p2': 'En realidad, la demanda se mantenía estable.',
'caseStudies.adminAutomation.context.p3': 'Los leads seguían llegando, los clientes estaban siendo atendidos y los ingresos continuaban. Pero detrás de escena, el equipo estaba saturado con tareas administrativas que se habían convertido silenciosamente en una barrera para el progreso.',
'caseStudies.adminAutomation.context.p4': 'Las tareas manuales eran una parte importante de las operaciones diarias:',

'caseStudies.adminAutomation.context.list1': 'Agregar y actualizar leads',
'caseStudies.adminAutomation.context.list2': 'Seguimientos y recordatorios',
'caseStudies.adminAutomation.context.list3': 'Coordinar citas',
'caseStudies.adminAutomation.context.list4': 'Seguimiento de estados en hojas de cálculo',
'caseStudies.adminAutomation.context.list5': 'Transferencias internas por correo electrónico y WhatsApp',

'caseStudies.adminAutomation.context.p5': 'Ninguno de estos esfuerzos generaba ingresos directamente, pero sí consumía mucho tiempo, atención y energía.',
'caseStudies.adminAutomation.context.p6': 'Este estudio de caso muestra cómo Go High Level utilizó la automatización para reemplazar tareas administrativas repetitivas, haciendo el negocio más ágil, rápido y escalable sin contratar más personas.',

// --- Challenge ---
'caseStudies.adminAutomation.challenge.label': 'El Desafío',
'caseStudies.adminAutomation.challenge.title': 'Personas Haciendo Tareas que No Deberían Ser Humanas',
'caseStudies.adminAutomation.challenge.p1': 'Las personas estaban realizando tareas que los sistemas deberían haber gestionado. Algunos de los principales problemas eran:',

'caseStudies.adminAutomation.challenge.list1': 'Miembros del equipo pasando horas ingresando datos',
'caseStudies.adminAutomation.challenge.list2': 'Seguimientos perdidos debido al control manual',
'caseStudies.adminAutomation.challenge.list3': 'Diferentes personas usando procesos distintos',
'caseStudies.adminAutomation.challenge.list4': 'Transferencias y aprobaciones que tardaban demasiado',
'caseStudies.adminAutomation.challenge.list5': 'Sin visibilidad en tiempo real de lo que estaba ocurriendo',

'caseStudies.adminAutomation.challenge.p2': 'A medida que el volumen aumentaba, la carga administrativa crecía de forma proporcional. Más clientes significaban más comunicaciones, más coordinación y más posibilidades de errores. El negocio crecía, pero no se volvía más eficiente.',

// --- Approach ---
'caseStudies.adminAutomation.approach.label': 'Nuestro Enfoque',
'caseStudies.adminAutomation.approach.title': 'Por Qué Contratar Más Personal Administrativo No Era la Solución',
'caseStudies.adminAutomation.approach.p1': 'Contratar más personal administrativo habría aumentado los costos, la complejidad y la dependencia sin resolver el problema real. El problema no era la capacidad, sino el diseño del proceso. La automatización eliminó la coordinación manual desde la raíz.',

// Phase 1
'caseStudies.adminAutomation.approach.phase1.title': 'Mapeo de Tareas Administrativas',
'caseStudies.adminAutomation.approach.phase1.duration': 'Semanas 1–2',
'caseStudies.adminAutomation.approach.phase1.desc': 'Antes de comenzar, Go High Level realizó una auditoría operativa completa para entender dónde se invertían el tiempo y el esfuerzo.',
'caseStudies.adminAutomation.approach.phase1.p1': 'Se realizó un mapa de:',
'caseStudies.adminAutomation.approach.phase1.list1': 'Tareas diarias, semanales y mensuales del área administrativa',
'caseStudies.adminAutomation.approach.phase1.list2': 'Duración de cada tarea',
'caseStudies.adminAutomation.approach.phase1.list3': 'Dependencias entre tareas',
'caseStudies.adminAutomation.approach.phase1.list4': 'Puntos donde ocurrían errores o retrasos',
'caseStudies.adminAutomation.approach.phase1.p2': 'Más del 60% del tiempo administrativo se dedicaba a tareas repetitivas con reglas claras, ideales para automatización.',

// Phase 2
'caseStudies.adminAutomation.approach.phase2.title': 'Un Único Sistema de Registro',
'caseStudies.adminAutomation.approach.phase2.duration': 'Semanas 3–4',
'caseStudies.adminAutomation.approach.phase2.desc': 'El uso excesivo de herramientas generaba duplicación, confusión y conciliación manual.',
'caseStudies.adminAutomation.approach.phase2.p1': 'Todos los datos operativos fueron centralizados en un único sistema, eliminando la necesidad de verificaciones cruzadas y seguimientos manuales.',

// Phase 3
'caseStudies.adminAutomation.approach.phase3.title': 'Automatización de Flujos Administrativos Clave',
'caseStudies.adminAutomation.approach.phase3.duration': 'Semanas 5–7',
'caseStudies.adminAutomation.approach.phase3.desc': 'Las tareas administrativas críticas fueron automatizadas para que el sistema pudiera crear, asignar y rastrear trabajo sin intervención manual.',

// Phase 4
'caseStudies.adminAutomation.approach.phase4.title': 'Intervención Humana Basada en Excepciones',
'caseStudies.adminAutomation.approach.phase4.duration': 'Semanas 8–10',
'caseStudies.adminAutomation.approach.phase4.desc': 'La automatización gestionaba el flujo normal, y las personas solo intervenían cuando surgía una excepción como retrasos, leads estancados o situaciones que requerían juicio humano.',

// Phase 5
'caseStudies.adminAutomation.approach.phase5.title': 'Reportes, Responsabilidad y Visibilidad',
'caseStudies.adminAutomation.approach.phase5.duration': 'Semanas 11–12',
'caseStudies.adminAutomation.approach.phase5.desc': 'Los paneles en tiempo real reemplazaron el seguimiento manual, ofreciendo visibilidad completa del progreso, cuellos de botella y salud operativa.',

// --- Results ---
'caseStudies.adminAutomation.results.label': 'Los Resultados',
'caseStudies.adminAutomation.results.title': 'De Administración Manual a Operaciones Automatizadas',

'caseStudies.adminAutomation.results.card1.before': 'Alta',
'caseStudies.adminAutomation.results.card1.after': '60%+↓',
'caseStudies.adminAutomation.results.card1.label': 'Carga administrativa significativamente reducida',

'caseStudies.adminAutomation.results.card2.before': 'Lento',
'caseStudies.adminAutomation.results.card2.after': '35%↑',
'caseStudies.adminAutomation.results.card2.label': 'Finalización de tareas más rápida',

'caseStudies.adminAutomation.results.card3.before': 'Frecuente',
'caseStudies.adminAutomation.results.card3.after': '45%↓',
'caseStudies.adminAutomation.results.card3.label': 'Errores y seguimientos perdidos reducidos',

'caseStudies.adminAutomation.results.card4.before': 'Manual',
'caseStudies.adminAutomation.results.card4.after': 'Automatizado',
'caseStudies.adminAutomation.results.card4.label': 'Gestión de leads y coordinación interna',

// --- Testimonial ---
'caseStudies.adminAutomation.testimonial.quote': 'Nuestros usuarios ahora exploran, interactúan y completan acciones en lugar de abandonar después de unos segundos. El rediseño cambió completamente la forma en que las personas interactúan con nuestra plataforma.',
'caseStudies.adminAutomation.testimonial.author': 'Director de Producto',
'caseStudies.adminAutomation.testimonial.title': 'Empresa de Plataforma Digital',

// --- CTA ---
'caseStudies.adminAutomation.cta.title': '¿Quieres aumentar la interacción sin más tráfico?',
'caseStudies.adminAutomation.cta.subtitle': 'Ayudamos a plataformas digitales a convertir visitantes pasivos en usuarios activos mediante diseño UX basado en investigación.',
'caseStudies.adminAutomation.cta.primary': 'Programar una Consulta',
'caseStudies.adminAutomation.cta.secondary': 'Ver Más Casos de Estudio',


// ========================================
// INSIGHTS PAGE
// Designing CI/CD Pipelines
// ========================================

// --- Hero ---
'insights.cicd.hero.category': 'Servicios y Consultoría en TI',
'insights.cicd.hero.date': '04 de febrero de 2026',
'insights.cicd.hero.title': 'Diseñando Pipelines CI/CD para Equipos de Ingeniería de Alta Velocidad',
'insights.cicd.hero.excerpt': 'Los equipos de ingeniería de alta velocidad necesitan más que rapidez. Los pipelines CI/CD bien diseñados permiten una entrega rápida de software mientras preservan la calidad, la seguridad y la confiabilidad operativa a escala.',
'insights.cicd.hero.bgAlt': 'Fondo de protección de seguros',

// --- Body Intro ---
'insights.cicd.body.p1': "En el mundo digital actual, donde la competencia es intensa, la rapidez no es una opción; es una necesidad. Los equipos de ingeniería de alto rendimiento deben poder añadir nuevas funcionalidades rápidamente, corregir errores y mantener una alta calidad incluso a gran escala. Aquí es donde la implementación de pipelines CI/CD se vuelve fundamental para la entrega rápida de software y la velocidad de ingeniería a largo plazo.",

'insights.cicd.body.p2': 'Un pipeline CI/CD moderno permite a los equipos desplegar cambios de forma rápida y segura sin comprometer la seguridad, la estabilidad ni la confianza del desarrollador. A medida que las organizaciones adoptan modelos Agile y DevOps, los despliegues manuales, los entornos inconsistentes y los ciclos de retroalimentación lentos se convierten en riesgos operativos. Los pipelines CI/CD diseñados específicamente abordan estos desafíos mediante la estandarización, la automatización de controles de calidad y la garantía de coherencia entre entornos.',

// --- Section 1 ---
'insights.cicd.section1.title': '1. Por qué CI/CD es importante para equipos de ingeniería de alta velocidad',
'insights.cicd.section1.p1': 'Los equipos que trabajan rápidamente operan en entornos donde el código cambia constantemente. Sin un sistema CI/CD sólido, estos cambios pueden provocar fallos en compilaciones y despliegues, ralentizando el desarrollo.',
'insights.cicd.section1.p2': 'Los pipelines CI/CD automatizan la compilación, las pruebas y el despliegue del código. Esto permite que los equipos se concentren en desarrollar nuevas funcionalidades en lugar de preocuparse por las liberaciones. Cuando están bien configurados, funcionan como una red de seguridad: detectan problemas temprano y aseguran entregas rápidas y confiables.',

// --- Section 2 ---
'insights.cicd.section2.title': '2. Principios fundamentales de los pipelines de entrega rápida',
'insights.cicd.section2.p1': 'Para que los pipelines de entrega rápida funcionen eficazmente, el diseño CI/CD debe priorizar la velocidad y la confiabilidad. Los mejores pipelines tienen éxito porque siguen principios fundamentales.',
'insights.cicd.section2.p2': 'Primero, todo debe estar automatizado. Los procesos manuales ralentizan cada etapa. Desde la modificación del código hasta el despliegue en producción, la automatización garantiza consistencia y eficiencia.',
'insights.cicd.section2.p3': 'Las pruebas deben comenzar temprano y continuar constantemente. Las pruebas unitarias, de integración y de seguridad deben ejecutarse lo antes posible para evitar retrasos posteriores en el ciclo de lanzamiento.',
'insights.cicd.section2.p4': 'La ejecución paralela — ejecutar pruebas y compilaciones simultáneamente — acelera significativamente los ciclos de liberación.',

// --- Section 3 ---
'insights.cicd.section3.title': '3. Diseñar pipelines DevOps escalables es esencial',
'insights.cicd.section3.p1': 'Un pipeline Agile DevOps debe evolucionar junto con el equipo. A medida que las organizaciones crecen, sus pipelines deben gestionar más servicios, colaboradores y entornos sin fallos.',
'insights.cicd.section3.p2': 'Los sistemas CI/CD escalables utilizan pipelines modulares, plantillas reutilizables y enfoques de pipeline-as-code para garantizar uniformidad entre proyectos.',
'insights.cicd.section3.p3': 'Las soluciones CI/CD nativas de la nube y los entornos contenerizados ofrecen flexibilidad y capacidad de adaptación.',
'insights.cicd.section3.p4': 'La visibilidad es igual de importante. Supervisar el rendimiento de los pipelines, su tasa de fallos y su uso permite mejorar continuamente el proceso de entrega.',

// --- Section 4 ---
'insights.cicd.section4.title': '4. Mantener la calidad en ciclos de lanzamiento rápidos',
'insights.cicd.section4.p1': 'Los despliegues rápidos no significan despliegues descuidados. Los equipos de alto rendimiento utilizan mecanismos de control para equilibrar velocidad y calidad.',
'insights.cicd.section4.p2': 'Los controles de calidad automatizados, los procesos de aprobación para tareas críticas y los mecanismos de rollback garantizan la confiabilidad.',
'insights.cicd.section4.p3': 'La seguridad también debe integrarse en el pipeline mediante la identificación automática de vulnerabilidades y la verificación de dependencias bajo principios DevSecOps.',

// --- Key Takeaways ---
'insights.cicd.takeaways.title': 'Puntos Clave',
'insights.cicd.takeaways.item1': 'Los pipelines CI/CD son fundamentales para mantener la velocidad de ingeniería',
'insights.cicd.takeaways.item2': 'La automatización, las pruebas y la ejecución paralela permiten ciclos de retroalimentación rápidos',
'insights.cicd.takeaways.item3': 'Un diseño escalable de pipelines apoya el crecimiento sin fricción operativa',
'insights.cicd.takeaways.item4': 'Los mecanismos integrados de calidad y seguridad protegen la confiabilidad a alta velocidad',

// --- Conclusion ---
'insights.cicd.conclusion.title': 'Conclusión',
'insights.cicd.conclusion.p1': 'Diseñar pipelines CI/CD para equipos de ingeniería de alta velocidad no se trata solo de automatización, sino de generar la confianza necesaria para avanzar rápidamente.',
'insights.cicd.conclusion.p2': 'Las organizaciones que buscan acelerar la ingeniería a largo plazo deben centrarse en pipelines de entrega rápida, pipelines DevOps ágiles escalables y ciclos de lanzamiento rápidos con estándares estrictos de calidad.',
'insights.cicd.conclusion.p3': 'Un pipeline CI/CD bien planificado es un activo estratégico que permite innovar más rápido, adaptarse al cambio y ofrecer valor constante a los usuarios.',

// --- Sidebar ---
'insights.cicd.sidebar.title': 'En Este Artículo',
'insights.cicd.sidebar.item1': '1. Por qué CI/CD es importante',
'insights.cicd.sidebar.item2': '2. Principios Fundamentales',
'insights.cicd.sidebar.item3': '3. Pipelines DevOps Escalables',
'insights.cicd.sidebar.item4': '4. Controles de Calidad y Seguridad',
'insights.cicd.sidebar.item5': '5. Conclusión',

// --- Share Section ---
'insights.cicd.share.title': 'Compartir Este Artículo',
'insights.cicd.share.copied': '¡Enlace copiado!',

// ========================================
// CASE STUDY PAGE
// Build & Deployment Automation
// ========================================

// --- Hero ---
'caseStudies.buildDeploy.hero.tag1': 'Automatización de procesos',
'caseStudies.buildDeploy.hero.tag2': 'Gobernanza y Seguridad',
'caseStudies.buildDeploy.hero.industry': 'Plataforma de seguros de salud',
'caseStudies.buildDeploy.hero.title': 'Automatización de Build y Despliegue para una Suite de Seguros de Salud Basada en la Nube',
'caseStudies.buildDeploy.hero.subtitle': 'Un análisis real de la implementación que muestra cómo una automatización consciente de los requisitos de cumplimiento mejoró la velocidad de puesta en producción, la estabilidad operativa y la confianza, sin comprometer el控制 regulatorio.',
'caseStudies.buildDeploy.hero.bgAlt': 'Fondo de protección de seguros',

// --- Metrics ---
'caseStudies.buildDeploy.metrics.item1.value': '55%↑',
'caseStudies.buildDeploy.metrics.item1.label': 'Ciclos de lanzamiento más rápidos',
'caseStudies.buildDeploy.metrics.item2.value': '50%↓',
'caseStudies.buildDeploy.metrics.item2.label': 'Errores de despliegue',
'caseStudies.buildDeploy.metrics.item3.value': '40%↑',
'caseStudies.buildDeploy.metrics.item3.label': 'Estabilidad operativa',
'caseStudies.buildDeploy.metrics.item4.value': '100%',
'caseStudies.buildDeploy.metrics.item4.label': 'Automatización conforme a requisitos regulatorios',

// --- Context ---
'caseStudies.buildDeploy.context.label': 'El Contexto',
'caseStudies.buildDeploy.context.title': 'Las entregas manuales ralentizaban una plataforma crítica',
'caseStudies.buildDeploy.context.p1': 'Los builds manuales dificultaban la innovación. La suite de seguros de salud era estable y fiable, pero sufría una fuerte presión debido a su crecimiento. La plataforma no podía seguir el ritmo de las nuevas necesidades de las aseguradoras, los cambios regulatorios y las actualizaciones funcionales que llegaban más rápido de lo que se podían publicar.',
'caseStudies.buildDeploy.context.p2': 'La demanda seguía siendo alta. Los clientes necesitaban que el sistema procesara reclamaciones, rastreara pólizas y generara informes. Pero los procesos de build y despliegue eran muy manuales, lentos y llenos de riesgos en segundo plano.',
'caseStudies.buildDeploy.context.p3': 'Varios equipos tenían que planificar los lanzamientos. Las ventanas de despliegue eran cortas debido al riesgo en producción. Se necesitaban días en lugar de horas para realizar pequeños cambios de configuración. El sistema funcionaba, pero la velocidad de entrega estaba desalineada.',
'caseStudies.buildDeploy.context.p4': 'Este caso de estudio muestra cómo automatizamos el build y el despliegue de una suite de seguros de salud basada en la nube. Esto permitió publicar nuevas versiones más rápido manteniendo la seguridad, la estabilidad y el cumplimiento.',

// --- Challenge ---
'caseStudies.buildDeploy.challenge.label': 'El Desafío',
'caseStudies.buildDeploy.challenge.title': 'Los procesos manuales creaban un riesgo de entrega, no de fiabilidad',
'caseStudies.buildDeploy.challenge.p1': 'El principal problema no era la infraestructura ni las capacidades de ingeniería; era la forma en que se realizaban los builds y los despliegues.',
'caseStudies.buildDeploy.challenge.p2': 'Estos son algunos de los mayores problemas:',
'caseStudies.buildDeploy.challenge.item1': 'Construcción y despliegue manual en diferentes entornos',
'caseStudies.buildDeploy.challenge.item2': 'Fuerte dependencia de los ingenieros de release',
'caseStudies.buildDeploy.challenge.item3': 'Configuraciones inconsistentes entre staging y producción',
'caseStudies.buildDeploy.challenge.item4': 'Capacidad limitada de rollback',
'caseStudies.buildDeploy.challenge.item5': 'Miedo a los despliegues debido a los riesgos de inactividad y cumplimiento',
'caseStudies.buildDeploy.challenge.item6': 'Ausencia de un pipeline de release estandarizado para todos los servicios.',
'caseStudies.buildDeploy.challenge.p3': 'A medida que la plataforma crecía, cada nueva versión se volvía más difícil. Más funcionalidades significaban más planificación, más verificaciones y más riesgos. Aunque la demanda aumentaba, la velocidad disminuía.',

// --- Approach ---
'caseStudies.buildDeploy.approach.label': 'Nuestro Enfoque',
'caseStudies.buildDeploy.approach.title': 'Una automatización diseñada para el control, no para el caos',

// Phase 1
'caseStudies.buildDeploy.approach.phase1.number': '1',
'caseStudies.buildDeploy.approach.phase1.title': 'Análisis de los flujos de trabajo de build y despliegue',
'caseStudies.buildDeploy.approach.phase1.duration': 'Semanas 1–2',
'caseStudies.buildDeploy.approach.phase1.p1': 'Mapeamos todo el proceso de release, desde el commit del código hasta el despliegue en producción. Se documentó cada paso manual, cada barrera de aprobación y cada dependencia.',
'caseStudies.buildDeploy.approach.phase1.p2': 'La auditoría reveló que más del 65% del trabajo de despliegue era repetitivo y basado en reglas. Esto lo hacía ideal para la automatización sin comprometer el cumplimiento.',

// Phase 2
'caseStudies.buildDeploy.approach.phase2.number': '2',
'caseStudies.buildDeploy.approach.phase2.title': 'Implementación de los mismos pipelines de build para todos los servicios',
'caseStudies.buildDeploy.approach.phase2.duration': 'Semanas 3–4',
'caseStudies.buildDeploy.approach.phase2.p1': 'Creamos pipelines de build estandarizados y reutilizables para toda la suite de seguros de salud.',
'caseStudies.buildDeploy.approach.phase2.p2': 'Entre los cambios más importantes:',
'caseStudies.buildDeploy.approach.phase2.item1': 'Parámetros de build consistentes',
'caseStudies.buildDeploy.approach.phase2.item2': 'Paridad de entornos entre desarrollo, staging y producción',
'caseStudies.buildDeploy.approach.phase2.item3': 'Versionado automático de artefactos',
'caseStudies.buildDeploy.approach.phase2.item4': 'Gestión segura de secretos',
'caseStudies.buildDeploy.approach.phase2.p3': 'Esto eliminó las inconsistencias que anteriormente provocaban fallos en el despliegue.',

// Phase 3
'caseStudies.buildDeploy.approach.phase3.number': '3',
'caseStudies.buildDeploy.approach.phase3.title': 'Despliegue automatizado con salvaguardas de cumplimiento',
'caseStudies.buildDeploy.approach.phase3.duration': 'Semanas 5–7',
'caseStudies.buildDeploy.approach.phase3.p1': 'Tuvimos en cuenta las normativas de salud al automatizar el despliegue. Los pipelines automatizados garantizaban:',
'caseStudies.buildDeploy.approach.phase3.item1': 'Verificaciones de validación antes del despliegue',
'caseStudies.buildDeploy.approach.phase3.item2': 'Aprobaciones específicas para cada entorno',
'caseStudies.buildDeploy.approach.phase3.item3': 'Registro de auditoría para cada release',
'caseStudies.buildDeploy.approach.phase3.item4': 'Estrategias de lanzamiento controladas',
'caseStudies.buildDeploy.approach.phase3.p2': 'Cada despliegue seguía la misma ruta segura, lo que hacía los procesos más rápidos y menos riesgosos.',

// Phase 4
'caseStudies.buildDeploy.approach.phase4.number': '4',
'caseStudies.buildDeploy.approach.phase4.title': 'Supervisión, rollbacks y visibilidad de los lanzamientos',
'caseStudies.buildDeploy.approach.phase4.duration': 'Semanas 8–10',
'caseStudies.buildDeploy.approach.phase4.p1': 'En lugar de seguir el estado manualmente, los paneles de despliegue en tiempo real hacían el trabajo. Los equipos podían ver inmediatamente:',
'caseStudies.buildDeploy.approach.phase4.item1': 'El progreso del despliegue',
'caseStudies.buildDeploy.approach.phase4.item2': 'Puntos potenciales de falla',
'caseStudies.buildDeploy.approach.phase4.item3': 'Preparación para rollback',
'caseStudies.buildDeploy.approach.phase4.item4': 'Estado de salud del entorno',
'caseStudies.buildDeploy.approach.phase4.p2': 'Los procedimientos de rollback automatizados garantizaban que los problemas pudieran resolverse de forma segura sin provocar largos periodos de interrupción.',

// --- Results ---
'caseStudies.buildDeploy.results.label': 'Los Resultados',
'caseStudies.buildDeploy.results.title': 'De lanzamientos manuales a una entrega predecible y conforme',
'caseStudies.buildDeploy.results.card1.before': 'Lento',
'caseStudies.buildDeploy.results.card1.after': '55% más rápido',
'caseStudies.buildDeploy.results.card1.label': 'Ciclos de release',
'caseStudies.buildDeploy.results.card2.before': 'Propenso a errores',
'caseStudies.buildDeploy.results.card2.after': '50%↓',
'caseStudies.buildDeploy.results.card2.label': 'Fallos de despliegue',
'caseStudies.buildDeploy.results.card3.before': 'Frágil',
'caseStudies.buildDeploy.results.card3.after': 'Estable',
'caseStudies.buildDeploy.results.card3.label': 'Fiabilidad operativa',
'caseStudies.buildDeploy.results.card4.before': 'Manual',
'caseStudies.buildDeploy.results.card4.after': 'Gobernado',
'caseStudies.buildDeploy.results.card4.label': 'Releases listas para cumplimiento',

// --- Testimonial ---
'caseStudies.buildDeploy.testimonial.quote': "Nuestros usuarios ahora exploran, interactúan y completan acciones en lugar de abandonar a los pocos segundos. El rediseño ha cambiado por completo la forma en que las personas interactúan con nuestra plataforma.",
'caseStudies.buildDeploy.testimonial.authorName': 'Gerente de Producto',
'caseStudies.buildDeploy.testimonial.authorTitle': 'Empresa de plataforma digital',

// --- CTA ---
'caseStudies.buildDeploy.cta.title': '¿Desea aumentar la interacción sin más tráfico?',
'caseStudies.buildDeploy.cta.subtitle': 'Ayudamos a las plataformas digitales a transformar visitantes pasivos en usuarios activos mediante un diseño UX basado en la investigación.',
'caseStudies.buildDeploy.cta.primary': 'Programar una consulta',
'caseStudies.buildDeploy.cta.secondary': 'Ver más casos de estudio',

// ========================================
// INSIGHT PAGE
// How to Evaluate & Choose the Right Web
// ========================================

// --- Hero ---
'insights.webPartner.hero.category': 'Servicios de TI y Asesoría',
'insights.webPartner.hero.date': 'February 05, 2026',
'insights.webPartner.hero.title': 'How to Evaluate & Choose the Right Web Development Partner for Long-Term Success',
'insights.webPartner.hero.excerpt': 'Choosing the right web development partner is a strategic decision. This guide explains how to evaluate partners beyond short-term delivery and select one that supports long-term growth, scalability, and business outcomes.',
'insights.webPartner.hero.bgAlt': 'Insurance protection background',

// --- Body Intro ---
'insights.webPartner.body.p1': 'In today\'s digital world, a website or app serves more than just an online presence. It helps your business expand, spreads the word about your brand, and is a long-term asset. No matter if you\'re a startup growing quickly, a company that has been around for a while and is going through a digital transformation, or a major company that wants to make things better for customers, it\'s very crucial to choose the correct web development partner.',
'insights.webPartner.body.p2': 'There are many agencies, development companies, and freelancers to choose from, which can make it hard to choose the ideal partner. This lesson teaches you how to pick web development partners carefully, putting long-term value ahead of quick delivery.',

// --- Section 1 ---
'insights.webPartner.section1.title': '1. Why it\'s important to pick the right web development partner',
'insights.webPartner.section1.p1': 'Engineers A web development connection isn\'t just a one-time thing; it could last for years. The right partner will help you make digital tools that help you reach your business goals, finish projects on time and on budget, and grow your platforms as your firm grows. They help get your digital infrastructure ready for things like AI improvements, faster speeds, or new integrations in the future.',
'insights.webPartner.section1.p2': 'More than 85% of digital projects fail because the technology doesn\'t work with the partner or the partner isn\'t right, according to a study. A powerful growth partner is like a teammate. They provide you advice, help you deal with problems, and support your plan as you go.',

// --- Section 2 ---
'insights.webPartner.section2.title': '2. Set the needs and goals for your project',
'insights.webPartner.section2.p1': 'Before you talk to potential partners, you need to be clear. First, you need to know what issue you\'re trying to solve, who you\'re trying to reach, how much money you have to spend, how long you have to do it, and what success metrics are most important to you, like SEO performance, conversions, or speed. Determine whether you require a website, a web application, an e-commerce platform, or system integrations.',
'insights.webPartner.section2.p2': 'Include this in a Project Requirements Document (PRD). It\'s easier to check if offers are valid, negotiations go more smoothly, and suppliers can be compared fairly when there is a clear PRD.',
'insights.webPartner.section2.imageAlt': 'How to Evaluate & Choose the Right Web Development Partner for Long-Term Success',

// --- Section 3 ---
'insights.webPartner.section3.title': '3. What to Look for in a Partner for Web Development',

'insights.webPartner.section3.sub1.title': 'Technical Expertise and Technology Alignment',
'insights.webPartner.section3.sub1.p1': 'Check to see if the partner has worked with the tools, frameworks, CMS platforms, cloud infrastructure, and other technologies that your project needs to run. When technical alignment is strong, the risk goes down, and it is easier to keep things running over time.',

'insights.webPartner.section3.sub2.title': 'Industry Knowledge and Experience',
'insights.webPartner.section3.sub2.p1': 'Partners that have worked in the same field before know the rules, what consumers want, and what problems come up every day. You can make better decisions and get things done faster with this information.',

'insights.webPartner.section3.sub3.title': 'Portfolio and Case Studies',
'insights.webPartner.section3.sub3.p1': 'Look at previous work to see how useful it is, how effectively the UI/UX works, how quickly it responds, and how well it meets business goals. You can think strategically and solve problems, as evidenced by case studies.',

'insights.webPartner.section3.sub4.title': 'Communication and Collaboration Model',
'insights.webPartner.section3.sub4.p1': 'Effective communication prevents misunderstandings and excessive delays. Determine the frequency of updates, the tools utilized, and the presence of a project manager for oversight.',

'insights.webPartner.section3.sub5.title': 'Security, Scalability, and Delivery Process',
'insights.webPartner.section3.sub5.p1': 'You can trust partners who implement organized methods such as Agile, prioritize security and compliance, and plan for growth by monitoring performance and performing regular maintenance.',

'insights.webPartner.section3.sub6.title': 'Transparent Pricing and Long-Term Value',
'insights.webPartner.section3.sub6.p1': 'Instead of looking for the cheapest choice, look for the best value. Look for detailed cost breakdowns, realistic schedules, and choices for long-term help.',

// --- Key Takeaways ---
'insights.webPartner.keyTakeaways.title': 'Key Takeaways',
'insights.webPartner.keyTakeaways.item1': 'Web development partnerships are long-term strategic relationships',
'insights.webPartner.keyTakeaways.item2': 'Clear requirements enable better partner evaluation and alignment',
'insights.webPartner.keyTakeaways.item3': 'Industry experience and technical fit reduce delivery risk',
'insights.webPartner.keyTakeaways.item4': 'Transparency, security, and scalability matter more than short-term cost',

// --- Section 4 ---
'insights.webPartner.section4.title': '4. Final Partner Evaluation Checklist',
'insights.webPartner.section4.p1': 'Before making a final decision, confirm that you have:',
'insights.webPartner.section4.item1': 'Documented clear project goals and requirements',
'insights.webPartner.section4.item2': 'Reviewed portfolios and validated references',
'insights.webPartner.section4.item3': 'Evaluated communication and delivery processes',
'insights.webPartner.section4.item4': 'Confirmed security, compliance, and scalability plans',
'insights.webPartner.section4.item5': 'Reviewed pricing and long-term support models',

// --- Conclusion ---
'insights.webPartner.conclusion.title': 'Conclusion',
'insights.webPartner.conclusion.p1': 'Choosing the right web development partner is a critical business decision that directly impacts your organization’s digital success. By prioritizing alignment, governance, and long-term value, you can build a partnership that supports sustainable growth and continuous improvement.',
'insights.webPartner.conclusion.p2': 'The right partner does more than deliver software - they help you build a resilient digital foundation that evolves with your business.',

// --- Sidebar ---
'insights.webPartner.sidebar.toc.title': 'In This Article',
'insights.webPartner.sidebar.toc.item1': '1. Why Partner Choice Matters',
'insights.webPartner.sidebar.toc.item2': '2. Define Project Needs',
'insights.webPartner.sidebar.toc.item3': '3. What to Look for in a Partner',
'insights.webPartner.sidebar.toc.item4': '4. Final Evaluation Checklist',
'insights.webPartner.sidebar.toc.item5': '5. Conclusion',

'insights.webPartner.sidebar.share.title': 'Share This Article',
'insights.webPartner.sidebar.share.copied': 'Link copied!',


// ========================================
// CASE STUDY PAGE
// How We Deliver High-Performance Web Platforms
// ========================================

// --- Hero ---
'caseStudies.highPerformance.hero.tag1': 'Rendimiento Web',
'caseStudies.highPerformance.hero.tag2': 'Arquitectura de Plataforma',
'caseStudies.highPerformance.hero.industry': 'Plataforma Digital',
'caseStudies.highPerformance.hero.title': 'Cómo Entregamos Plataformas Web de Alto Rendimiento',
'caseStudies.highPerformance.hero.subtitle': 'Un análisis real de entrega que muestra cómo una arquitectura orientada al rendimiento mejoró la velocidad, el compromiso y la escalabilidad sin reconstruir la infraestructura.',
'caseStudies.highPerformance.hero.bgAlt': 'Fondo de protección de seguros',

// --- Metrics ---
'caseStudies.highPerformance.metrics.item1.value': '50%↓',
'caseStudies.highPerformance.metrics.item1.label': 'Tiempo de Carga de Página',
'caseStudies.highPerformance.metrics.item2.value': '40%↓',
'caseStudies.highPerformance.metrics.item2.label': 'Tasa de Rebote',
'caseStudies.highPerformance.metrics.item3.value': '30%↑',
'caseStudies.highPerformance.metrics.item3.label': 'Compromiso del Usuario',
'caseStudies.highPerformance.metrics.item4.value': '0',
'caseStudies.highPerformance.metrics.item4.label': 'Reconstrucciones de Infraestructura',

// --- Context ---
'caseStudies.highPerformance.context.label': 'El Contexto',
'caseStudies.highPerformance.context.title': 'La plataforma estaba siendo limitada por el rendimiento',
'caseStudies.highPerformance.context.p1': 'La plataforma no estaba rota, pero podría haber sido mejor. Había mucho tráfico, se añadían nuevas funciones todo el tiempo y las personas seguían muy interesadas. Pero detrás de escena, los problemas de rendimiento estaban empeorando lentamente la experiencia del usuario y la escalabilidad.',
'caseStudies.highPerformance.context.p2': 'Cuando había muchas personas en el sitio, las páginas tardaban mucho en cargarse. Hubo momentos en que las nuevas funciones empeoraron las cosas. Los desarrolladores pasaban más tiempo solucionando problemas que mejorando el producto. Estos problemas no eran demasiado graves, pero sí ralentizaban las cosas.',
'caseStudies.highPerformance.context.p3': 'Este caso de estudio muestra cómo creamos una plataforma en línea de alto rendimiento cambiando la forma en que fue planificada, mejorando la manera en que fue entregada y haciendo que el rendimiento fuera parte de cada etapa del proceso.',

// --- Challenge ---
'caseStudies.highPerformance.challenge.label': 'El Desafío',
'caseStudies.highPerformance.challenge.title': 'El problema no era la tecnología - era la metodología de entrega',
'caseStudies.highPerformance.challenge.p1': 'El problema principal no era la falta de habilidades o herramientas; era cómo se gestionaba el rendimiento.',
'caseStudies.highPerformance.challenge.p2': 'Algunos de los mayores problemas fueron:',
'caseStudies.highPerformance.challenge.item1': 'Mejorar el rendimiento demasiado tarde en el ciclo de vida.',
'caseStudies.highPerformance.challenge.item2': 'Equipos que solo trabajan en el front end y el back end',
'caseStudies.highPerformance.challenge.item3': 'No hay reglas fijas sobre qué tan bien deben funcionar las cosas.',
'caseStudies.highPerformance.challenge.item4': 'Pruebas manuales y solución de problemas a medida que surgen',
'caseStudies.highPerformance.challenge.item5': 'No podíamos ver qué tan bien se desempeñaban los usuarios reales.',
'caseStudies.highPerformance.challenge.p3': 'Con cada nueva versión, el riesgo crecía a medida que más personas usaban el producto. La plataforma se estaba haciendo más grande, pero no estaba mejorando en lo que hacía.',

// --- Approach ---
'caseStudies.highPerformance.approach.label': 'Nuestro Enfoque',
'caseStudies.highPerformance.approach.title': 'Diseñar para el rendimiento desde el primer día',

// Phase 1
'caseStudies.highPerformance.approach.phase1.number': '1',
'caseStudies.highPerformance.approach.phase1.title': 'Establecer Líneas Base de Rendimiento',
'caseStudies.highPerformance.approach.phase1.duration': 'Semanas 1–2',
'caseStudies.highPerformance.approach.phase1.p1': 'Comenzamos revisando los niveles de frontend, backend e infraestructura de la plataforma. Seleccionamos métricas clave como tiempo de carga, respuesta de API y Core Web Vitals como puntos de referencia para tener un punto de partida claro.',
'caseStudies.highPerformance.approach.phase1.p2': 'Esto mostró rápidamente dónde los problemas de rendimiento tenían el mayor impacto en el negocio.',

// Phase 2
'caseStudies.highPerformance.approach.phase2.number': '2',
'caseStudies.highPerformance.approach.phase2.title': 'Arquitectura Web que Prioriza el Rendimiento',
'caseStudies.highPerformance.approach.phase2.duration': 'Semanas 3–4',
'caseStudies.highPerformance.approach.phase2.p1': 'No hicimos solo pequeños ajustes; reescribimos elementos importantes del sistema utilizando principios orientados al rendimiento:',
'caseStudies.highPerformance.approach.phase2.item1': 'Elementos del front end que pueden modificarse',
'caseStudies.highPerformance.approach.phase2.item2': 'Mejores respuestas de la API',
'caseStudies.highPerformance.approach.phase2.item3': 'Estrategias de caché efectivas',
'caseStudies.highPerformance.approach.phase2.item4': 'Infraestructura en la nube escalable',
'caseStudies.highPerformance.approach.phase2.p2': 'Esto aseguró que la plataforma web pudiera evolucionar sin mantenimiento constante.',

// Phase 3
'caseStudies.highPerformance.approach.phase3.number': '3',
'caseStudies.highPerformance.approach.phase3.title': 'Pipelines de Entrega con Verificaciones Automatizadas de Rendimiento',
'caseStudies.highPerformance.approach.phase3.duration': 'Semanas 5–7',
'caseStudies.highPerformance.approach.phase3.p1': 'Agregamos pruebas de rendimiento directamente en el proceso de producción y distribución. Antes de salir en vivo, cada versión era verificada automáticamente para asegurarse de que cumpliera con los estándares de rendimiento.',
'caseStudies.highPerformance.approach.phase3.p2': 'Este procedimiento eliminó regresiones y hizo que las pruebas manuales ya no fueran necesarias.',

// Phase 4
'caseStudies.highPerformance.approach.phase4.number': '4',
'caseStudies.highPerformance.approach.phase4.title': 'Monitoreo y Mejora en Tiempo Real',
'caseStudies.highPerformance.approach.phase4.duration': 'Semanas 8–10',
'caseStudies.highPerformance.approach.phase4.p1': 'Paneles de monitoreo en vivo mostraban cómo se desempeñaban los usuarios reales. Los equipos podían identificar problemas inmediatamente, incluidos ralentizaciones, picos de tráfico o errores, sin tener que esperar a que los usuarios se quejaran.',

// --- Results ---
'caseStudies.highPerformance.results.label': 'Los Resultados',
'caseStudies.highPerformance.results.title': 'El rendimiento se convirtió en una ventaja competitiva',
'caseStudies.highPerformance.results.card1.before': 'Lento',
'caseStudies.highPerformance.results.card1.after': '50%↓',
'caseStudies.highPerformance.results.card1.label': 'Cargas de página más rápidas',
'caseStudies.highPerformance.results.card2.before': 'Alto',
'caseStudies.highPerformance.results.card2.after': '40%↓',
'caseStudies.highPerformance.results.card2.label': 'Tasa de rebote reducida',
'caseStudies.highPerformance.results.card3.before': 'Bajo',
'caseStudies.highPerformance.results.card3.after': '30%↑',
'caseStudies.highPerformance.results.card3.label': 'Mayor compromiso del usuario',
'caseStudies.highPerformance.results.card4.before': 'Riesgoso',
'caseStudies.highPerformance.results.card4.after': 'Estable',
'caseStudies.highPerformance.results.card4.label': 'Lanzamientos más rápidos con menos retrocesos',

// --- Testimonial ---
'caseStudies.highPerformance.testimonial.quote': 'Nuestros usuarios ahora exploran, interactúan y completan acciones en lugar de irse después de unos pocos segundos. El rediseño cambió completamente la forma en que las personas interactúan con nuestra plataforma.',
'caseStudies.highPerformance.testimonial.authorName': 'Director de Producto',
'caseStudies.highPerformance.testimonial.authorTitle': 'Empresa de Plataforma Digital',

// --- CTA ---
'caseStudies.highPerformance.cta.title': '¿Quieres Aumentar el Compromiso Sin Más Tráfico?',
'caseStudies.highPerformance.cta.subtitle': 'Ayudamos a las plataformas digitales a convertir visitantes pasivos en usuarios activos a través de un diseño UX basado en investigación.',
'caseStudies.highPerformance.cta.primary': 'Programar una Consulta',
'caseStudies.highPerformance.cta.secondary': 'Ver Más Casos de Estudio',

// ========================================
// INSIGHT PAGE
// The Connection Between Web Architecture, SEO & Digital Growth
// ========================================

// --- Hero ---
'insights.webArchitecture.hero.category': 'Arquitectura Web y SEO',
'insights.webArchitecture.hero.date': '06 de febrero de 2026',
'insights.webArchitecture.hero.title': 'La Conexión Entre la Arquitectura Web, el SEO y el Crecimiento Digital',
'insights.webArchitecture.hero.excerpt': 'La arquitectura web forma la base técnica del SEO y del crecimiento digital a largo plazo. Este artículo explica cómo la estructura, el rendimiento y la escalabilidad influyen directamente en la visibilidad en buscadores, la experiencia del usuario y los resultados empresariales.',
'insights.webArchitecture.hero.bgAlt': 'Fondo de protección de seguros',

// --- Body ---
'insights.webArchitecture.body.p1': 'En el mundo digital actual, un sitio web es más que una simple imagen atractiva. También es una base técnica que influye en lo fácil que es encontrarlo en los motores de búsqueda, qué tan bien funciona para los usuarios y qué tan bien se desempeña el negocio a largo plazo. En el centro de esta base está la arquitectura web. La forma en que los motores de búsqueda analizan, indexan y clasifican tu sitio web es increíblemente significativa. La arquitectura web y el SEO trabajan juntos para construir un motor sólido que ayudará a tener éxito en línea durante mucho tiempo.',

// Section 1
'insights.webArchitecture.section1.title': '1. ¿Qué significa tener arquitectura web?',
'insights.webArchitecture.section1.p1': 'La secuencia de las páginas, la estructura de las URL, los enlaces internos, la navegación y la configuración tecnológica forman parte de la arquitectura web. Una estructura cuidadosamente pensada facilita que los visitantes y los motores de búsqueda entiendan y utilicen el sitio.',
'insights.webArchitecture.section1.p2': 'Cuando la arquitectura es mala, el sitio funciona lentamente, los enlaces fallan, el contenido se duplica y el rastreo es difícil. Todos estos factores perjudican el SEO y la experiencia de los usuarios en tu sitio.',

// Section 2
'insights.webArchitecture.section2.title': '2. Cómo la estructura de un sitio web influye en el SEO',
'insights.webArchitecture.section2.p1': 'Los motores de búsqueda necesitan que tu sitio web tenga una estructura clara. Cuando el diseño es claro y lógico, los bots de los motores de búsqueda pueden rastrear e indexar el contenido correctamente. Puedes distribuir la autoridad de enlaces utilizando categorías de manera efectiva, asegurando claridad en tus URL y enlazando adecuadamente a las páginas relevantes.',
'insights.webArchitecture.section2.p2': 'La velocidad del sitio y su funcionamiento en dispositivos móviles son dos factores arquitectónicos muy importantes que afectan el posicionamiento. Un código ligero, recursos eficientes e infraestructura escalable ayudan con los tiempos de carga y reducen la tasa de rebote. Todo esto influye en los rankings de búsqueda.',
'insights.webArchitecture.section2.p3': 'La navegación estructurada también ayuda a las personas a encontrar contenido más rápido, lo que las mantiene más tiempo en el sitio y reduce el pogo-sticking. Ambos factores son beneficiosos para el SEO.',

// Section 3
'insights.webArchitecture.section3.title': '3. Cómo el SEO impulsa el crecimiento digital',
'insights.webArchitecture.section3.p1': 'El SEO no se trata solo de obtener posiciones altas; también se trata de atraer tráfico que probablemente se convierta en ventas. Cuando el diseño web sigue las mejores prácticas de SEO, las empresas disfrutan de más tráfico orgánico, una mejor experiencia de usuario y tasas de conversión más altas.',
'insights.webArchitecture.section3.p2': 'Un diseño que puede crecer permite a las empresas añadir más contenido, servicios y mercados sin comprometer sus posiciones en los motores de búsqueda. Este nivel de flexibilidad es necesario para el crecimiento digital a largo plazo.',

// Section 4
'insights.webArchitecture.section4.title': '4. La arquitectura web como base para escalar',
'insights.webArchitecture.section4.p1': 'Las empresas que construyen una arquitectura web efectiva desde el principio no tienen que pagar correcciones costosas más adelante. Un diseño optimizado para SEO respalda el marketing de contenidos, facilita que los usuarios encuentren tu sitio y hace que tu negocio parezca más confiable. A medida que aumenta el tráfico orgánico, disminuye la necesidad de anuncios pagados, lo que con el tiempo conduce a un mejor retorno de la inversión.',
'insights.webArchitecture.section4.p2': 'Por el contrario, no diseñar adecuadamente tu arquitectura puede frenar el crecimiento, incluso si tienes contenido y marketing excelentes.',

// --- Key Takeaways ---
'insights.webArchitecture.takeaways.title': 'Conclusiones Clave',
'insights.webArchitecture.takeaways.item1': 'La arquitectura web es la base del rendimiento SEO',
'insights.webArchitecture.takeaways.item2': 'Una estructura clara mejora la capacidad de rastreo e indexación',
'insights.webArchitecture.takeaways.item3': 'El rendimiento y la optimización móvil impactan directamente en los rankings',
'insights.webArchitecture.takeaways.item4': 'Una arquitectura escalable respalda el crecimiento digital a largo plazo',

// --- Conclusion ---
'insights.webArchitecture.conclusion.title': 'Conclusión',
'insights.webArchitecture.conclusion.p1': 'La arquitectura web, el SEO y el crecimiento digital están estrechamente relacionados. Un sitio web bien estructurado facilita que los motores de búsqueda encuentren tu información, mejora la experiencia del usuario y ofrece a tu negocio una plataforma que puede crecer junto con él. Al asegurarse de que la arquitectura del sitio y la estrategia SEO trabajen juntas, las empresas pueden construir una base digital sólida que les ayude a mantenerse visibles, interactuar con los clientes y tener éxito a largo plazo.',

// --- Sidebar ---
'insights.webArchitecture.sidebar.tocTitle': 'En Este Artículo',
'insights.webArchitecture.sidebar.item1': '1. ¿Qué es la arquitectura web?',
'insights.webArchitecture.sidebar.item2': '2. Cómo la arquitectura impacta el SEO',
'insights.webArchitecture.sidebar.item3': '3. Cómo el SEO impulsa el crecimiento digital',
'insights.webArchitecture.sidebar.item4': '4. Arquitectura para escalar',
'insights.webArchitecture.sidebar.item5': '5. Conclusión',
'insights.webArchitecture.sidebar.shareTitle': 'Compartir Este Artículo',
'insights.webArchitecture.sidebar.copyFeedback': '¡Enlace copiado!',

// ========================================
// CASE STUDY PAGE
// Automating Lead Follow-Ups for a Plumbing Business
// ========================================

// --- Hero ---
'caseStudies.plumbing.hero.tag1': 'Automatización',
'caseStudies.plumbing.hero.tag2': 'Gestión de Leads',
'caseStudies.plumbing.hero.industry': 'Servicios Locales',
'caseStudies.plumbing.hero.title': 'Automatización del Seguimiento de Leads para un Negocio de Plomería',
'caseStudies.plumbing.hero.subtitle': 'Cómo una empresa local de plomería aumentó las reservas y los ingresos al automatizar el seguimiento de leads sin aumentar el gasto en publicidad ni el personal.',
'caseStudies.plumbing.hero.bgAlt': 'Fondo de protección de seguros',

// --- Metrics ---
'caseStudies.plumbing.metrics.item1.value': '80%↓',
'caseStudies.plumbing.metrics.item1.label': 'Tiempo de Respuesta',
'caseStudies.plumbing.metrics.item2.value': '47%↑',
'caseStudies.plumbing.metrics.item2.label': 'Trabajos Reservados',
'caseStudies.plumbing.metrics.item3.value': '35%↑',
'caseStudies.plumbing.metrics.item3.label': 'Ingresos Mensuales',
'caseStudies.plumbing.metrics.item4.value': '0',
'caseStudies.plumbing.metrics.item4.label': 'Leads Perdidos',

// --- Context ---
'caseStudies.plumbing.context.label': 'El Contexto',
'caseStudies.plumbing.context.title': 'Alto volumen de leads, bajo seguimiento',
'caseStudies.plumbing.context.p1': 'Un negocio de plomería de tamaño mediano que presta servicios en un área metropolitana local estaba generando un flujo constante de leads desde su sitio web, Google Ads, solicitudes de servicio de emergencia y consultas telefónicas.',
'caseStudies.plumbing.context.p2': 'La demanda era fuerte, pero las reservas eran inconsistentes. El problema no era el marketing - era el seguimiento lento y poco confiable de los leads, lo que hacía que los clientes potenciales acudieran a la competencia.',
'caseStudies.plumbing.context.p3': 'Este estudio de caso describe cómo la automatización del seguimiento de leads transformó los tiempos de respuesta, aumentó las conversiones y desbloqueó el crecimiento de ingresos sin gasto adicional en marketing.',

// --- Challenge ---
'caseStudies.plumbing.challenge.label': 'El Desafío',
'caseStudies.plumbing.challenge.title': 'El seguimiento manual estaba costando ingresos',
'caseStudies.plumbing.challenge.p1': 'Antes de la automatización, un pequeño equipo de oficina manejaba manualmente cada lead. Este enfoque generaba presión operativa y oportunidades perdidas.',
'caseStudies.plumbing.challenge.item1': 'Los leads eran contactados horas después o al día siguiente',
'caseStudies.plumbing.challenge.item2': 'Los leads fuera del horario laboral y en períodos ocupados se perdían por completo',
'caseStudies.plumbing.challenge.item3': 'Mensajes inconsistentes y sin seguimiento estructurado',
'caseStudies.plumbing.challenge.item4': 'Los leads frecuentemente elegían competidores que respondían más rápido',
'caseStudies.plumbing.challenge.p2': 'En situaciones de plomería de emergencia, la velocidad determina la confianza. Las respuestas retrasadas se traducían directamente en trabajos perdidos.',

// --- Approach ---
'caseStudies.plumbing.approach.label': 'Nuestro Enfoque',
'caseStudies.plumbing.approach.title': 'Seguimiento automatizado, rápido y centrado en el cliente',

// Phase 1
'caseStudies.plumbing.approach.phase1.number': '1',
'caseStudies.plumbing.approach.phase1.title': 'Captura Centralizada de Leads',
'caseStudies.plumbing.approach.phase1.duration': 'Semana 1',
'caseStudies.plumbing.approach.phase1.p1': 'Todos los leads provenientes de formularios web, anuncios, solicitudes de emergencia y llamadas se dirigieron a un único CRM. Esto aseguró visibilidad, responsabilidad y cero pérdida de leads.',

// Phase 2
'caseStudies.plumbing.approach.phase2.number': '2',
'caseStudies.plumbing.approach.phase2.title': 'Respuestas Automatizadas Inmediatas',
'caseStudies.plumbing.approach.phase2.duration': 'Semana 2',
'caseStudies.plumbing.approach.phase2.p1': 'Dentro de los 60 segundos posteriores al envío de un formulario o consulta, los prospectos recibían lo siguiente:',
'caseStudies.plumbing.approach.phase2.item1': 'Un mensaje SMS personalizado confirmando la recepción de su solicitud',
'caseStudies.plumbing.approach.phase2.item2': 'Un correo electrónico con información sobre el servicio y los próximos pasos',
'caseStudies.plumbing.approach.phase2.item3': 'Esta respuesta rápida hacía que los clientes sintieran que la ayuda estaba en camino.',

// Phase 3
'caseStudies.plumbing.approach.phase3.number': '3',
'caseStudies.plumbing.approach.phase3.title': 'Secuencias Inteligentes de Seguimiento',
'caseStudies.plumbing.approach.phase3.duration': 'Semana 3',
'caseStudies.plumbing.approach.phase3.p1': 'Si un lead no reservaba inmediatamente, el sistema activaba seguimientos programados a las dos horas, un día y tres días - manteniendo el impulso sin ser intrusivo.',

// Phase 4
'caseStudies.plumbing.approach.phase4.number': '4',
'caseStudies.plumbing.approach.phase4.title': 'Programación y Alertas al Equipo',
'caseStudies.plumbing.approach.phase4.duration': 'Semana 4',
'caseStudies.plumbing.approach.phase4.p1': 'Los leads podían reservar citas instantáneamente a través de enlaces de programación, mientras que el personal de oficina recibía alertas en tiempo real sobre respuestas, reservas y palabras clave de alta intención.',

// --- Results ---
'caseStudies.plumbing.results.label': 'Los Resultados',
'caseStudies.plumbing.results.title': 'La automatización generó crecimiento medible',
'caseStudies.plumbing.results.card1.before': 'Horas',
'caseStudies.plumbing.results.card1.after': '< 1 min',
'caseStudies.plumbing.results.card1.label': 'Tiempo de respuesta reducido',
'caseStudies.plumbing.results.card2.before': 'Bajo',
'caseStudies.plumbing.results.card2.after': '47%↑',
'caseStudies.plumbing.results.card2.label': 'Más leads convertidos en trabajos',
'caseStudies.plumbing.results.card3.before': 'Estable',
'caseStudies.plumbing.results.card3.after': '35%↑',
'caseStudies.plumbing.results.card3.label': 'Crecimiento mensual de ingresos',
'caseStudies.plumbing.results.card4.before': 'Manual',
'caseStudies.plumbing.results.card4.after': 'Automatizado',
'caseStudies.plumbing.results.card4.label': 'Cero leads perdidos',

// --- Testimonial ---
'caseStudies.plumbing.testimonial.quote': 'Our users now explore, interact, and complete actions instead of leaving after a few seconds. The redesign completely changed how people engage with our platform.',
'caseStudies.plumbing.testimonial.authorName': 'Head of Product',
'caseStudies.plumbing.testimonial.authorTitle': 'Digital Platform Company',

// --- CTA ---
'caseStudies.plumbing.cta.title': 'Want to Increase Engagement Without More Traffic?',
'caseStudies.plumbing.cta.subtitle': 'We help digital platforms turn passive visitors into active users through research-driven UX design.',
'caseStudies.plumbing.cta.primary': 'Schedule a Consultation',
'caseStudies.plumbing.cta.secondary': 'View More Case Studies',

// PAGE: caseStudy.uxRedesignIncreaseEngagement
// LANGUAGE: es

// --- Hero ---
'caseStudy.uxRedesignIncreaseEngagement.hero.imageAlt': 'Fondo de protección de seguros',
'caseStudy.uxRedesignIncreaseEngagement.hero.tag1': 'Diseño UI/UX',
'caseStudy.uxRedesignIncreaseEngagement.hero.tag2': 'Datos y Analítica',
'caseStudy.uxRedesignIncreaseEngagement.hero.tag3': 'Empresa de plataforma digital',
'caseStudy.uxRedesignIncreaseEngagement.hero.title': 'Rediseño UX para aumentar la interacción',
'caseStudy.uxRedesignIncreaseEngagement.hero.subtitle': 'Transformación de visitantes pasivos en usuarios activos mediante mejoras estratégicas de UX, convirtiendo navegadores en usuarios comprometidos sin gasto adicional en adquisición de tráfico.',

// --- Metrics Bar ---
'caseStudy.uxRedesignIncreaseEngagement.metrics.item1.value': '42%↓',
'caseStudy.uxRedesignIncreaseEngagement.metrics.item1.label': 'Tasa de rebote',
'caseStudy.uxRedesignIncreaseEngagement.metrics.item2.value': '65%↑',
'caseStudy.uxRedesignIncreaseEngagement.metrics.item2.label': 'Duración de la sesión',
'caseStudy.uxRedesignIncreaseEngagement.metrics.item3.value': '78%↑',
'caseStudy.uxRedesignIncreaseEngagement.metrics.item3.label': 'Interacciones con CTA',
'caseStudy.uxRedesignIncreaseEngagement.metrics.item4.value': '4–5',
'caseStudy.uxRedesignIncreaseEngagement.metrics.item4.label': 'Acciones del usuario por visita',

// --- Context ---
'caseStudy.uxRedesignIncreaseEngagement.context.sectionLabel': 'El Contexto',
'caseStudy.uxRedesignIncreaseEngagement.context.heading': 'El tráfico era fuerte. La interacción no lo era.',
'caseStudy.uxRedesignIncreaseEngagement.context.paragraph1': 'La plataforma atraía un flujo constante de visitantes a través de búsqueda, campañas pagadas y referencias. La notoriedad no era el problema — la interacción lo era.',
'caseStudy.uxRedesignIncreaseEngagement.context.paragraph2': 'Los usuarios llegaban pero se iban rápidamente. Las sesiones eran cortas, la interacción era mínima y muy pocos visitantes se registraban, exploraban herramientas o convertían. El negocio no tenía problemas de tráfico — tenía problemas para convertir visitantes en usuarios activos.',

// --- Challenge ---
'caseStudy.uxRedesignIncreaseEngagement.challenge.sectionLabel': 'El Desafío',
'caseStudy.uxRedesignIncreaseEngagement.challenge.heading': 'Alta tasa de abandono y baja interacción',
'caseStudy.uxRedesignIncreaseEngagement.challenge.intro': 'A pesar de una adquisición sólida, el comportamiento del usuario reveló múltiples barreras de UX que impedían una interacción más profunda:',
'caseStudy.uxRedesignIncreaseEngagement.challenge.item1.title': 'Salidas inmediatas:',
'caseStudy.uxRedesignIncreaseEngagement.challenge.item1.description': 'Muchos usuarios abandonaban páginas clave en segundos sin interactuar.',
'caseStudy.uxRedesignIncreaseEngagement.challenge.item2.title': 'Baja profundidad de desplazamiento:',
'caseStudy.uxRedesignIncreaseEngagement.challenge.item2.description': 'El contenido importante y las funciones rara vez eran vistas.',
'caseStudy.uxRedesignIncreaseEngagement.challenge.item3.title': 'Rutas confusas:',
'caseStudy.uxRedesignIncreaseEngagement.challenge.item3.description': 'La navegación y la estructura del contenido hacían poco claro qué hacer a continuación.',
'caseStudy.uxRedesignIncreaseEngagement.challenge.item4.title': 'Jerarquía visual débil:',
'caseStudy.uxRedesignIncreaseEngagement.challenge.item4.description': 'Las acciones clave no destacaban, lo que provocaba inacción.',
'caseStudy.uxRedesignIncreaseEngagement.challenge.item5.title': 'CTAs poco claros:',
'caseStudy.uxRedesignIncreaseEngagement.challenge.item5.description': 'Los llamados a la acción estaban ausentes o mal posicionados.',

// --- Approach ---
'caseStudy.uxRedesignIncreaseEngagement.approach.sectionLabel': 'Nuestro Enfoque',
'caseStudy.uxRedesignIncreaseEngagement.approach.heading': 'Rediseño UX impulsado por el comportamiento',

'caseStudy.uxRedesignIncreaseEngagement.approach.phase1.number': '1',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase1.title': 'Análisis del comportamiento del usuario',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase1.duration': 'Semanas 1–2',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase1.description': 'Análisis de mapas de calor, seguimiento de desplazamiento y flujos de usuario para identificar puntos de fricción, zonas de abandono y señales de intención poco claras.',

'caseStudy.uxRedesignIncreaseEngagement.approach.phase2.number': '2',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase2.title': 'Navegación y arquitectura de la información',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase2.duration': 'Semanas 3–4',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase2.description': 'Simplificación de la navegación, agrupación de funciones relacionadas y clarificación de rutas primarias y secundarias para que los usuarios siempre supieran qué hacer a continuación.',

'caseStudy.uxRedesignIncreaseEngagement.approach.phase3.number': '3',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase3.title': 'Jerarquía visual y optimización de CTA',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase3.duration': 'Semanas 5–7',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase3.description': 'Uso de contraste, espaciado y priorización del diseño para resaltar acciones clave y reducir la carga cognitiva.',

'caseStudy.uxRedesignIncreaseEngagement.approach.phase4.number': '4',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase4.title': 'Microinteracciones y retroalimentación',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase4.duration': 'Semanas 8–10',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase4.description': 'Introducción de estados hover, indicadores de progreso y retroalimentación responsiva para que la experiencia se sintiera dinámica y humana.',

'caseStudy.uxRedesignIncreaseEngagement.approach.phase5.number': '5',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase5.title': 'Pruebas y medición',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase5.duration': 'Semanas 11–12',
'caseStudy.uxRedesignIncreaseEngagement.approach.phase5.description': 'Monitoreo continuo de métricas de interacción y optimización de flujos mediante iteración basada en datos.',

// --- Results ---
'caseStudy.uxRedesignIncreaseEngagement.results.sectionLabel': 'Los Resultados',
'caseStudy.uxRedesignIncreaseEngagement.results.heading': 'De navegación pasiva a interacción activa',

'caseStudy.uxRedesignIncreaseEngagement.results.card1.before': 'Alto',
'caseStudy.uxRedesignIncreaseEngagement.results.card1.arrow': '→',
'caseStudy.uxRedesignIncreaseEngagement.results.card1.after': '↓42%',
'caseStudy.uxRedesignIncreaseEngagement.results.card1.label': 'Tasa de rebote significativamente reducida',

'caseStudy.uxRedesignIncreaseEngagement.results.card2.before': 'Bajo',
'caseStudy.uxRedesignIncreaseEngagement.results.card2.arrow': '→',
'caseStudy.uxRedesignIncreaseEngagement.results.card2.after': '↑65%',
'caseStudy.uxRedesignIncreaseEngagement.results.card2.label': 'Duración de la sesión aumentada',

'caseStudy.uxRedesignIncreaseEngagement.results.card3.before': 'Mínimo',
'caseStudy.uxRedesignIncreaseEngagement.results.card3.arrow': '→',
'caseStudy.uxRedesignIncreaseEngagement.results.card3.after': '↑78%',
'caseStudy.uxRedesignIncreaseEngagement.results.card3.label': 'Aumento de interacciones con CTA',

'caseStudy.uxRedesignIncreaseEngagement.results.card4.before': '1–2',
'caseStudy.uxRedesignIncreaseEngagement.results.card4.arrow': '→',
'caseStudy.uxRedesignIncreaseEngagement.results.card4.after': '4–5',
'caseStudy.uxRedesignIncreaseEngagement.results.card4.label': 'Las acciones del usuario por visita se duplicaron',

// --- Testimonial ---
'caseStudy.uxRedesignIncreaseEngagement.testimonial.quote': 'Nuestros usuarios ahora exploran, interactúan y completan acciones en lugar de irse después de unos segundos. El rediseño cambió completamente la forma en que las personas interactúan con nuestra plataforma.',
'caseStudy.uxRedesignIncreaseEngagement.testimonial.authorName': 'Jefe de Producto',
'caseStudy.uxRedesignIncreaseEngagement.testimonial.authorTitle': 'Empresa de plataforma digital',

// --- CTA ---
'caseStudy.uxRedesignIncreaseEngagement.cta.heading': '¿Quieres aumentar la interacción sin más tráfico?',
'caseStudy.uxRedesignIncreaseEngagement.cta.description': 'Ayudamos a plataformas digitales a convertir visitantes pasivos en usuarios activos mediante diseño UX basado en investigación.',
'caseStudy.uxRedesignIncreaseEngagement.cta.primaryButton': 'Programar una consulta',
'caseStudy.uxRedesignIncreaseEngagement.cta.secondaryButton': 'Ver más estudios de caso',

// ========================================
// CONTACT PAGE
// Book a Discovery Call
// ========================================

// --- Hero ---
'contact.discovery.hero.title': 'Reservar una Llamada de Descubrimiento',
'contact.discovery.hero.subtitle': 'Una conversación estructurada sobre sus operaciones — sin discurso de ventas. Elija un horario que le funcione.',
'contact.discovery.hero.bgAlt': 'Fondo de protección de seguros',

// ========================================
// INSIGHTS ARTICLE
// AI Adoption Roadmap (Full Literal Extraction)
// ========================================

// --- Hero ---
'insights.aiAdoption.hero.image.alt': 'Fondo de protección de seguros',
'insights.aiAdoption.hero.category': 'Estrategia de IA',
'insights.aiAdoption.hero.date': '26 de febrero de 2026',
'insights.aiAdoption.hero.title': 'Hoja de Ruta de Adopción de IA para Medianas Empresas',
'insights.aiAdoption.hero.excerpt': 'La IA ya no es exclusiva de los gigantes tecnológicos. Las medianas empresas ahora pueden desplegar sistemas de IA gobernados y escalables, siempre que sigan una hoja de ruta estructurada alineada con los resultados de negocio.',

// --- Body Intro ---
'insights.aiAdoption.body.intro.p1': 'Las empresas tecnológicas ya no tienen el monopolio de la inteligencia artificial. Hoy en día, las medianas empresas pueden utilizar potentes herramientas de IA para hacer sus operaciones más eficientes, reducir gastos y encontrar nuevas formas de generar ingresos. Pero el éxito en la adopción de la IA no ocurre por arte de magia. Requiere una hoja de ruta bien planificada que conecte la tecnología con la estrategia empresarial, establezca bases de datos sólidas y escale de manera inteligente.',
'insights.aiAdoption.body.intro.p2': 'Aquí tienes una guía realista, paso a paso, para ayudar a tu mediana empresa a comenzar con la IA.',

// --- Section 1 ---
'insights.aiAdoption.body.businessGoals.title': '1. Establece objetivos comerciales claros',
'insights.aiAdoption.body.businessGoals.p1': 'La IA nunca debería empezar con un "intentemos algo genial". La primera pregunta debe ser: "¿Qué problema estamos intentando resolver?"',
'insights.aiAdoption.body.businessGoals.p2': 'Identifica áreas que tendrán un gran impacto, tales como:',
'insights.aiAdoption.body.businessGoals.item1': 'Acelerar el tiempo de respuesta del servicio al cliente',
'insights.aiAdoption.body.businessGoals.item2': 'Aumentar la eficiencia operativa',
'insights.aiAdoption.body.businessGoals.item3': 'Mejorar la precisión de los pronósticos de ventas',
'insights.aiAdoption.body.businessGoals.item4': 'Optimizar la asignación de recursos',
'insights.aiAdoption.body.businessGoals.p3': 'Busca casos de uso que tengan un efecto directo en los ingresos, los ahorros o la satisfacción del cliente. Es más fácil cuantificar el rendimiento cuando el objetivo de negocio está claro.',

// --- Section 2 ---
'insights.aiAdoption.body.readiness.title': '2. Evalúa si estás preparado para la IA',
'insights.aiAdoption.body.readiness.p1': 'Antes de comprar herramientas de IA, analiza tus capacidades actuales. Las investigaciones del MIT CISR muestran que muchas empresas enfrentan problemas porque comienzan a usar IA sin conocer su nivel de madurez.',
'insights.aiAdoption.body.readiness.p2': 'Factores importantes a evaluar:',
'insights.aiAdoption.body.readiness.item1': 'Calidad de los Datos: ¿Están los datos limpios, estructurados y son confiables?',
'insights.aiAdoption.body.readiness.item2': 'Infraestructura: ¿Pueden los sistemas soportar cargas de trabajo de IA escalables?',
'insights.aiAdoption.body.readiness.item3': 'Talento y Capacidades: ¿Poseen los equipos internos alfabetización de datos y habilidades de supervisión de IA?',
'insights.aiAdoption.body.readiness.item4': 'Gobernanza: ¿Están establecidos los marcos de cumplimiento, privacidad y seguridad?',
'insights.aiAdoption.body.readiness.p3': 'Esta evaluación elimina errores costosos y crea metas razonables.',

// --- Image ---
'insights.aiAdoption.body.image.alt': 'Hoja de Ruta de Adopción de IA para Medianas Empresas',

// --- Section 3 ---
'insights.aiAdoption.body.dataFoundation.title': '3. Construye una Base de Datos Sólida',
'insights.aiAdoption.body.dataFoundation.p1': 'Los datos son lo que la IA necesita para funcionar. Los proyectos de IA se detendrán si tus datos están dispersos entre departamentos o atrapados en sistemas antiguos.',
'insights.aiAdoption.body.dataFoundation.p2': 'Las medianas empresas deben priorizar lo siguiente:',
'insights.aiAdoption.body.dataFoundation.item1': 'Almacenamiento de datos centralizado, como lagos de datos o plataformas unificadas',
'insights.aiAdoption.body.dataFoundation.item2': 'Limpieza y estandarización de datos',
'insights.aiAdoption.body.dataFoundation.item3': 'Políticas para una propiedad y gobernanza de datos clara',
'insights.aiAdoption.body.dataFoundation.p3': 'Plataformas como Databricks permiten a las empresas unificar datos y analítica en un solo lugar, lo que reduce los silos y facilita la colaboración.',
'insights.aiAdoption.body.dataFoundation.p4': 'Incluso los mejores modelos de IA no funcionarán bien si no tienen acceso a datos precisos.',

// --- Section 4 ---
'insights.aiAdoption.body.pilots.title': '4. Comienza con proyectos piloto de gran impacto',
'insights.aiAdoption.body.pilots.p1': 'En lugar de intentar cambiar toda la empresa a la vez, comienza con proyectos piloto pequeños.',
'insights.aiAdoption.body.pilots.p2': 'Las mejores características de un piloto son:',
'insights.aiAdoption.body.pilots.item1': 'Alcance claramente definido',
'insights.aiAdoption.body.pilots.item2': 'Métricas de éxito medibles',
'insights.aiAdoption.body.pilots.item3': 'Sólido patrocinio ejecutivo',
'insights.aiAdoption.body.pilots.item4': 'Mecanismos definidos de seguimiento del ROI',
'insights.aiAdoption.body.pilots.p3': 'Por ejemplo, usar un chatbot de IA para ayudar a los clientes o usar analítica predictiva para gestionar el inventario.',
'insights.aiAdoption.body.pilots.p4': 'IBM y otras compañías enfatizan la importancia de empezar pequeño pero planificar el crecimiento desde el principio. Los triunfos tempranos aumentan la confianza interna y justifican la inversión.',

// --- Section 5 ---
'insights.aiAdoption.body.governance.title': '5. Establece la gestión de riesgos y la gobernanza',
'insights.aiAdoption.body.governance.p1': 'La gobernanza se vuelve más importante a medida que los sistemas de IA toman decisiones.',
'insights.aiAdoption.body.governance.p2': 'Las medianas empresas necesitan establecer reglas sobre:',
'insights.aiAdoption.body.governance.item1': 'Privacidad de datos y cumplimiento regulatorio',
'insights.aiAdoption.body.governance.item2': 'Transparencia y explicabilidad del modelo',
'insights.aiAdoption.body.governance.item3': 'Detección de sesgos y estándares de uso ético',
'insights.aiAdoption.body.governance.item4': 'Monitoreo del rendimiento y auditabilidad',
'insights.aiAdoption.body.governance.p3': 'Organizaciones consultoras como Gartner dicen que las empresas deben equilibrar la innovación con la gestión de riesgos para evitar problemas regulatorios y de reputación.',
'insights.aiAdoption.body.governance.p4': 'Una gobernanza sólida genera confianza con los clientes, empleados y otros grupos de interés.',

// --- Section 6 ---
'insights.aiAdoption.body.talent.title': '6. Fomenta una cultura de IA y desarrolla el talento',
'insights.aiAdoption.body.talent.p1': 'La transformación de la IA es tanto cultural como técnica.',
'insights.aiAdoption.body.talent.p2': 'Las organizaciones deben:',
'insights.aiAdoption.body.talent.item1': 'Capacitar al personal en alfabetización de datos y fundamentos de IA',
'insights.aiAdoption.body.talent.item2': 'Fomentar la colaboración interfuncional',
'insights.aiAdoption.body.talent.item3': 'Involucrar a expertos externos cuando se requiera capacidad especializada',
'insights.aiAdoption.body.talent.item4': 'Comunicar cómo la IA mejora los roles en lugar de reemplazarlos',
'insights.aiAdoption.body.talent.p3': 'La adopción se acelera cuando los usuarios de negocio, y no solo los equipos de TI, están facultados para aprovechar las herramientas de IA de manera responsable.',

// --- Section 7 ---
'insights.aiAdoption.body.workflow.title': '7. Integra la IA en los flujos de trabajo principales',
'insights.aiAdoption.body.workflow.p1': 'La IA aporta valor cuando se integra directamente en los sistemas operativos, no cuando se aísla en un tablero de control.',
'insights.aiAdoption.body.workflow.p2': 'Esto incluye:',
'insights.aiAdoption.body.workflow.item1': 'Integrar los resultados de la IA en los sistemas CRM, ERP y financieros',
'insights.aiAdoption.body.workflow.item2': 'Automatizar decisiones rutinarias con controles de supervisión humana',
'insights.aiAdoption.body.workflow.item3': 'Refinar continuamente los modelos basados en la retroalimentación operativa',
'insights.aiAdoption.body.workflow.p3': 'La IA debe apoyar la toma de decisiones en tiempo real dentro de los flujos de trabajo diarios.',

// --- Section 8 ---
'insights.aiAdoption.body.scaling.title': '8. Escala con una Arquitectura Estructurada',
'insights.aiAdoption.body.scaling.p1': 'Una vez que los pilotos demuestran un impacto medible, el escalado debe ser deliberado, no fragmentado.',
'insights.aiAdoption.body.scaling.p2': 'Escalar requiere:',
'insights.aiAdoption.body.scaling.item1': 'Plataformas estandarizadas y entornos de datos compartidos',
'insights.aiAdoption.body.scaling.item2': 'Supervisión centralizada de la gobernanza',
'insights.aiAdoption.body.scaling.item3': 'Documentación y manuales operativos',
'insights.aiAdoption.body.scaling.item4': 'Medición continua del rendimiento',
'insights.aiAdoption.body.scaling.p3': 'Evita los silos departamentales de IA. Construye un ecosistema unificado capaz de ofrecer confiabilidad operativa a largo plazo.',

// --- Section 9 ---
'insights.aiAdoption.body.continuous.title': '9. Mide y Mejora Continuamente',
'insights.aiAdoption.body.continuous.p1': 'La adopción de IA no es una implementación única; es una capacidad en constante evolución.',
'insights.aiAdoption.body.continuous.p2': 'Las empresas deben monitorear:',
'insights.aiAdoption.body.continuous.item1': 'Retorno de la inversión (ROI)',
'insights.aiAdoption.body.continuous.item2': 'Ganancias en eficiencia operativa',
'insights.aiAdoption.body.continuous.item3': 'Métricas de satisfacción del cliente',
'insights.aiAdoption.body.continuous.item4': 'Precisión y estabilidad del modelo',
'insights.aiAdoption.body.continuous.item5': 'Indicadores de cumplimiento y auditoría',
'insights.aiAdoption.body.continuous.p3': 'El ajuste continuo asegura que los sistemas de IA permanezcan alineados con los objetivos de negocio en evolución.',

// --- Key Takeaways ---
'insights.aiAdoption.body.takeaways.title': 'Conclusiones Clave',
'insights.aiAdoption.body.takeaways.item1': 'La adopción de IA debe comenzar con objetivos de negocio medibles',
'insights.aiAdoption.body.takeaways.item2': 'La preparación de los datos determina la confiabilidad operativa',
'insights.aiAdoption.body.takeaways.item3': 'La gobernanza debe integrarse desde el primer día',
'insights.aiAdoption.body.takeaways.item4': 'Los proyectos piloto validan el escalado en toda la empresa',
'insights.aiAdoption.body.takeaways.item5': 'La medición continua asegura un ROI sostenido',

// --- Conclusion ---
'insights.aiAdoption.body.conclusion.title': 'Conclusión',
'insights.aiAdoption.body.conclusion.p1': 'Para las medianas empresas, la adopción de la IA representa tanto una oportunidad estratégica como un imperativo operativo.',
'insights.aiAdoption.body.conclusion.p2': 'Las organizaciones que tienen éxito:',
'insights.aiAdoption.body.conclusion.item1': 'Alínean la IA con objetivos de negocio claros',
'insights.aiAdoption.body.conclusion.item2': 'Establecen bases de datos sólidas',
'insights.aiAdoption.body.conclusion.item3': 'Lanzan pilotos controlados de alto impacto',
'insights.aiAdoption.body.conclusion.item4': 'Integran la gobernanza y el cumplimiento de manera temprana',
'insights.aiAdoption.body.conclusion.item5': 'Escalan a través de una arquitectura unificada',
'insights.aiAdoption.body.conclusion.item6': 'Se comprometen con una optimización continua',
'insights.aiAdoption.body.conclusion.p3': 'La IA no se trata de seguir tendencias. Se trata de construir sistemas gobernados que conviertan los datos empresariales en decisiones confiables y medibles.',
'insights.aiAdoption.body.conclusion.p4': 'Comienza deliberadamente. Construye bases sólidas. Escala con propósito.',

// --- Sidebar ---
'insights.aiAdoption.sidebar.tocTitle': 'En este artículo',
'insights.aiAdoption.sidebar.toc.item1': '1. Definir objetivos comerciales claros',
'insights.aiAdoption.sidebar.toc.item2': '2. Evaluar la preparación organizacional',
'insights.aiAdoption.sidebar.toc.item3': '3. Construir una base de datos sólida',
'insights.aiAdoption.sidebar.toc.item4': '4. Lanzar proyectos piloto de alto impacto',
'insights.aiAdoption.sidebar.toc.item5': '5. Integrar gobernanza y gestión de riesgos',
'insights.aiAdoption.sidebar.toc.item6': '6. Desarrollar talento y cultura de IA',
'insights.aiAdoption.sidebar.toc.item7': '7. Integrar la IA en flujos de trabajo',
'insights.aiAdoption.sidebar.toc.item8': '8. Escalar con arquitectura estructurada',
'insights.aiAdoption.sidebar.toc.item9': '9. Medir y mejorar continuamente',
'insights.aiAdoption.sidebar.toc.item10': '10. Conclusión',

'insights.aiAdoption.sidebar.shareTitle': 'Compartir este artículo',
'insights.aiAdoption.sidebar.share.linkedin': 'Compartir en LinkedIn',
'insights.aiAdoption.sidebar.share.twitter': 'Compartir en Twitter',
'insights.aiAdoption.sidebar.share.facebook': 'Compartir en Facebook',
'insights.aiAdoption.sidebar.share.copy': 'Copiar enlace',
'insights.aiAdoption.sidebar.copyFeedback': '¡Enlace copiado!',

// ========================================
// INSIGHTS ARTICLE
// From Data to Decisions
// ========================================

// --- Hero ---
'insights.fromDataToDecisions.hero.image.alt': 'Fondo de protección de seguros',
'insights.fromDataToDecisions.hero.category': 'Estrategia de IA y Arquitectura Empresarial',
'insights.fromDataToDecisions.hero.date': '24 de febrero de 2026',
'insights.fromDataToDecisions.hero.title': 'De los Datos a las Decisiones: Construyendo un Ecosistema de IA Listo para la Empresa',
'insights.fromDataToDecisions.hero.excerpt': 'La IA empresarial en 2026 no se trata de experimentación. Se trata de construir ecosistemas escalables y gobernados que conviertan los datos en decisiones de negocio confiables.',

// --- Body Intro ---
'insights.fromDataToDecisions.body.intro.p1': 'En 2026, construir un ecosistema de IA listo para la empresa no consiste en probar las herramientas más novedosas. Se trata de crear un sistema que pueda crecer, que sea confiable y que funcione para todos en su compañía, al tiempo que respalda sus objetivos comerciales. Hay una gran diferencia entre probar algunos programas de IA y convertir la IA en parte del funcionamiento diario de su empresa.',

// --- Section 1 ---
'insights.fromDataToDecisions.body.enterpriseMeaning.title': '1. Qué significa realmente "IA Lista para la Empresa"',
'insights.fromDataToDecisions.body.enterpriseMeaning.p1': 'Piense en la diferencia entre un prototipo y un coche de producción. El prototipo puede verse genial, pero el coche de producción ha sido sometido a muchas pruebas, está fabricado para durar y diseñado para funcionar todos los días. El modelo de producción es la IA que está lista para los negocios.',
'insights.fromDataToDecisions.body.enterpriseMeaning.p2': 'Debe cumplir con:',
'insights.fromDataToDecisions.body.enterpriseMeaning.item1': 'Escalabilidad a medida que crece el número de usuarios y datos.',
'insights.fromDataToDecisions.body.enterpriseMeaning.item2': 'Integración con sistemas actuales como CRM, ERP y plataformas de cadena de suministro.',
'insights.fromDataToDecisions.body.enterpriseMeaning.item3': 'Honestidad, datos precisos y decisiones que puedan ser explicadas.',
'insights.fromDataToDecisions.body.enterpriseMeaning.item4': 'Conciencia del entorno y de cómo funcionan sus flujos de trabajo específicos.',
'insights.fromDataToDecisions.body.enterpriseMeaning.p3': 'Databricks y otras compañías enfatizan que la IA empresarial no se trata solo de realizar pruebas aisladas. Requiere un entorno unificado donde los datos fluyan libremente y la automatización inteligente sea un elemento normal del negocio.',

// --- Section 2 ---
'insights.fromDataToDecisions.body.infrastructure.title': '2. Por qué la infraestructura es importante',
'insights.fromDataToDecisions.body.infrastructure.p1': 'Es fácil conectar una herramienta de IA y pensar que funcionará. Pero la infraestructura es lo que marca la diferencia entre las pruebas a corto plazo y el cambio a largo plazo.',
'insights.fromDataToDecisions.body.infrastructure.p2': 'Sin los cimientos adecuados:',
'insights.fromDataToDecisions.body.infrastructure.item1': 'Cada departamento crea soluciones de IA que no funcionan entre sí.',
'insights.fromDataToDecisions.body.infrastructure.item2': 'Los datos siguen dispersos en diferentes plataformas.',
'insights.fromDataToDecisions.body.infrastructure.item3': 'La automatización se ve bloqueada por procesos manuales.',
'insights.fromDataToDecisions.body.infrastructure.item4': 'El escalado se sale de control.',
'insights.fromDataToDecisions.body.infrastructure.item5': 'Aumentan los riesgos de seguridad y cumplimiento.',
'insights.fromDataToDecisions.body.infrastructure.p3': 'Una infraestructura sólida hace posible la fusión de datos, lo que significa unir los datos de clientes, ventas y productos en una sola base. También facilita la toma de decisiones autónoma, permitiendo que la IA gestione tareas como aprobaciones rutinarias, enrutamiento de clientes u optimización de inventarios por sí sola.',
'insights.fromDataToDecisions.body.infrastructure.p4': 'La infraestructura también garantiza que se sigan las reglas y que la gobernanza esté presente en sectores regulados. No podrá salir del modo piloto si omite este paso.',
'insights.fromDataToDecisions.body.infrastructure.image.alt': 'Por qué la estrategia de IA falla sin cimientos sólidos de TI',



// --- Section 3 ---
'insights.fromDataToDecisions.body.maturity.title': '3. Los cuatro niveles de madurez de la IA',
'insights.fromDataToDecisions.body.maturity.item1': 'Adopción Inicial: Pilotos limitados con impacto operativo mínimo',
'insights.fromDataToDecisions.body.maturity.item2': 'Crecimiento Fragmentado: Experimentación a nivel de departamento',
'insights.fromDataToDecisions.body.maturity.item3': 'Integración Empresarial: Plataformas unificadas y gobernanza',
'insights.fromDataToDecisions.body.maturity.item4': 'IA Transformacional: IA integrada en procesos competitivos centrales',
'insights.fromDataToDecisions.body.maturity.p1': 'La IA empresarial transformadora significa integrar la IA en las operaciones comerciales clave para obtener una ventaja sobre sus competidores.',
'insights.fromDataToDecisions.body.maturity.p2': 'La mayoría de las empresas se encuentran hoy entre las etapas dos y tres. Este marco le muestra cómo crecer de forma planificada en lugar de hacerlo de manera desordenada.',



// --- Section 4 ---
'insights.fromDataToDecisions.body.dataReadiness.title': '4. ¿Qué hace que los datos estén listos para la IA?',
'insights.fromDataToDecisions.body.dataReadiness.p1': 'No todos los datos pueden ser utilizados por la IA. Los datos listos para la IA deben cumplir tres requisitos:',
'insights.fromDataToDecisions.body.dataReadiness.item1': 'Calidad: Datos limpios, consistentes y validados',
'insights.fromDataToDecisions.body.dataReadiness.item2': 'Accesibilidad: Estructurados y disponibles para sistemas y tomadores de decisiones',
'insights.fromDataToDecisions.body.dataReadiness.item3': 'Confianza: Gobernados, seguros y que cumplen con la privacidad',
'insights.fromDataToDecisions.body.dataReadiness.p2': 'Los modelos de IA entrenados con datos inconsistentes o fragmentados generarán resultados poco confiables. Las arquitecturas de datos centralizadas transforman la información dispersa en activos estructurados de calidad para la toma de decisiones.',
'insights.fromDataToDecisions.body.dataReadiness.p3': 'Las entradas de datos deficientes crean salidas inestables. Las bases de datos sólidas permiten una automatización dependiente.',

// --- Section 5 ---
'insights.fromDataToDecisions.body.roadmap.title': '5. Diseñando una hoja de ruta estratégica de IA',
'insights.fromDataToDecisions.body.roadmap.p1': 'La tecnología por sí sola no crea el éxito de la IA empresarial. Una hoja de ruta estratégica debe abordar:',
'insights.fromDataToDecisions.body.roadmap.item1': 'Modernización de la arquitectura de datos',
'insights.fromDataToDecisions.body.roadmap.item2': 'Interoperabilidad del sistema',
'insights.fromDataToDecisions.body.roadmap.item3': 'Marcos de gestión de riesgos y gobernanza',
'insights.fromDataToDecisions.body.roadmap.item4': 'Alineación operativa',
'insights.fromDataToDecisions.body.roadmap.item5': 'Desarrollo de talento y capacidades',
'insights.fromDataToDecisions.body.roadmap.item6': 'Procesos de innovación escalables',
'insights.fromDataToDecisions.body.roadmap.p2': 'Las organizaciones exitosas equilibran las victorias rápidas tempranas con la planificación arquitectónica a largo plazo. El despliegue de la IA debe ser gradual, gobernado y alineado con objetivos de negocio medibles.',

// --- Section 6 ---
'insights.fromDataToDecisions.body.trends.title': '6. Tendencias de IA empresarial que marcan el 2026',
'insights.fromDataToDecisions.body.trends.p1': 'Varias tendencias están acelerando la adopción de la IA empresarial:',
'insights.fromDataToDecisions.body.trends.item1': 'Modernización de la nube y plataformas de datos escalables',
'insights.fromDataToDecisions.body.trends.item2': 'Herramientas de IA democratizadas para usuarios de negocios',
'insights.fromDataToDecisions.body.trends.item3': 'Sistemas de IA multimodales (texto, imagen, audio, video)',
'insights.fromDataToDecisions.body.trends.item4': 'Modelos operativos integrados de datos e IA',
'insights.fromDataToDecisions.body.trends.item5': 'Marcos de referencia para la medición de madurez',
'insights.fromDataToDecisions.body.trends.p2': 'Las organizaciones miden cada vez más el progreso de la IA frente a estándares de gobernanza y puntos de referencia de rendimiento operativo, en lugar de solo por el volumen de experimentación.',

// --- Section 7 ---
'insights.fromDataToDecisions.body.risks.title': '7. Riesgos a gestionar',
'insights.fromDataToDecisions.body.risks.p1': 'La IA empresarial introduce riesgos medibles. Los desafíos comunes incluyen:',
'insights.fromDataToDecisions.body.risks.item1': 'Sesgo del modelo causado por la mala calidad de los datos',
'insights.fromDataToDecisions.body.risks.item2': 'Barreras de integración con sistemas heredados',
'insights.fromDataToDecisions.body.risks.item3': 'Exposición en términos de cumplimiento y gobernanza',
'insights.fromDataToDecisions.body.risks.item4': 'Fracasos en el escalado tras pilotos exitosos',
'insights.fromDataToDecisions.body.risks.item5': 'Escasez de talento en IA',
'insights.fromDataToDecisions.body.risks.p2': 'Mitigar estos riesgos requiere un monitoreo proactivo, mecanismos de IA explicable y marcos de supervisión estructurados.',

// --- Conclusion ---
'insights.fromDataToDecisions.body.conclusion.title': '8. Conclusión',
'insights.fromDataToDecisions.body.conclusion.p1': 'La IA lista para la empresa en 2026 no es opcional. Se está volviendo fundamental para la competitividad operativa.',
'insights.fromDataToDecisions.body.conclusion.p2': 'Las organizaciones que tienen éxito:',
'insights.fromDataToDecisions.body.conclusion.item1': 'Construyen sobre cimientos de datos gobernados y de alta calidad',
'insights.fromDataToDecisions.body.conclusion.item2': 'Adoptan estrategias de crecimiento impulsadas por la madurez',
'insights.fromDataToDecisions.body.conclusion.item3': 'Alinean las iniciativas de IA con objetivos comerciales medibles',
'insights.fromDataToDecisions.body.conclusion.item4': 'Modernizan la infraestructura antes de escalar la automatización',
'insights.fromDataToDecisions.body.conclusion.item5': 'Fomentan una cultura de mejora continua',
'insights.fromDataToDecisions.body.conclusion.p3': 'La IA no es una iniciativa separada. Es un ecosistema interconectado integrado en las operaciones de la empresa.',
'insights.fromDataToDecisions.body.conclusion.p4': 'Comience de forma deliberada. Construya cimientos sólidos. Escale con propósito.',
'insights.fromDataToDecisions.body.conclusion.p5': 'El objetivo no es simplemente desplegar la IA. El objetivo es construir sistemas gobernados que conviertan los datos en decisiones confiables de nivel empresarial.',

// --- Key Takeaways ---
'insights.fromDataToDecisions.body.takeaways.title': 'Conclusiones Clave',
'insights.fromDataToDecisions.body.takeaways.item1': 'La IA empresarial requiere infraestructura, no experimentación',
'insights.fromDataToDecisions.body.takeaways.item2': 'La preparación de los datos determina la confiabilidad de las decisiones',
'insights.fromDataToDecisions.body.takeaways.item3': 'Los modelos de madurez guían el escalado estructurado de la IA',
'insights.fromDataToDecisions.body.takeaways.item4': 'La gobernanza y la seguridad deben integrarse desde el principio',
'insights.fromDataToDecisions.body.takeaways.item5': 'Los ecosistemas de IA deben alinearse con resultados de negocio medibles',

// --- Sidebar ---
'insights.fromDataToDecisions.sidebar.tocTitle': 'En este artículo',
'insights.fromDataToDecisions.sidebar.toc.item1': '1. Qué es la IA lista para la empresa',
'insights.fromDataToDecisions.sidebar.toc.item2': '2. Por qué la infraestructura',
'insights.fromDataToDecisions.sidebar.toc.item3': '3. Cuatro niveles de madurez de la IA',
'insights.fromDataToDecisions.sidebar.toc.item4': '4. Datos listos para la IA',
'insights.fromDataToDecisions.sidebar.toc.item5': '5. Hoja de ruta estratégica de IA',
'insights.fromDataToDecisions.sidebar.toc.item6': '6. Tendencias de IA en 2026',
'insights.fromDataToDecisions.sidebar.toc.item7': '7. Riesgos a gestionar',
'insights.fromDataToDecisions.sidebar.toc.item8': '8. Conclusión',

'insights.fromDataToDecisions.sidebar.shareTitle': 'Compartir este artículo',
'insights.fromDataToDecisions.sidebar.share.linkedin': 'Compartir en LinkedIn',
'insights.fromDataToDecisions.sidebar.share.twitter': 'Compartir en Twitter',
'insights.fromDataToDecisions.sidebar.share.facebook': 'Compartir en Facebook',
'insights.fromDataToDecisions.sidebar.share.copy': 'Copiar enlace',
'insights.fromDataToDecisions.sidebar.copyFeedback': '¡Enlace copiado!',


// ========================================
// INSIGHTS ARTICLE
// Why AI Strategy Fails Without Strong IT Foundations
// ========================================

// --- Hero ---
'insights.whyAIStrategyFails.hero.image.alt': 'Fondo de protección de seguros',
'insights.whyAIStrategyFails.hero.category': 'Estrategia de IA y Arquitectura de TI',
'insights.whyAIStrategyFails.hero.date': '23 de febrero de 2026',
'insights.whyAIStrategyFails.hero.title': 'Por qué la estrategia de IA falla sin cimientos sólidos de TI',
'insights.whyAIStrategyFails.hero.excerpt': 'La IA falla cuando se construye sobre cimientos de TI débiles. Una infraestructura escalable y datos gobernados son esenciales para obtener resultados sostenibles.',

// --- Body Intro ---
'insights.whyAIStrategyFails.body.intro.p1': 'La inteligencia artificial ya no es solo una prueba. Las empresas en muchos campos están gastando mucho dinero en proyectos de IA, desde analítica predictiva hasta automatización generativa. Pero incluso con mayores fondos y apoyo de los ejecutivos, muchos proyectos de IA dejan de funcionar, no hacen lo que se supone que deben hacer o fallan por completo.',
'insights.whyAIStrategyFails.body.intro.p2': 'La razón no son los malos algoritmos.',
'insights.whyAIStrategyFails.body.intro.p3': 'Los fundamentos de TI son deficientes.',

// --- Section 1 ---
'insights.whyAIStrategyFails.body.notSimple.title': '1. La IA no es una solución simple',
'insights.whyAIStrategyFails.body.notSimple.p1': 'Las empresas suelen ver la IA como un complemento para su software, algo que se puede añadir a los sistemas existentes sin realizar grandes cambios. La IA necesita mucha infraestructura para funcionar. Necesita una arquitectura escalable, canales de datos limpios, entornos seguros y flujos de trabajo para la integración continua.',
'insights.whyAIStrategyFails.body.notSimple.p2': 'La IA se vuelve poco confiable, costosa y difícil de escalar sin cimientos de TI actuales.',
'insights.whyAIStrategyFails.body.notSimple.p3': 'Antes de utilizar modelos avanzados, las empresas deben comprobar si su infraestructura puede gestionar bien las cargas de trabajo de IA.',

// --- Section 2 ---
'insights.whyAIStrategyFails.body.legacy.title': '2. Los sistemas antiguos causan problemas estructurales',
'insights.whyAIStrategyFails.body.legacy.p1': 'Muchas empresas siguen utilizando estructuras monolíticas y bases de datos fragmentadas. Estos sistemas nunca fueron diseñados para realizar analítica en tiempo real, procesos de aprendizaje automático o procesar grandes cantidades de datos.',
'insights.whyAIStrategyFails.body.legacy.p2': 'Cuando se añaden herramientas de IA a sistemas antiguos, suelen ocurrir ciertos problemas:',
'insights.whyAIStrategyFails.body.legacy.item1': 'Los silos de datos hacen imposible entrenar un modelo único.',
'insights.whyAIStrategyFails.body.legacy.item2': 'Los sistemas lentos dificultan la obtención de información.',
'insights.whyAIStrategyFails.body.legacy.item3': 'La automatización se ve bloqueada por procesos manuales.',
'insights.whyAIStrategyFails.body.legacy.item4': 'Los costes de integración crecen inesperadamente.',
'insights.whyAIStrategyFails.body.legacy.p3': 'Los sistemas nativos de la nube, impulsados por API y escalables son necesarios para la IA moderna. Los proyectos de IA tienen dificultades para pasar de la etapa de prueba de concepto sin modernización.',
'insights.whyAIStrategyFails.body.legacy.image.alt': 'Por qué la estrategia de IA falla sin cimientos sólidos de TI',

// --- Section 3 ---
'insights.whyAIStrategyFails.body.dataQuality.title': '3. La calidad de los datos afecta al funcionamiento de la IA.',
'insights.whyAIStrategyFails.body.dataQuality.p1': 'Los sistemas de IA solo pueden funcionar tan bien como los datos que utilizan. Una mala gobernanza de datos, formatos inconsistentes, información faltante y registros duplicados pueden hacer que el rendimiento sea muy malo.',
'insights.whyAIStrategyFails.body.dataQuality.p2': 'Las empresas a menudo no se dan cuenta de cuánto trabajo requiere:',
'insights.whyAIStrategyFails.body.dataQuality.item1': 'Unificar las fuentes de datos',
'insights.whyAIStrategyFails.body.dataQuality.item2': 'Asegurarse de que sus canales de datos funcionen.',
'insights.whyAIStrategyFails.body.dataQuality.item3': 'Establecer marcos para la validación de datos',
'insights.whyAIStrategyFails.body.dataQuality.item4': 'Asegurarse de seguir las normas',
'insights.whyAIStrategyFails.body.dataQuality.p3': 'Los cimientos sólidos de TI crean arquitecturas de datos centralizadas y estructuras de gobernanza que hacen que la IA sea segura y confiable.',

// --- Section 4 ---
'insights.whyAIStrategyFails.body.scalability.title': '4. No asumir que la escalabilidad es una necesidad',
'insights.whyAIStrategyFails.body.scalability.p1': 'Muchos pilotos de IA han mostrado un buen rendimiento inicial. Pero cuando las empresas intentan utilizar estas soluciones en toda la compañía, empiezan a ver problemas con su infraestructura.',
'insights.whyAIStrategyFails.body.scalability.p2': 'Las limitaciones en computación, almacenamiento y los problemas de rendimiento se vuelven claros de inmediato.',
'insights.whyAIStrategyFails.body.scalability.p3': 'Amazon Web Services, Microsoft Azure y Google Cloud son ejemplos de plataformas nativas de la nube que permiten el escalado elástico. Sin embargo, esto solo funciona si los sistemas están construidos para aprovecharse de ellos.',
'insights.whyAIStrategyFails.body.scalability.p4': 'Diseñar para el escalado desde el principio es importante para que la IA funcione.',

// --- Section 5 ---
'insights.whyAIStrategyFails.body.security.title': '5. No se olvide de la seguridad y la gobernanza',
'insights.whyAIStrategyFails.body.security.p1': 'La IA añade nuevos niveles de riesgo, como preocupaciones sobre la privacidad de los datos, sesgos en los modelos, exposición a regulaciones y puntos débiles en ciberseguridad.',
'insights.whyAIStrategyFails.body.security.p2': 'Las empresas que no tienen una buena gobernanza de TI arriesgan fallos de cumplimiento y daños a su reputación.',
'insights.whyAIStrategyFails.body.security.p3': 'Una infraestructura sólida debe tener:',
'insights.whyAIStrategyFails.body.security.item1': 'Gestión de identidades y accesos',
'insights.whyAIStrategyFails.body.security.item2': 'Protocolos de cifrado',
'insights.whyAIStrategyFails.body.security.item3': 'Trazas de auditoría',
'insights.whyAIStrategyFails.body.security.item4': 'Sistemas para el monitoreo de modelos',
'insights.whyAIStrategyFails.body.security.p4': 'Una hoja de ruta de IA planificada debe funcionar con los marcos de seguridad de la empresa, no contra ellos.',

// --- Section 6 ---
'insights.whyAIStrategyFails.body.itFirst.title': '6. La estrategia de TI es lo primero en la estrategia de IA',
'insights.whyAIStrategyFails.body.itFirst.p1': 'Las empresas que tienen éxito con la IA la utilizan de diversas maneras. Primero, invierten dinero en:',
'insights.whyAIStrategyFails.body.itFirst.item1': 'Modernización de la nube',
'insights.whyAIStrategyFails.body.itFirst.item2': 'Automatización y DevOps',
'insights.whyAIStrategyFails.body.itFirst.item3': 'Ingeniería de datos',
'insights.whyAIStrategyFails.body.itFirst.item4': 'Interoperabilidad de sistemas',
'insights.whyAIStrategyFails.body.itFirst.p2': 'Ven la IA como una herramienta que se puede utilizar sobre una infraestructura digital robusta, no como una forma de acelerar la innovación.',
'insights.whyAIStrategyFails.body.itFirst.p3': 'En Synexum Labs pensamos en la estrategia de IA como una extensión de la arquitectura de TI. Antes de poner en uso sistemas inteligentes, nos aseguramos de que las empresas tengan las estructuras adecuadas para soportarlos a lo largo del tiempo.',
'insights.whyAIStrategyFails.body.itFirst.p4': 'La IA no falla porque no quiera funcionar.',
'insights.whyAIStrategyFails.body.itFirst.p5': 'Falla cuando la base que hay debajo no es lo suficientemente fuerte para sostenerla.',

// --- Key Takeaways ---
'insights.whyAIStrategyFails.body.takeaways.title': 'Conclusiones clave',
'insights.whyAIStrategyFails.body.takeaways.item1': 'Las iniciativas de IA fallan principalmente debido a una infraestructura de TI débil',
'insights.whyAIStrategyFails.body.takeaways.item2': 'Los sistemas heredados limitan la escalabilidad y la integración',
'insights.whyAIStrategyFails.body.takeaways.item3': 'La gobernanza de datos es crítica para la confiabilidad de la IA',
'insights.whyAIStrategyFails.body.takeaways.item4': 'La seguridad y el cumplimiento deben integrarse desde el principio',
'insights.whyAIStrategyFails.body.takeaways.item5': 'La arquitectura de TI moderna debe preceder al despliegue de la IA',

// --- Conclusion ---
'insights.whyAIStrategyFails.body.conclusion.title': 'Conclusión',
'insights.whyAIStrategyFails.body.conclusion.p1': 'La inteligencia artificial es poderosa, pero no es autosuficiente. Una transformación de IA sostenible requiere una infraestructura moderna, entornos de datos gobernados y una arquitectura escalable.',
'insights.whyAIStrategyFails.body.conclusion.p2': 'Las organizaciones que priorizan la modernización de TI antes del despliegue de IA se posicionan para una confiabilidad operativa a largo plazo y un impacto medible.',
'insights.whyAIStrategyFails.body.conclusion.p3': 'Sin cimientos sólidos, incluso la estrategia de IA más avanzada tendrá dificultades para ofrecer valor empresarial.',

// --- Sidebar ---
'insights.whyAIStrategyFails.sidebar.tocTitle': 'En este artículo',
'insights.whyAIStrategyFails.sidebar.toc.item1': '1. La IA no es un simple complemento',
'insights.whyAIStrategyFails.sidebar.toc.item2': '2. Limitaciones de sistemas heredados',
'insights.whyAIStrategyFails.sidebar.toc.item3': '3. Datos y gobernanza',
'insights.whyAIStrategyFails.sidebar.toc.item4': '4. Requisitos de escalabilidad',
'insights.whyAIStrategyFails.sidebar.toc.item5': '5. Seguridad y gobernanza',
'insights.whyAIStrategyFails.sidebar.toc.item6': '6. TI antes que IA',
'insights.whyAIStrategyFails.sidebar.toc.item7': '7. Conclusión',

'insights.whyAIStrategyFails.sidebar.shareTitle': 'Compartir este artículo',
'insights.whyAIStrategyFails.sidebar.share.linkedin': 'Compartir en LinkedIn',
'insights.whyAIStrategyFails.sidebar.share.twitter': 'Compartir en Twitter',
'insights.whyAIStrategyFails.sidebar.share.facebook': 'Compartir en Facebook',
'insights.whyAIStrategyFails.sidebar.share.copy': 'Copiar enlace',
'insights.whyAIStrategyFails.sidebar.copyFeedback': '¡Enlace copiado!',


    },
};

/* ---------------- REVERSE LOOKUP ---------------- */

let reverseTranslations = {};

function buildReverseTranslations() {
    reverseTranslations = {};
    if (!translations.en) return;

    Object.keys(translations.en).forEach(key => {
        const val = translations.en[key];
        if (typeof val === 'string') {
            reverseTranslations[val.trim()] = key;
        }
    });
}
buildReverseTranslations();

/* ---------------- LANGUAGE STATE ---------------- */

let currentLanguage = localStorage.getItem('trevoxa-lang') || 'en';

/* ---------------- SET LANGUAGE ---------------- */

function setLanguage(lang) {
    currentLanguage = lang;
    localStorage.setItem('trevoxa-lang', lang);
    document.documentElement.lang = lang;
    applyTranslations();
    updateLanguageButtons();
    updateLanguageLabel(lang);
}


function updateLanguageLabel(lang) {
    const map = {
        en: "English",
        fr: "Français",
        es: "Español"
    };

    const label = document.getElementById("currentLangLabel");
    if (!label) return;

    label.textContent = map[lang] || "English";
    label.dataset.lang = lang; // lock state
}


/* ---------------- APPLY TRANSLATIONS ---------------- */

function applyTranslations() {

    /* data-translate attributes */
    document.querySelectorAll('[data-translate]').forEach(el => {
        const key = el.getAttribute('data-translate');
        const value = translations[currentLanguage]?.[key];
        if (!value) return;

        if (el.childNodes.length) {
            el.childNodes.forEach(node => {
                if (node.nodeType === Node.TEXT_NODE && node.nodeValue.trim()) {
                    node.nodeValue = value;
                }
            });
        } else {
            el.textContent = value;
        }
    });

    /* auto text translation */
    function walk(node) {
        if (node.nodeType === Node.TEXT_NODE) {
if (
    node.parentElement &&
    node.parentElement.closest(
        '[data-translate], [data-no-translate], #currentLangLabel'
    )
) return;

            if (!node.__originalText) node.__originalText = node.nodeValue;

            const original = node.__originalText;
            const trimmed = original.trim();
            if (!trimmed) return;

            const key = reverseTranslations[trimmed];
            if (!key) {
                node.nodeValue = original;
                return;
            }

            const translated = translations[currentLanguage]?.[key] || trimmed;
            node.nodeValue = original.replace(trimmed, translated);
            return;
        }

        if (['SCRIPT', 'STYLE', 'NOSCRIPT', 'TEXTAREA', 'SVG'].includes(node.nodeName)) return;
        node.childNodes.forEach(walk);
    }

    walk(document.body);

    /* placeholders */
    document.querySelectorAll('[data-translate-placeholder]').forEach(el => {
        const key = el.getAttribute('data-translate-placeholder');
        const value = translations[currentLanguage]?.[key];
        if (value) el.placeholder = value;
    });
}

/* ---------------- UPDATE TOGGLE UI ---------------- */

function updateLanguageButtons() {
    const ids = ['langEN', 'langFR', 'langES', 'mobileLangEN', 'mobileLangFR', 'mobileLangES'];

    ids.forEach(id => {
        const el = document.getElementById(id);
        if (!el) return;

        if (id.toLowerCase().includes('en')) {
            el.classList.toggle('active', currentLanguage === 'en');
        }
        if (id.toLowerCase().includes('fr')) {
            el.classList.toggle('active', currentLanguage === 'fr');
        }
        if (id.toLowerCase().includes('es')) {
            el.classList.toggle('active', currentLanguage === 'es');
        }
    });
}

/* ---------------- INITIAL LOAD ---------------- */
document.addEventListener('DOMContentLoaded', function () {
    requestAnimationFrame(() => {
        setLanguage(currentLanguage);
        updateLanguageButtons();
        updateLanguageLabel(currentLanguage);
    });
});
/* ---------------- AUTO RE-TRANSLATE ---------------- */

const observer = new MutationObserver(() => {
    applyTranslations();
    updateLanguageButtons(); // 🔥 THIS WAS MISSING
});
observer.observe(document.body, { childList: true, subtree: true });

/* ---------------- GLOBAL ACCESS ---------------- */

window.setLanguage = setLanguage;
window.translatePage = () => {
    applyTranslations();
    updateLanguageButtons();
};
</script>