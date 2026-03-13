<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Class 10 Study Hub - Get all the study materials, notes, and solutions for Class 10 subjects including Math, Science, English, and Social Science.">
    <meta name="keywords" content="Class 10 notes, Class 10 solutions, Class 10 study materials, Class 10 syllabus, Class 10 resources, Class 10 Math, Class 10 Science, Class 10 English, Class 10 Social Science">
    <meta name="author" content="Class 10 Study Hub">
    <meta property="og:title" content="Class 10 Study Hub | Your Study Resource Destination">
    <meta property="og:description" content="Explore comprehensive Class 10 study materials and exam preparation resources for Math, Science, English, and Social Science.">
    <meta property="og:image" content="https://dj420-gif.github.io/Studymaster/logo.png">
    <meta property="og:url" content="https://dj420-gif.github.io/Studymaster/">
    <meta property="og:type" content="website">
    <meta name="robots" content="index, follow">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <link rel="canonical" href="https://dj420-gif.github.io/Studymaster/">
    <link rel="sitemap" type="application/xml" title="Sitemap" href="https://dj420-gif.github.io/Studymaster/sitemap.xml">
    <title>Class 10 Study Hub | Study Materials, Notes & Solutions</title>
    <link rel="stylesheet" href="styles.css">
    <!-- Breadcrumb JSON-LD -->
    <script type="application/ld+json">
    {
        "@context": "https://schema.org",
        "@type": "BreadcrumbList",
        "itemListElement": [
            {
                "@type": "ListItem",
                "position": 1,
                "name": "Home",
                "item": "https://dj420-gif.github.io/Studymaster/"
            },
            {
                "@type": "ListItem",
                "position": 2,
                "name": "Subjects",
                "item": "https://dj420-gif.github.io/Studymaster/#subjects"
            },
            {
                "@type": "ListItem",
                "position": 3,
                "name": "Resources",
                "item": "https://dj420-gif.github.io/Studymaster/resources.html"
            }
        ]
    }
    </script>
    <!-- FAQ JSON-LD -->
    <script type="application/ld+json">
    {
        "@context": "https://schema.org",
        "@type": "FAQPage",
        "mainEntity": [
            {
                "@type": "Question",
                "name": "What is Class 10 Study Hub?",
                "acceptedAnswer": {
                    "@type": "Answer",
                    "text": "Class 10 Study Hub is an educational resource offering notes, solutions, and study guides for Class 10 students."
                }
            },
            {
                "@type": "Question",
                "name": "Are study materials free on Class 10 Study Hub?",
                "acceptedAnswer": {
                    "@type": "Answer",
                    "text": "Yes, all study materials, notes, and resources are free for students."
                }
            }
        ]
    }
    </script>
    <!-- Google tag (gtag.js) -->
    <script async src="https://www.googletagmanager.com/gtag/js?id=G-SWPWBWH4BZ"></script>
    <script>
      window.dataLayer = window.dataLayer || [];
      function gtag(){dataLayer.push(arguments);}
      gtag('js', new Date());
      gtag('config', 'G-SWPWBWH4BZ');
    </script>
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Sora:wght@400;600;700;800&family=DM+Sans:ital,wght@0,300;0,400;0,500;1,400&display=swap" rel="stylesheet">
    <style>
        /* =========================================
           CSS VARIABLES & RESET
        ========================================= */
        :root {
            --bg: #f5f7ff;
            --surface: #ffffff;
            --surface-alt: #eef1ff;
            --primary: #4f46e5;
            --primary-dark: #3730a3;
            --primary-light: #818cf8;
            --accent: #f59e0b;
            --accent-dark: #d97706;
            --text: #1e1b4b;
            --text-muted: #6b7280;
            --text-light: #9ca3af;
            --border: rgba(79, 70, 229, 0.12);
            --shadow-sm: 0 2px 8px rgba(79,70,229,0.08);
            --shadow-md: 0 8px 24px rgba(79,70,229,0.12);
            --shadow-lg: 0 20px 48px rgba(79,70,229,0.16);
            --radius: 16px;
            --radius-sm: 10px;
            --transition: 0.3s cubic-bezier(0.4, 0, 0.2, 1);
            /* Subject colors */
            --math: #4f46e5;
            --science: #059669;
            --english: #db2777;
            --social: #d97706;
        }
        *, *::before, *::after {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        html {
            scroll-behavior: smooth;
        }
        body {
            font-family: 'DM Sans', sans-serif;
            background: var(--bg);
            color: var(--text);
            line-height: 1.65;
            overflow-x: hidden;
        }
        /* =========================================
           HEADER & NAVIGATION
        ========================================= */
        header {
            background: white;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 1px 0 rgba(79,70,229,0.1), var(--shadow-sm);
        }
        .header-inner {
            max-width: 1160px;
            margin: 0 auto;
            padding: 0 24px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            height: 68px;
            gap: 16px;
        }
        .site-logo {
            display: flex;
            align-items: center;
            gap: 10px;
            text-decoration: none;
            flex-shrink: 0;
        }
        .logo-icon {
            width: 38px;
            height: 38px;
            background: linear-gradient(135deg, var(--primary), var(--primary-light));
            border-radius: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 18px;
            flex-shrink: 0;
        }
        .site-logo h1 {
            font-family: 'Sora', sans-serif;
            font-size: 1.15rem;
            font-weight: 700;
            color: var(--text);
            line-height: 1.2;
        }
        .site-logo h1 span {
            color: var(--primary);
        }
        /* Desktop Nav */
        .nav-links {
            display: flex;
            align-items: center;
            list-style: none;
            gap: 4px;
        }
        .nav-links a {
            font-family: 'DM Sans', sans-serif;
            font-size: 0.9rem;
            font-weight: 500;
            color: var(--text-muted);
            text-decoration: none;
            padding: 8px 14px;
            border-radius: 8px;
            transition: var(--transition);
            white-space: nowrap;
        }
        .nav-links a:hover {
            color: var(--primary);
            background: var(--surface-alt);
        }
        .nav-cta {
            background: linear-gradient(135deg, var(--primary), var(--primary-dark)) !important;
            color: white !important;
            padding: 8px 18px !important;
            border-radius: 8px !important;
        }
        .nav-cta:hover {
            opacity: 0.9;
            background: linear-gradient(135deg, var(--primary), var(--primary-dark)) !important;
            transform: translateY(-1px);
        }
        /* Search */
        .search-wrapper {
            display: flex;
            align-items: center;
            background: var(--surface-alt);
            border: 1.5px solid var(--border);
            border-radius: 10px;
            overflow: hidden;
            transition: var(--transition);
            flex-shrink: 0;
        }
        .search-wrapper:focus-within {
            border-color: var(--primary-light);
            box-shadow: 0 0 0 3px rgba(79,70,229,0.1);
            background: white;
        }
        #search-bar {
            border: none;
            outline: none;
            background: transparent;
            padding: 9px 14px;
            font-family: 'DM Sans', sans-serif;
            font-size: 0.9rem;
            color: var(--text);
            width: 200px;
        }
        #search-bar::placeholder {
            color: var(--text-light);
        }
        #search-btn {
            border: none;
            background: transparent;
            padding: 9px 13px;
            cursor: pointer;
            font-size: 1rem;
            color: var(--primary);
            transition: var(--transition);
        }
        #search-btn:hover {
            background: rgba(79,70,229,0.08);
        }
        /* Hamburger */
        .hamburger {
            display: none;
            flex-direction: column;
            gap: 5px;
            cursor: pointer;
            padding: 6px;
            border-radius: 8px;
            transition: var(--transition);
            background: none;
            border: none;
            flex-shrink: 0;
        }
        .hamburger span {
            display: block;
            width: 22px;
            height: 2px;
            background: var(--text);
            border-radius: 2px;
            transition: var(--transition);
        }
        .hamburger.open span:nth-child(1) { transform: translateY(7px) rotate(45deg); }
        .hamburger.open span:nth-child(2) { opacity: 0; }
        .hamburger.open span:nth-child(3) { transform: translateY(-7px) rotate(-45deg); }
        /* Mobile nav drawer */
        .mobile-nav {
            display: none;
            flex-direction: column;
            background: white;
            border-top: 1px solid var(--border);
            padding: 12px 24px 16px;
            gap: 4px;
        }
        .mobile-nav.open {
            display: flex;
        }
        .mobile-nav a {
            font-family: 'DM Sans', sans-serif;
            font-size: 0.95rem;
            font-weight: 500;
            color: var(--text-muted);
            text-decoration: none;
            padding: 10px 14px;
            border-radius: 8px;
            transition: var(--transition);
        }
        .mobile-nav a:hover {
            color: var(--primary);
            background: var(--surface-alt);
        }
        .mobile-nav .nav-cta-mob {
            background: linear-gradient(135deg, var(--primary), var(--primary-dark));
            color: white !important;
            text-align: center;
            margin-top: 4px;
        }
        .mobile-search {
            display: flex;
            align-items: center;
            background: var(--surface-alt);
            border: 1.5px solid var(--border);
            border-radius: 10px;
            overflow: hidden;
            margin-top: 8px;
        }
        .mobile-search input {
            border: none;
            outline: none;
            background: transparent;
            padding: 9px 14px;
            font-size: 0.9rem;
            flex: 1;
            color: var(--text);
        }
        .mobile-search button {
            border: none;
            background: transparent;
            padding: 9px 13px;
            cursor: pointer;
            font-size: 1rem;
            color: var(--primary);
        }
        /* =========================================
           HERO SECTION
        ========================================= */
        .hero {
            background: linear-gradient(135deg, #312e81 0%, #4f46e5 50%, #7c3aed 100%);
            position: relative;
            overflow: hidden;
            padding: 72px 24px;
            text-align: center;
        }
        .hero::before {
            content: '';
            position: absolute;
            inset: 0;
            background-image:
                radial-gradient(circle at 20% 50%, rgba(255,255,255,0.06) 0%, transparent 50%),
                radial-gradient(circle at 80% 20%, rgba(245,158,11,0.15) 0%, transparent 50%),
                radial-gradient(circle at 60% 80%, rgba(255,255,255,0.04) 0%, transparent 40%);
        }
        .hero-shapes {
            position: absolute;
            inset: 0;
            pointer-events: none;
            overflow: hidden;
        }
        .shape {
            position: absolute;
            border-radius: 50%;
            opacity: 0.06;
            background: white;
        }
        .shape-1 { width: 300px; height: 300px; top: -80px; left: -80px; }
        .shape-2 { width: 200px; height: 200px; bottom: -60px; right: 10%; }
        .shape-3 { width: 120px; height: 120px; top: 30%; right: 5%; opacity: 0.04; }
        .hero-content {
            position: relative;
            z-index: 1;
            max-width: 700px;
            margin: 0 auto;
        }
        .hero-badge {
            display: inline-flex;
            align-items: center;
            gap: 6px;
            background: rgba(255,255,255,0.15);
            border: 1px solid rgba(255,255,255,0.25);
            color: white;
            font-size: 0.8rem;
            font-weight: 600;
            padding: 6px 14px;
            border-radius: 100px;
            margin-bottom: 20px;
            letter-spacing: 0.03em;
            text-transform: uppercase;
        }
        .hero h2 {
            font-family: 'Sora', sans-serif;
            font-size: clamp(2rem, 5vw, 3rem);
            font-weight: 800;
            color: white;
            line-height: 1.15;
            margin-bottom: 18px;
            letter-spacing: -0.02em;
        }
        .hero h2 .highlight {
            color: #fcd34d;
        }
        .hero p {
            font-size: 1.05rem;
            color: rgba(255,255,255,0.82);
            max-width: 560px;
            margin: 0 auto 32px;
            line-height: 1.7;
        }
        .hero-actions {
            display: flex;
            gap: 12px;
            justify-content: center;
            flex-wrap: wrap;
        }
        .btn-primary {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            background: #fcd34d;
            color: #1e1b4b;
            font-family: 'DM Sans', sans-serif;
            font-weight: 700;
            font-size: 0.95rem;
            padding: 13px 26px;
            border-radius: 10px;
            text-decoration: none;
            transition: var(--transition);
            box-shadow: 0 4px 16px rgba(252,211,77,0.4);
        }
        .btn-primary:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 24px rgba(252,211,77,0.5);
        }
        .btn-ghost {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            background: rgba(255,255,255,0.15);
            color: white;
            border: 1.5px solid rgba(255,255,255,0.35);
            font-family: 'DM Sans', sans-serif;
            font-weight: 600;
            font-size: 0.95rem;
            padding: 13px 26px;
            border-radius: 10px;
            text-decoration: none;
            transition: var(--transition);
        }
        .btn-ghost:hover {
            background: rgba(255,255,255,0.25);
            transform: translateY(-2px);
        }
        /* Stats Row */
        .stats-row {
            display: flex;
            justify-content: center;
            gap: 0;
            background: white;
            border-bottom: 1px solid var(--border);
        }
        .stat-item {
            flex: 1;
            max-width: 220px;
            text-align: center;
            padding: 18px 20px;
            border-right: 1px solid var(--border);
        }
        .stat-item:last-child {
            border-right: none;
        }
        .stat-num {
            font-family: 'Sora', sans-serif;
            font-size: 1.5rem;
            font-weight: 800;
            color: var(--primary);
            line-height: 1;
        }
        .stat-label {
            font-size: 0.78rem;
            color: var(--text-muted);
            margin-top: 3px;
            font-weight: 500;
        }
        /* =========================================
           SECTIONS GENERAL
        ========================================= */
        section {
            max-width: 1160px;
            margin: 0 auto;
            padding: 64px 24px;
        }
        .section-label {
            display: inline-flex;
            align-items: center;
            gap: 6px;
            font-size: 0.75rem;
            font-weight: 700;
            text-transform: uppercase;
            letter-spacing: 0.1em;
            color: var(--primary);
            background: rgba(79,70,229,0.08);
            padding: 5px 12px;
            border-radius: 100px;
            margin-bottom: 10px;
        }
        .section-heading {
            font-family: 'Sora', sans-serif;
            font-size: clamp(1.5rem, 3vw, 2rem);
            font-weight: 800;
            color: var(--text);
            margin-bottom: 8px;
            letter-spacing: -0.02em;
        }
        .section-sub {
            color: var(--text-muted);
            font-size: 1rem;
            margin-bottom: 40px;
            max-width: 520px;
        }
        /* =========================================
           HOW TO START SECTION
        ========================================= */
        #start-class-10 {
            background: var(--surface-alt);
            max-width: 100%;
            border-top: 1px solid var(--border);
            border-bottom: 1px solid var(--border);
        }
        #start-class-10 > .inner {
            max-width: 1160px;
            margin: 0 auto;
        }
        .steps-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 16px;
        }
        .step-card {
            background: white;
            border-radius: var(--radius);
            padding: 24px;
            border: 1.5px solid var(--border);
            position: relative;
            transition: var(--transition);
            overflow: hidden;
        }
        .step-card::before {
            content: '';
            position: absolute;
            inset: 0;
            background: linear-gradient(135deg, var(--primary), var(--primary-light));
            opacity: 0;
            transition: var(--transition);
        }
        .step-card:hover {
            transform: translateY(-4px);
            box-shadow: var(--shadow-md);
            border-color: var(--primary-light);
        }
       .step-num {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            width: 36px;
            height: 36px;
            background: linear-gradient(135deg, var(--primary), var(--primary-light));
            color: white;
            font-family: 'Sora', sans-serif;
            font-size: 0.9rem;
            font-weight: 700;
            border-radius: 10px;
            margin-bottom: 14px;
            flex-shrink: 0;
        }
        .step-card h3 {
            font-family: 'Sora', sans-serif;
            font-size: 0.95rem;
            font-weight: 700;
            color: var(--text);
            margin-bottom: 8px;
        }
        .step-card p {
            font-size: 0.87rem;
            color: var(--text-muted);
            line-height: 1.6;
        }
        /* =========================================
           SUBJECTS SECTION
        ========================================= */
        .subjects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, mi
