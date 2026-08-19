## **System Prompt for your AI Web Agent**

You are an expert Frontend Architect and UI/UX Senior Designer specializing in clean, high-conversion B2B platforms. Your task is to redesign the website for Grace International (gracetmc.com), an elite, ISO 9001:2015 certified overseas manpower consultancy with over 25 years of experience matching top-tier talent from India with corporate clients in the Gulf and Middle East.

CRITICAL DISAMBIGUATION NOTICE:  
The legacy data contains e-commerce scraping noise (references to "barrier repair cream", "power tools", and "shopping carts"). You must completely IGNORE all e-commerce, consumer retail, and product shopping references. The business is strictly a Corporate B2B Human Resources & Recruitment Consultancy.

DESIGN ARCHITECTURE RULES:  
1\. Palette: Light, premium, executive layout. Use pure white (\#FFFFFF), deep corporate navy (\#0F2942) for authority text, clean slate/cool grey (\#F8FAFC) for backgrounds, and a sharp vibrant blue (\#2563EB) as a functional accent color.  
2\. Typography: Clean, highly-readable geometric sans-serif (e.g., Inter, Plus Jakarta Sans).  
3\. Layout Structure: Drastically minimize multi-level navigation. Opt for an elegant, single-tier master header. Break dense blocks of copy into punchy, value-driven micro-layouts with substantial white space.  
4\. Professional Polish: Utilize card components with soft shadows, micro-interactions, subtle borders, and vivid status elements to indicate a tech-driven, state-of-the-art agency.

## ---

**Modern Light Business Concept Redesign**

\<\!DOCTYPE html\>  
\<html lang="en"\>  
\<head\>  
  \<meta charset="UTF-8"\>  
  \<meta name="viewport" content="width=device-width, initial-scale=1.0"\>  
  \<title\>Grace International | Elite Global Workforce Solutions\</title\>  
  \<script src="https://tailwindcss.com"\>\</script\>  
  \<link rel="preconnect" href="https://googleapis.com"\>  
  \<link rel="preconnect" href="https://gstatic.com" crossorigin\>  
  \<link href="https://googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700\&display=swap" rel="stylesheet"\>  
  \<style\>  
    body { font-family: 'Plus Jakarta Sans', sans-serif; }  
  \</style\>  
\</head\>  
\<body class="bg-\[\#F8FAFC\] text-\[\#0F2942\] antialiased"\>

  *\<\!-- TOP DECK: Global Trust Indicator \--\>*  
  \<div class="bg-\[\#0F2942\] text-white/80 text-xs py-2 px-6 flex justify-between items-center border-b border-white/10"\>  
    \<div class="flex items-center gap-4"\>  
      \<span\>Govt. of India Approved Reg: \<strong\>B-0657/MUM/PER/1000\+/3/8187/2001\</strong\>\</span\>  
      \<span class="w-1.5 h-1.5 rounded-full bg-emerald-400 animate-pulse"\>\</span\>  
      \<span class="text-white"\>ISO 9001:2015 Certified\</span\>  
    \</div\>  
    \<div class="hidden md:flex gap-4"\>  
      \<a href="mailto:info@gracetmc.com" class="hover:text-white transition"\>info@gracetmc.com\</a\>  
      \<span\>+91 22 49741100\</span\>  
    \</div\>  
  \</div\>

  *\<\!-- NAVIGATION HEADER \--\>*  
  \<header class="sticky top-0 z-50 bg-white/80 backdrop-blur-md border-b border-slate-100 px-6 py-4 flex justify-between items-center"\>  
    \<div class="flex items-center gap-3"\>  
      \<div class="w-10 h-10 bg-blue-600 rounded-xl flex items-center justify-center font-bold text-white text-xl shadow-lg shadow-blue-500/20"\>G\</div\>  
      \<div\>  
        \<span class="text-lg font-bold tracking-tight block leading-none"\>GRACE\</span\>  
        \<span class="text-\[10px\] uppercase tracking-widest text-slate-400 font-semibold"\>International\</span\>  
      \</div\>  
    \</div\>  
      
    \<nav class="hidden lg:flex items-center gap-8 font-medium text-sm text-slate-600"\>  
      \<a href="\#about" class="hover:text-blue-600 transition"\>About Agency\</a\>  
      \<a href="\#sectors" class="hover:text-blue-600 transition"\>Sectors\</a\>  
      \<a href="\#guarantee" class="hover:text-blue-600 transition"\>90\-Day Guarantee\</a\>  
      \<a href="\#contact" class="hover:text-blue-600 transition"\>Contact\</a\>  
    \</nav\>

    \<div class="flex items-center gap-3"\>  
      \<a href="\#contact" class="bg-blue-600 hover:bg-blue-700 text-white text-sm font-semibold px-5 py-2.5 rounded-xl transition shadow-md shadow-blue-600/10"\>  
        Hire Talent  
      \</a\>  
    \</div\>  
  \</header\>

  *\<\!-- HERO SECTION \--\>*  
  \<section class="relative pt-20 pb-24 px-6 max-w-7xl mx-auto grid lg:grid-cols-12 gap-12 items-center"\>  
    \<div class="lg:col-span-7 space-y-6"\>  
      \<div class="inline-flex items-center gap-2 bg-blue-50 text-blue-700 text-xs font-semibold px-3 py-1.5 rounded-full"\>  
        ✨ 25 Years of Global Recruitment Excellence  
      \</div\>  
      \<h1 class="text-4xl sm:text-5xl lg:text-6xl font-bold tracking-tight leading-\[1.1\] text-slate-900"\>  
        Connecting the Gulf & Middle East with India's \<span class="text-blue-600"\>Premier Talent\</span\>.  
      \</h1\>  
      \<p class="text-lg text-slate-600 max-w-xl leading-relaxed"\>  
        Fully computerized, data-backed technical recruitment solutions. Over 50,000 verified candidates ready to scale your enterprise operations seamlessly.  
      \</p\>  
        
      *\<\!-- Live Metrics Hub \--\>*  
      \<div class="pt-6 grid grid-cols-3 gap-4 border-t border-slate-200"\>  
        \<div\>  
          \<span class="block text-3xl font-bold text-slate-900"\>50K+\</span\>  
          \<span class="text-xs text-slate-500 font-medium uppercase tracking-wider"\>Candidate Database\</span\>  
        \</div\>  
        \<div\>  
          \<span class="block text-3xl font-bold text-slate-900"\>100\+\</span\>  
          \<span class="text-xs text-slate-500 font-medium uppercase tracking-wider"\>MNC Clients served\</span\>  
        \</div\>  
        \<div\>  
          \<span class="block text-3xl font-bold text-slate-900"\>90 Days\</span\>  
          \<span class="text-xs text-slate-500 font-medium uppercase tracking-wider"\>Risk Indemnity\</span\>  
        \</div\>  
      \</div\>  
    \</div\>

    *\<\!-- Visual Tech Anchor Card \--\>*  
    \<div class="lg:col-span-5 relative"\>  
      \<div class="absolute inset-0 bg-blue-400 rounded-3xl filter blur-3xl opacity-10"\>\</div\>  
      \<div class="relative bg-white border border-slate-100 p-8 rounded-3xl shadow-xl shadow-slate-200/50 space-y-6"\>  
        \<div class="flex justify-between items-center"\>  
          \<span class="text-xs font-bold text-slate-400 uppercase tracking-widest"\>Live Engine Status\</span\>  
          \<span class="bg-emerald-50 text-emerald-700 text-\[11px\] font-semibold px-2.5 py-1 rounded-full flex items-center gap-1.5"\>  
            \<span class="w-1.5 h-1.5 rounded-full bg-emerald-500"\>\</span\> Active Matching  
          \</span\>  
        \</div\>  
        \<div class="space-y-4"\>  
          \<div class="p-4 bg-slate-50 rounded-2xl flex items-center justify-between border border-slate-100"\>  
            \<div\>  
              \<p class="text-sm font-semibold text-slate-800"\>In-House Specialty Center\</p\>  
              \<p class="text-xs text-slate-500"\>Rigorous engineering & trade evaluations\</p\>  
            \</div\>  
            \<span class="text-xs font-bold text-blue-600 bg-blue-50 px-2 py-1 rounded-lg"\>Verified\</span\>  
          \</div\>  
          \<div class="p-4 bg-slate-50 rounded-2xl flex items-center justify-between border border-slate-100"\>  
            \<div\>  
              \<p class="text-sm font-semibold text-slate-800"\>Automated Pipeline Matched\</p\>  
              \<p class="text-xs text-slate-500"\>Accelerated deployment to Middle East/Gulf\</p\>  
            \</div\>  
            \<span class="text-xs font-bold text-blue-600 bg-blue-50 px-2 py-1 rounded-lg"\>Smart\</span\>  
          \</div\>  
        \</div\>  
        \<a href="\#contact" class="block text-center w-full bg-slate-900 hover:bg-slate-800 text-white text-sm font-semibold py-3.5 rounded-2xl transition"\>  
          Initiate Executive Search  
        \</a\>  
      \</div\>  
    \</div\>  
  \</section\>

  *\<\!-- SOLID VALUE PROPOSITION (GUARANTEE) \--\>*  
  \<section id="guarantee" class="bg-white border-y border-slate-100 py-16 px-6"\>  
    \<div class="max-w-5xl mx-auto bg-slate-900 text-white rounded-3xl p-8 md:p-12 relative overflow-hidden shadow-2xl"\>  
      \<div class="absolute \-right-16 \-top-16 w-48 h-48 bg-blue-600/20 rounded-full blur-2xl"\>\</div\>  
      \<div class="max-w-2xl space-y-4"\>  
        \<span class="text-xs font-bold tracking-widest text-blue-400 uppercase"\>Unprecedented Accountability\</span\>  
        \<h2 class="text-2xl md:text-3xl font-bold"\>The Grace 90\-Day Probationary Guarantee\</h2\>  
        \<p class="text-white/70 text-sm md:text-base leading-relaxed"\>  
          We guarantee the specific fitness and performance of every selected candidate. If a candidate is determined to be unsuitable during the first 90 days of their probationary deployment, we will repatriate them entirely at our own expense.  
        \</p\>  
      \</div\>  
    \</div\>  
  \</section\>

  *\<\!-- CORE SECTORS OF RECRUITMENT \--\>*  
  \<section id="sectors" class="py-20 px-6 max-w-7xl mx-auto space-y-12"\>  
    \<div class="text-center max-w-xl mx-auto space-y-3"\>  
      \<h2 class="text-3xl font-bold tracking-tight text-slate-900"\>Industry Specializations\</h2\>  
      \<p class="text-slate-500 text-sm"\>Providing flexible, highly customized, and cost-effective hiring frameworks across key global domains.\</p\>  
    \</div\>  
      
    \<div class="grid sm:grid-cols-2 lg:grid-cols-4 gap-6"\>  
      \<div class="bg-white border border-slate-100 p-6 rounded-2xl shadow-sm hover:shadow-md transition"\>  
        \<div class="w-10 h-10 bg-blue-50 rounded-xl flex items-center justify-center text-blue-600 mb-4 font-bold"\>🏗️\</div\>  
        \<h3 class="font-semibold text-slate-900 mb-1"\>Heavy Industrial\</h3\>  
        \<p class="text-xs text-slate-500"\>Core manufacturing, infrastructure development, and plant operations personnel.\</p\>  
      \</div\>  
      \<div class="bg-white border border-slate-100 p-6 rounded-2xl shadow-sm hover:shadow-md transition"\>  
        \<div class="w-10 h-10 bg-blue-50 rounded-xl flex items-center justify-center text-blue-600 mb-4 font-bold"\>⚡\</div\>  
        \<h3 class="font-semibold text-slate-900 mb-1"\>Engineering & Infrastructure\</h3\>  
        \<p class="text-xs text-slate-500"\>Certified technicians, project operators, and civil development teams.\</p\>  
      \</div\>  
      \<div class="bg-white border border-slate-100 p-6 rounded-2xl shadow-sm hover:shadow-md transition"\>  
        \<div class="w-10 h-10 bg-blue-50 rounded-xl flex items-center justify-center text-blue-600 mb-4 font-bold"\>🌍\</div\>  
        \<h3 class="font-semibold text-slate-900 mb-1"\>Multinational Cross-Border\</h3\>  
        \<p class="text-xs text-slate-500"\>Highly customized, scalable deployments optimized for regulatory compliance.\</p\>  
      \</div\>  
      \<div class="bg-white border border-slate-100 p-6 rounded-2xl shadow-sm hover:shadow-md transition"\>  
        \<div class="w-10 h-10 bg-blue-50 rounded-xl flex items-center justify-center text-blue-600 mb-4 font-bold"\>🛠️\</div\>  
        \<h3 class="font-semibold text-slate-900 mb-1"\>Skilled Trades\</h3\>  
        \<p class="text-xs text-slate-500"\>Rigorous, multi-tier verified skilled professionals for immediate output.\</p\>  
      \</div\>  
    \</div\>  
  \</section\>

  *\<\!-- RECRUITMENT HUB / CONTACT FORM \--\>*  
  \<section id="contact" class="bg-white border-t border-slate-100 py-20 px-6"\>  
    \<div class="max-w-7xl mx-auto grid lg:grid-cols-2 gap-12"\>  
      \<div class="space-y-6"\>  
        \<span class="text-xs font-bold text-blue-600 uppercase tracking-widest"\>Global Headquarters\</span\>  
        \<h2 class="text-3xl font-bold text-slate-900"\>Partner with Grace International Today\</h2\>  
        \<p class="text-slate-600 text-sm leading-relaxed"\>

Based in Mumbai, India’s primary business capital, our teams leverage high-efficiency digital screening workflows alongside physical testing infrastructure to identify optimal candidate matches rapidly.

Address:  
201, Antariksh Thakoor House, Makwana Road, Marol Andheri East, Mumbai \- 400059

Inquiries:

graceintl@gmail.com  
info@gracetmc.com

Telephone:  
\+91 22 20880378 / \+91 22 49741100

Corporate Requirement Intake  
Submit your current hiring mandates. Our evaluators will follow up within 12 business hours.

Submit Mandate

© 2026 Grace International Manpower Consultants. All Rights Reserved.  
ISO 9001:2015 Registered Agency • Government of India Registration Number: B-0657/MUM/PER/1000+/3/8187/2001

\*\*\*

\#\#\# Key Technical Improvements Made

\* \*\*Filtered Out Noise:\*\* Extracted and fully eliminated all legacy e-commerce text errors ("barrier repair cream", "power tools") to keep the site focused 100% on \*\*B2B Global Recruitment and Manpower Solutions\*\*.  
\* \*\*Modern Executive Theme:\*\* Implemented a balanced, light modern corporate theme using \*\*Tailwind CSS\*\*, heavy type contrast, and deep accent blues suited for enterprise relationships.  
\* \*\*Unified Regulatory Trust:\*\* Structured critical legal validation fields (ISO certification, Government of India license numbers) directly inside a high-visibility structural header banner.   
\* \*\*Optimized Intake Pipeline:\*\* Replaced the legacy e-commerce checkout loop with an actionable \*\*Corporate Intake Form\*\* designed to convert business visitors into operational clients.

To assist you further, please let me know:  
\* Would you like me to include an \*\*online candidate portal\*\* feature for job seekers to upload resumes?  
\* Do you want separate, dedicated layouts for \*\*Employers\*\* versus \*\*Candidates\*\*?  
\* Are there any specific \*\*social links\*\* or \*\*partner logos\*\* you would like integrated into the layout?  
