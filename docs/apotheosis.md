{
  "meta": {
    "id": "frontend-0-to-hero-curriculum",
    "title": "0-to-Hero Frontend Engineering Curriculum",
    "version": "2.0.0",
    "targetRole": "Frontend Engineer (NCR / Product / Full-Stack Frontend)",
    "defaultLanguage": "TypeScript",
    "supportedLanguages": ["TypeScript", "JavaScript"],
    "counts": {
      "syllabusModules": 8,
      "practiceTasks": 26,
      "interviewConcepts": 27,
      "projects": 5,
      "flagshipProjects": 3,
      "dsaCategories": 5,
      "dsaProblems": 50
    }
  },
  "userProgressDefaults": {
    "item": {
      "completed": false,
      "completedAt": null,
      "notes": ""
    },
    "dsaProblem": {
      "status": "todo",
      "completedAt": null,
      "attempts": 0,
      "solutionLanguage": "TypeScript",
      "notes": ""
    }
  },
  "syllabus": [
    {
      "id": "mod-1",
      "slug": "html5-modern-css-responsive-design",
      "order": 1,
      "title": "HTML5, Modern CSS & Responsive Design",
      "practice": [
        {
          "id": "mod-1-prac-1",
          "order": 1,
          "type": "practice",
          "text": "Build semantic layouts using <header>, <main>, <nav>, <article>, <section>, and accessible <form> controls with proper <label> associations.",
          "tags": ["html5", "semantics", "forms", "accessibility"]
        },
        {
          "id": "mod-1-prac-2",
          "order": 2,
          "type": "practice",
          "text": "Build complex 2D dashboards with CSS Grid and 1D alignment/navbars with Flexbox without hardcoding pixel widths.",
          "tags": ["css-grid", "flexbox", "layout"]
        },
        {
          "id": "mod-1-prac-3",
          "order": 3,
          "type": "practice",
          "text": "Implement mobile-first responsive breakpoints, fluid typography (clamp()), CSS custom properties (variables), and dark/light theme switching.",
          "tags": ["responsive", "clamp", "css-variables", "theming"]
        },
        {
          "id": "mod-1-prac-4",
          "order": 4,
          "type": "practice",
          "text": "Recreate common UI layouts in Tailwind CSS (responsive cards, sticky sidebars, modals).",
          "tags": ["tailwind-css", "ui-patterns"]
        }
      ],
      "interviewConcepts": [
        {
          "id": "mod-1-int-1",
          "order": 1,
          "type": "interview-concept",
          "text": "Semantic HTML & why it matters for SEO and screen readers (ARIA roles, aria-label, tabindex, focus traps).",
          "tags": ["seo", "a11y", "aria", "focus-management"]
        },
        {
          "id": "mod-1-int-2",
          "order": 2,
          "type": "interview-concept",
          "text": "The CSS Box Model (content-box vs. border-box), specificity calculation, stacking context (z-index), and positioning (relative, absolute, fixed, sticky).",
          "tags": ["box-model", "specificity", "z-index", "positioning"]
        },
        {
          "id": "mod-1-int-3",
          "order": 3,
          "type": "interview-concept",
          "text": "rem vs. em vs. px vs. vh/dvh.",
          "tags": ["css-units", "viewport"]
        },
        {
          "id": "mod-1-int-4",
          "order": 4,
          "type": "interview-concept",
          "text": "Critical Rendering Path (how the browser turns HTML/CSS/JS into pixels, reflow vs. repaint).",
          "tags": ["browser-internals", "rendering", "reflow-repaint"]
        }
      ]
    },
    {
      "id": "mod-2",
      "slug": "core-javascript-internals",
      "order": 2,
      "title": "Core JavaScript (0 to Internals)",
      "practice": [
        {
          "id": "mod-2-prac-1",
          "order": 1,
          "type": "practice",
          "text": "Write polyfills from scratch: Array.prototype.map, filter, reduce, flat, and Function.prototype.call, apply, bind.",
          "tags": ["polyfills", "arrays", "functions"]
        },
        {
          "id": "mod-2-prac-2",
          "order": 2,
          "type": "practice",
          "text": "Write utility functions: debounce(), throttle(), memoize(), deepClone() (handling nested objects/arrays), and curry().",
          "tags": ["utilities", "debounce", "throttle", "memoize", "deep-clone", "curry"]
        },
        {
          "id": "mod-2-prac-3",
          "order": 3,
          "type": "practice",
          "text": "Practice immutable array/object transformations (structuredClone, spread/rest, Object.groupBy, Map, Set).",
          "tags": ["immutability", "structuredClone", "map-set"]
        }
      ],
      "interviewConcepts": [
        {
          "id": "mod-2-int-1",
          "order": 1,
          "type": "interview-concept",
          "text": "Execution context, call stack, lexical scope, and closures (including classic stale closure bugs).",
          "tags": ["execution-context", "call-stack", "scope", "closures"]
        },
        {
          "id": "mod-2-int-2",
          "order": 2,
          "type": "interview-concept",
          "text": "Hoisting (var vs. let vs. const) and the Temporal Dead Zone (TDZ).",
          "tags": ["hoisting", "tdz", "variables"]
        },
        {
          "id": "mod-2-int-3",
          "order": 3,
          "type": "interview-concept",
          "text": "The this keyword across regular functions, arrow functions, methods, and constructors.",
          "tags": ["this-keyword", "functions"]
        },
        {
          "id": "mod-2-int-4",
          "order": 4,
          "type": "interview-concept",
          "text": "Prototypal inheritance and the prototype chain.",
          "tags": ["prototypes", "inheritance"]
        },
        {
          "id": "mod-2-int-5",
          "order": 5,
          "type": "interview-concept",
          "text": "Shallow copy vs. deep copy, pass-by-value vs. pass-by-reference, and garbage collection / memory leaks.",
          "tags": ["memory", "garbage-collection", "copying"]
        }
      ]
    },
    {
      "id": "mod-3",
      "slug": "asynchronous-js-dom-browser-apis",
      "order": 3,
      "title": "Asynchronous JS, DOM & Browser APIs",
      "practice": [
        {
          "id": "mod-3-prac-1",
          "order": 1,
          "type": "practice",
          "text": "Build a promise combinator suite from scratch: Promise.all, Promise.allSettled, Promise.race, Promise.any.",
          "tags": ["promises", "combinators", "async"]
        },
        {
          "id": "mod-3-prac-2",
          "order": 2,
          "type": "practice",
          "text": "Build an interactive list using event delegation (one listener on parent instead of 100 on children).",
          "tags": ["dom", "event-delegation", "performance"]
        },
        {
          "id": "mod-3-prac-3",
          "order": 3,
          "type": "practice",
          "text": "Implement request cancellation using AbortController when a user types rapidly in a search box.",
          "tags": ["AbortController", "cancellation", "fetch"]
        },
        {
          "id": "mod-3-prac-4",
          "order": 4,
          "type": "practice",
          "text": "Persist user preferences safely in localStorage with try/catch error handling.",
          "tags": ["localStorage", "error-handling", "storage"]
        }
      ],
      "interviewConcepts": [
        {
          "id": "mod-3-int-1",
          "order": 1,
          "type": "interview-concept",
          "text": "The Event Loop: call stack, Web APIs, Microtask Queue (Promises, queueMicrotask), and Macrotask/Callback Queue (setTimeout, DOM events)—be ready to predict console output order.",
          "tags": ["event-loop", "microtasks", "macrotasks", "async"]
        },
        {
          "id": "mod-3-int-2",
          "order": 2,
          "type": "interview-concept",
          "text": "Event bubbling, capturing, e.preventDefault(), and e.stopPropagation().",
          "tags": ["dom-events", "bubbling", "capturing"]
        },
        {
          "id": "mod-3-int-3",
          "order": 3,
          "type": "interview-concept",
          "text": "localStorage vs. sessionStorage vs. Cookies (HttpOnly, Secure, SameSite).",
          "tags": ["storage", "cookies", "security"]
        },
        {
          "id": "mod-3-int-4",
          "order": 4,
          "type": "interview-concept",
          "text": "CORS (why browsers block cross-origin requests and what preflight OPTIONS requests do).",
          "tags": ["cors", "http", "security"]
        }
      ]
    },
    {
      "id": "mod-4",
      "slug": "typescript-for-production-frontend",
      "order": 4,
      "title": "TypeScript for Production Frontend",
      "practice": [
        {
          "id": "mod-4-prac-1",
          "order": 1,
          "type": "practice",
          "text": "Type component props, children (React.ReactNode), event handlers (React.ChangeEvent<HTMLInputElement>), and custom hooks.",
          "tags": ["typescript", "react-types", "hooks"]
        },
        {
          "id": "mod-4-prac-2",
          "order": 2,
          "type": "practice",
          "text": "Model API responses using interface and type, discriminated unions for UI states ({ status: 'loading' } | { status: 'error'; error: string } | { status: 'success'; data: User[] }), and generics (ApiResponse<T>).",
          "tags": ["typescript", "discriminated-unions", "generics"]
        },
        {
          "id": "mod-4-prac-3",
          "order": 3,
          "type": "practice",
          "text": "Replace any with unknown + type guards (typeof, in, custom isUser predicates).",
          "tags": ["typescript", "type-guards", "unknown"]
        }
      ],
      "interviewConcepts": [
        {
          "id": "mod-4-int-1",
          "order": 1,
          "type": "interview-concept",
          "text": "type vs. interface (declaration merging, unions/intersections).",
          "tags": ["typescript", "type-vs-interface"]
        },
        {
          "id": "mod-4-int-2",
          "order": 2,
          "type": "interview-concept",
          "text": "any vs. unknown vs. never vs. void.",
          "tags": ["typescript", "type-system"]
        },
        {
          "id": "mod-4-int-3",
          "order": 3,
          "type": "interview-concept",
          "text": "Built-in utility types: Partial<T>, Pick<T, K>, Omit<T, K>, Record<K, V>, Required<T>, ReturnType<T>.",
          "tags": ["typescript", "utility-types"]
        },
        {
          "id": "mod-4-int-4",
          "order": 4,
          "type": "interview-concept",
          "text": "Type inference vs. explicit annotations.",
          "tags": ["typescript", "type-inference"]
        }
      ]
    },
    {
      "id": "mod-5",
      "slug": "react-core-to-react-19-machine-coding",
      "order": 5,
      "title": "React (Core to React 19 & Machine Coding)",
      "practice": [
        {
          "id": "mod-5-prac-1",
          "order": 1,
          "type": "practice",
          "text": "Debounced Typeahead / Autocomplete with keyboard navigation (ArrowUp/Down/Enter/Escape) and request cancellation.",
          "tags": ["machine-coding", "typeahead", "keyboard-nav", "react"]
        },
        {
          "id": "mod-5-prac-2",
          "order": 2,
          "type": "practice",
          "text": "Accessible Modal, Tabs, and Accordion components from scratch.",
          "tags": ["machine-coding", "components", "a11y", "react"]
        },
        {
          "id": "mod-5-prac-3",
          "order": 3,
          "type": "practice",
          "text": "Paginated & Sortable Data Table with client/server search and URL query sync (useSearchParams).",
          "tags": ["machine-coding", "data-table", "url-state", "react"]
        },
        {
          "id": "mod-5-prac-4",
          "order": 4,
          "type": "practice",
          "text": "Infinite Scroll Feed using IntersectionObserver.",
          "tags": ["machine-coding", "infinite-scroll", "IntersectionObserver"]
        },
        {
          "id": "mod-5-prac-5",
          "order": 5,
          "type": "practice",
          "text": "Custom Hooks: useDebounce, useFetch, useLocalStorage, useClickOutside.",
          "tags": ["custom-hooks", "react"]
        }
      ],
      "interviewConcepts": [
        {
          "id": "mod-5-int-1",
          "order": 1,
          "type": "interview-concept",
          "text": "Virtual DOM, Reconciliation, Diffing algorithm, and why key props matter (and why array index as key breaks state).",
          "tags": ["virtual-dom", "reconciliation", "keys", "react"]
        },
        {
          "id": "mod-5-int-2",
          "order": 2,
          "type": "interview-concept",
          "text": "Hooks rules and internals: useState batching, useEffect lifecycle and cleanup functions, useRef (DOM access vs. mutable values without re-renders), useMemo, and useCallback (when they help vs. when they add overhead).",
          "tags": ["hooks", "memoization", "lifecycle", "react"]
        },
        {
          "id": "mod-5-int-3",
          "order": 3,
          "type": "interview-concept",
          "text": "Controlled vs. Uncontrolled components.",
          "tags": ["forms", "controlled-vs-uncontrolled", "react"]
        },
        {
          "id": "mod-5-int-4",
          "order": 4,
          "type": "interview-concept",
          "text": "Code splitting with React.lazy + Suspense, and catching crashes with Error Boundaries.",
          "tags": ["code-splitting", "suspense", "error-boundaries", "react"]
        },
        {
          "id": "mod-5-int-5",
          "order": 5,
          "type": "interview-concept",
          "text": "Modern React (React 19): useOptimistic, useActionState, use(), and ref passed directly as a prop without forwardRef.",
          "tags": ["react-19", "useOptimistic", "useActionState", "use"]
        }
      ]
    },
    {
      "id": "mod-6",
      "slug": "rest-apis-state-management-forms",
      "order": 6,
      "title": "REST APIs, State Management & Forms",
      "practice": [
        {
          "id": "mod-6-prac-1",
          "order": 1,
          "type": "practice",
          "text": "Build a typed API client wrapper (fetch or axios) with base URLs, auth token headers, and centralized HTTP error handling (401, 403, 404, 500).",
          "tags": ["api-client", "http", "error-handling"]
        },
        {
          "id": "mod-6-prac-2",
          "order": 2,
          "type": "practice",
          "text": "Manage server state with TanStack Query (caching, loading/error states, mutations, cache invalidation) and global client state with Redux Toolkit or Zustand.",
          "tags": ["tanstack-query", "zustand", "redux-toolkit", "state-management"]
        },
        {
          "id": "mod-6-prac-3",
          "order": 3,
          "type": "practice",
          "text": "Build a multi-step validated form using React Hook Form + Zod.",
          "tags": ["react-hook-form", "zod", "forms", "validation"]
        }
      ],
      "interviewConcepts": [
        {
          "id": "mod-6-int-1",
          "order": 1,
          "type": "interview-concept",
          "text": "REST fundamentals: HTTP methods (GET, POST, PUT, PATCH, DELETE), idempotency, and status codes (200, 201, 204, 400, 401, 403, 404, 422, 429, 500).",
          "tags": ["rest", "http-methods", "status-codes", "idempotency"]
        },
        {
          "id": "mod-6-int-2",
          "order": 2,
          "type": "interview-concept",
          "text": "Client State vs. Server State (why putting API data in Redux manually is harder than using TanStack Query).",
          "tags": ["client-state", "server-state", "tanstack-query"]
        },
        {
          "id": "mod-6-int-3",
          "order": 3,
          "type": "interview-concept",
          "text": "Optimistic UI updates (updating the UI immediately before the server responds, and rolling back on error).",
          "tags": ["optimistic-ui", "mutations", "ux"]
        },
        {
          "id": "mod-6-int-4",
          "order": 4,
          "type": "interview-concept",
          "text": "JWT authentication flow on the frontend (access tokens, refresh tokens, protected routes).",
          "tags": ["auth", "jwt", "refresh-tokens", "protected-routes"]
        }
      ]
    },
    {
      "id": "mod-7",
      "slug": "nextjs-performance-web-security",
      "order": 7,
      "title": "Next.js, Performance & Web Security",
      "practice": [
        {
          "id": "mod-7-prac-1",
          "order": 1,
          "type": "practice",
          "text": "Build a Next.js App Router project with dynamic routes (/items/[id]), loading skeletons (loading.tsx), and error boundaries (error.tsx).",
          "tags": ["nextjs", "app-router", "routing", "suspense"]
        },
        {
          "id": "mod-7-prac-2",
          "order": 2,
          "type": "practice",
          "text": "Run Chrome Lighthouse on your deployed app and fix layout shifts, oversized images, and missing ARIA labels.",
          "tags": ["lighthouse", "performance", "a11y", "images"]
        }
      ],
      "interviewConcepts": [
        {
          "id": "mod-7-int-1",
          "order": 1,
          "type": "interview-concept",
          "text": "CSR vs. SSR vs. SSG vs. ISR—when to choose each and their trade-offs for SEO and initial load speed.",
          "tags": ["rendering-strategies", "ssr", "ssg", "isr", "csr", "seo"]
        },
        {
          "id": "mod-7-int-2",
          "order": 2,
          "type": "interview-concept",
          "text": "Next.js App Router: Server Components vs. Client Components (\"use client\").",
          "tags": ["nextjs", "rsc", "server-vs-client"]
        },
        {
          "id": "mod-7-int-3",
          "order": 3,
          "type": "interview-concept",
          "text": "Core Web Vitals: LCP (Largest Contentful Paint), INP (Interaction to Next Paint), and CLS (Cumulative Layout Shift).",
          "tags": ["core-web-vitals", "lcp", "inp", "cls", "performance"]
        },
        {
          "id": "mod-7-int-4",
          "order": 4,
          "type": "interview-concept",
          "text": "Frontend Security: Preventing XSS (Cross-Site Scripting, sanitizing HTML) and CSRF (Cross-Site Request Forgery).",
          "tags": ["security", "xss", "csrf"]
        }
      ]
    },
    {
      "id": "mod-8",
      "slug": "git-testing-debugging",
      "order": 8,
      "title": "Git, Testing & Debugging",
      "practice": [
        {
          "id": "mod-8-prac-1",
          "order": 1,
          "type": "practice",
          "text": "Use feature branches, clean conventional commits (feat:, fix:, refactor:), pull requests, and resolve merge conflicts cleanly.",
          "tags": ["git", "workflow", "conventional-commits"]
        },
        {
          "id": "mod-8-prac-2",
          "order": 2,
          "type": "practice",
          "text": "Write basic component tests with Vitest + React Testing Library (testing user interactions rather than internal implementation).",
          "tags": ["testing", "vitest", "react-testing-library"]
        },
        {
          "id": "mod-8-prac-3",
          "order": 3,
          "type": "practice",
          "text": "Use Chrome DevTools (Network tab waterfall, Performance flamegraph, React DevTools Profiler) to track down slow renders and failed API calls.",
          "tags": ["devtools", "debugging", "profiling"]
        }
      ],
      "interviewConcepts": []
    }
  ],
  "projects": [
    {
      "id": "proj-1",
      "slug": "accessible-ui-component-kit-debounced-search-explorer",
      "order": 1,
      "title": "Accessible UI Component Kit & Debounced Search Explorer",
      "tier": "foundational",
      "tierLabel": "Foundational",
      "isFlagship": false,
      "fastTrackEligible": false,
      "summary": "A clean, zero-dependency React + TypeScript library of a Modal, Accordion, Tabs, Toast notifications, and an async typeahead search bar wired to a public API (like GitHub Users or OpenLibrary).",
      "skillsProven": [
        "Semantic HTML",
        "ARIA/keyboard accessibility",
        "Debouncing",
        "AbortController",
        "Custom hooks",
        "Responsive CSS/Tailwind"
      ]
    },
    {
      "id": "proj-2",
      "slug": "ecommerce-storefront-url-synced-filters-cart",
      "order": 2,
      "title": "E-Commerce Storefront with URL-Synced Filters & Cart",
      "tier": "intermediate",
      "tierLabel": "Intermediate",
      "isFlagship": false,
      "fastTrackEligible": false,
      "summary": "A product catalog with multi-criteria filtering (category, price range, sort order) persisted in URL query parameters, persistent cart state, and optimistic quantity updates.",
      "skillsProven": [
        "Complex client state (Zustand or Redux Toolkit)",
        "URL state management",
        "Memoization",
        "Skeleton loaders",
        "Responsive grid layouts"
      ]
    },
    {
      "id": "proj-3",
      "slug": "job-application-interview-pipeline-tracker",
      "order": 3,
      "title": "Job Application & Interview Pipeline Tracker",
      "tier": "flagship",
      "tierLabel": "Flagship — High Practical Value",
      "isFlagship": true,
      "fastTrackEligible": true,
      "summary": "A Kanban board + sortable table workspace for tracking job applications across stages (Applied, Screening, Machine Coding, Offer), complete with follow-up reminders, company notes, and a conversion rate analytics bar.",
      "skillsProven": [
        "Drag-and-drop state",
        "Optimistic updates",
        "React Hook Form + Zod validation",
        "Local/database persistence",
        "Clean dashboard UX"
      ]
    },
    {
      "id": "proj-4",
      "slug": "incident-service-uptime-status-monitor",
      "order": 4,
      "title": "Incident & Service Uptime Status Monitor",
      "tier": "flagship",
      "tierLabel": "Flagship — SaaS Ops",
      "isFlagship": true,
      "fastTrackEligible": true,
      "summary": "A real-time service monitoring dashboard where teams configure API endpoints, inspect response latency charts, log incident timelines, and view a public-facing status page.",
      "skillsProven": [
        "Data visualization",
        "TanStack Query polling & caching",
        "Role-based UI views",
        "TypeScript discriminated unions",
        "Handling empty/error/degraded states"
      ]
    },
    {
      "id": "proj-5",
      "slug": "collaborative-api-webhook-sandbox",
      "order": 5,
      "title": "Collaborative API & Webhook Sandbox",
      "tier": "flagship",
      "tierLabel": "Flagship — Developer Tool",
      "isFlagship": true,
      "fastTrackEligible": true,
      "summary": "A developer utility to inspect incoming JSON/HTTP payloads, format and diff headers/bodies, save request collections, and replay requests with custom headers.",
      "skillsProven": [
        "Deep understanding of HTTP/REST internals",
        "Recursive JSON tree rendering",
        "Clipboard/keyboard shortcuts",
        "Senior-level engineering polish"
      ]
    }
  ],
  "dsa": {
    "repoName": "frontend-dsa-50",
    "languages": ["TypeScript", "JavaScript"],
    "complexityTracking": ["timeComplexity", "spaceComplexity"],
    "guidanceNote": "NCR frontend interviews rarely ask obscure graph theory, but they do test arrays, strings, hash maps, sliding windows, stacks, trees (DOM traversal), and JavaScript closures/promises.",
    "categories": [
      {
        "id": "dsa-cat-a",
        "code": "A",
        "order": 1,
        "title": "Arrays, Strings & Hashing",
        "expectedCount": 12,
        "problemIds": [
          "dsa-1", "dsa-2", "dsa-3", "dsa-4", "dsa-5", "dsa-6",
          "dsa-7", "dsa-8", "dsa-9", "dsa-10", "dsa-11", "dsa-12"
        ]
      },
      {
        "id": "dsa-cat-b",
        "code": "B",
        "order": 2,
        "title": "Two Pointers & Sliding Window",
        "expectedCount": 8,
        "problemIds": [
          "dsa-13", "dsa-14", "dsa-15", "dsa-16",
          "dsa-17", "dsa-18", "dsa-19", "dsa-20"
        ]
      },
      {
        "id": "dsa-cat-c",
        "code": "C",
        "order": 3,
        "title": "Stack, Queue & Binary Search",
        "expectedCount": 8,
        "problemIds": [
          "dsa-21", "dsa-22", "dsa-23", "dsa-24",
          "dsa-25", "dsa-26", "dsa-27", "dsa-28"
        ]
      },
      {
        "id": "dsa-cat-d",
        "code": "D",
        "order": 4,
        "title": "Linked Lists, Trees & Graphs — DOM & Nested UI Logic",
        "expectedCount": 10,
        "problemIds": [
          "dsa-29", "dsa-30", "dsa-31", "dsa-32", "dsa-33",
          "dsa-34", "dsa-35", "dsa-36", "dsa-37", "dsa-38"
        ]
      },
      {
        "id": "dsa-cat-e",
        "code": "E",
        "order": 5,
        "title": "JavaScript-Specific & Frontend Utility Problems on LeetCode",
        "expectedCount": 12,
        "problemIds": [
          "dsa-39", "dsa-40", "dsa-41", "dsa-42", "dsa-43", "dsa-44",
          "dsa-45", "dsa-46", "dsa-47", "dsa-48", "dsa-49", "dsa-50"
        ]
      }
    ],
    "problems": [
      { "id": "dsa-1", "categoryId": "dsa-cat-a", "categoryCode": "A", "categoryOrder": 1, "globalOrder": 1, "leetcodeId": 1, "title": "Two Sum", "frontendRelevance": null },
      { "id": "dsa-2", "categoryId": "dsa-cat-a", "categoryCode": "A", "categoryOrder": 2, "globalOrder": 2, "leetcodeId": 217, "title": "Contains Duplicate", "frontendRelevance": null },
      { "id": "dsa-3", "categoryId": "dsa-cat-a", "categoryCode": "A", "categoryOrder": 3, "globalOrder": 3, "leetcodeId": 242, "title": "Valid Anagram", "frontendRelevance": null },
      { "id": "dsa-4", "categoryId": "dsa-cat-a", "categoryCode": "A", "categoryOrder": 4, "globalOrder": 4, "leetcodeId": 49, "title": "Group Anagrams", "frontendRelevance": null },
      { "id": "dsa-5", "categoryId": "dsa-cat-a", "categoryCode": "A", "categoryOrder": 5, "globalOrder": 5, "leetcodeId": 347, "title": "Top K Frequent Elements", "frontendRelevance": null },
      { "id": "dsa-6", "categoryId": "dsa-cat-a", "categoryCode": "A", "categoryOrder": 6, "globalOrder": 6, "leetcodeId": 238, "title": "Product of Array Except Self", "frontendRelevance": null },
      { "id": "dsa-7", "categoryId": "dsa-cat-a", "categoryCode": "A", "categoryOrder": 7, "globalOrder": 7, "leetcodeId": 128, "title": "Longest Consecutive Sequence", "frontendRelevance": null },
      { "id": "dsa-8", "categoryId": "dsa-cat-a", "categoryCode": "A", "categoryOrder": 8, "globalOrder": 8, "leetcodeId": 53, "title": "Maximum Subarray", "frontendRelevance": null },
      { "id": "dsa-9", "categoryId": "dsa-cat-a", "categoryCode": "A", "categoryOrder": 9, "globalOrder": 9, "leetcodeId": 56, "title": "Merge Intervals", "frontendRelevance": null },
      { "id": "dsa-10", "categoryId": "dsa-cat-a", "categoryCode": "A", "categoryOrder": 10, "globalOrder": 10, "leetcodeId": 14, "title": "Longest Common Prefix", "frontendRelevance": null },
      { "id": "dsa-11", "categoryId": "dsa-cat-a", "categoryCode": "A", "categoryOrder": 11, "globalOrder": 11, "leetcodeId": 387, "title": "First Unique Character in a String", "frontendRelevance": null },
      { "id": "dsa-12", "categoryId": "dsa-cat-a", "categoryCode": "A", "categoryOrder": 12, "globalOrder": 12, "leetcodeId": 443, "title": "String Compression", "frontendRelevance": null },

      { "id": "dsa-13", "categoryId": "dsa-cat-b", "categoryCode": "B", "categoryOrder": 1, "globalOrder": 13, "leetcodeId": 125, "title": "Valid Palindrome", "frontendRelevance": null },
      { "id": "dsa-14", "categoryId": "dsa-cat-b", "categoryCode": "B", "categoryOrder": 2, "globalOrder": 14, "leetcodeId": 167, "title": "Two Sum II - Input Array Is Sorted", "frontendRelevance": null },
      { "id": "dsa-15", "categoryId": "dsa-cat-b", "categoryCode": "B", "categoryOrder": 3, "globalOrder": 15, "leetcodeId": 15, "title": "3Sum", "frontendRelevance": null },
      { "id": "dsa-16", "categoryId": "dsa-cat-b", "categoryCode": "B", "categoryOrder": 4, "globalOrder": 16, "leetcodeId": 11, "title": "Container With Most Water", "frontendRelevance": null },
      { "id": "dsa-17", "categoryId": "dsa-cat-b", "categoryCode": "B", "categoryOrder": 5, "globalOrder": 17, "leetcodeId": 121, "title": "Best Time to Buy and Sell Stock", "frontendRelevance": null },
      { "id": "dsa-18", "categoryId": "dsa-cat-b", "categoryCode": "B", "categoryOrder": 6, "globalOrder": 18, "leetcodeId": 3, "title": "Longest Substring Without Repeating Characters", "frontendRelevance": null },
      { "id": "dsa-19", "categoryId": "dsa-cat-b", "categoryCode": "B", "categoryOrder": 7, "globalOrder": 19, "leetcodeId": 424, "title": "Longest Repeating Character Replacement", "frontendRelevance": null },
      { "id": "dsa-20", "categoryId": "dsa-cat-b", "categoryCode": "B", "categoryOrder": 8, "globalOrder": 20, "leetcodeId": 209, "title": "Minimum Size Subarray Sum", "frontendRelevance": null },

      { "id": "dsa-21", "categoryId": "dsa-cat-c", "categoryCode": "C", "categoryOrder": 1, "globalOrder": 21, "leetcodeId": 20, "title": "Valid Parentheses", "frontendRelevance": "classic HTML/JSX tag matching" },
      { "id": "dsa-22", "categoryId": "dsa-cat-c", "categoryCode": "C", "categoryOrder": 2, "globalOrder": 22, "leetcodeId": 155, "title": "Min Stack", "frontendRelevance": null },
      { "id": "dsa-23", "categoryId": "dsa-cat-c", "categoryCode": "C", "categoryOrder": 3, "globalOrder": 23, "leetcodeId": 739, "title": "Daily Temperatures", "frontendRelevance": "monotonic stack" },
      { "id": "dsa-24", "categoryId": "dsa-cat-c", "categoryCode": "C", "categoryOrder": 4, "globalOrder": 24, "leetcodeId": 394, "title": "Decode String", "frontendRelevance": null },
      { "id": "dsa-25", "categoryId": "dsa-cat-c", "categoryCode": "C", "categoryOrder": 5, "globalOrder": 25, "leetcodeId": 704, "title": "Binary Search", "frontendRelevance": null },
      { "id": "dsa-26", "categoryId": "dsa-cat-c", "categoryCode": "C", "categoryOrder": 6, "globalOrder": 26, "leetcodeId": 33, "title": "Search in Rotated Sorted Array", "frontendRelevance": null },
      { "id": "dsa-27", "categoryId": "dsa-cat-c", "categoryCode": "C", "categoryOrder": 7, "globalOrder": 27, "leetcodeId": 153, "title": "Find Minimum in Rotated Sorted Array", "frontendRelevance": null },
      { "id": "dsa-28", "categoryId": "dsa-cat-c", "categoryCode": "C", "categoryOrder": 8, "globalOrder": 28, "leetcodeId": 875, "title": "Koko Eating Bananas", "frontendRelevance": null },

      { "id": "dsa-29", "categoryId": "dsa-cat-d", "categoryCode": "D", "categoryOrder": 1, "globalOrder": 29, "leetcodeId": 206, "title": "Reverse Linked List", "frontendRelevance": null },
      { "id": "dsa-30", "categoryId": "dsa-cat-d", "categoryCode": "D", "categoryOrder": 2, "globalOrder": 30, "leetcodeId": 21, "title": "Merge Two Sorted Lists", "frontendRelevance": null },
      { "id": "dsa-31", "categoryId": "dsa-cat-d", "categoryCode": "D", "categoryOrder": 3, "globalOrder": 31, "leetcodeId": 141, "title": "Linked List Cycle", "frontendRelevance": null },
      { "id": "dsa-32", "categoryId": "dsa-cat-d", "categoryCode": "D", "categoryOrder": 4, "globalOrder": 32, "leetcodeId": 146, "title": "LRU Cache", "frontendRelevance": "frequently asked in frontend caching rounds" },
      { "id": "dsa-33", "categoryId": "dsa-cat-d", "categoryCode": "D", "categoryOrder": 5, "globalOrder": 33, "leetcodeId": 226, "title": "Invert Binary Tree", "frontendRelevance": null },
      { "id": "dsa-34", "categoryId": "dsa-cat-d", "categoryCode": "D", "categoryOrder": 6, "globalOrder": 34, "leetcodeId": 104, "title": "Maximum Depth of Binary Tree", "frontendRelevance": "mirrors DOM tree depth" },
      { "id": "dsa-35", "categoryId": "dsa-cat-d", "categoryCode": "D", "categoryOrder": 7, "globalOrder": 35, "leetcodeId": 102, "title": "Binary Tree Level Order Traversal (BFS)", "frontendRelevance": null },
      { "id": "dsa-36", "categoryId": "dsa-cat-d", "categoryCode": "D", "categoryOrder": 8, "globalOrder": 36, "leetcodeId": 236, "title": "Lowest Common Ancestor of a Binary Tree", "frontendRelevance": "finding common parent DOM node" },
      { "id": "dsa-37", "categoryId": "dsa-cat-d", "categoryCode": "D", "categoryOrder": 9, "globalOrder": 37, "leetcodeId": 200, "title": "Number of Islands", "frontendRelevance": "grid DFS/BFS" },
      { "id": "dsa-38", "categoryId": "dsa-cat-d", "categoryCode": "D", "categoryOrder": 10, "globalOrder": 38, "leetcodeId": 207, "title": "Course Schedule", "frontendRelevance": "dependency resolution" },

      { "id": "dsa-39", "categoryId": "dsa-cat-e", "categoryCode": "E", "categoryOrder": 1, "globalOrder": 39, "leetcodeId": 2620, "title": "Counter", "frontendRelevance": "closures" },
      { "id": "dsa-40", "categoryId": "dsa-cat-e", "categoryCode": "E", "categoryOrder": 2, "globalOrder": 40, "leetcodeId": 2665, "title": "Counter II", "frontendRelevance": null },
      { "id": "dsa-41", "categoryId": "dsa-cat-e", "categoryCode": "E", "categoryOrder": 3, "globalOrder": 41, "leetcodeId": 2635, "title": "Apply Transform Over Each Element in Array", "frontendRelevance": "Array.map polyfill" },
      { "id": "dsa-42", "categoryId": "dsa-cat-e", "categoryCode": "E", "categoryOrder": 4, "globalOrder": 42, "leetcodeId": 2634, "title": "Filter Elements from Array", "frontendRelevance": "Array.filter polyfill" },
      { "id": "dsa-43", "categoryId": "dsa-cat-e", "categoryCode": "E", "categoryOrder": 5, "globalOrder": 43, "leetcodeId": 2626, "title": "Array Reduce Transformation", "frontendRelevance": "Array.reduce polyfill" },
      { "id": "dsa-44", "categoryId": "dsa-cat-e", "categoryCode": "E", "categoryOrder": 6, "globalOrder": 44, "leetcodeId": 2629, "title": "Function Composition", "frontendRelevance": null },
      { "id": "dsa-45", "categoryId": "dsa-cat-e", "categoryCode": "E", "categoryOrder": 7, "globalOrder": 45, "leetcodeId": 2666, "title": "Allow One Function Call", "frontendRelevance": "once utility" },
      { "id": "dsa-46", "categoryId": "dsa-cat-e", "categoryCode": "E", "categoryOrder": 8, "globalOrder": 46, "leetcodeId": 2623, "title": "Memoize", "frontendRelevance": "caching function results" },
      { "id": "dsa-47", "categoryId": "dsa-cat-e", "categoryCode": "E", "categoryOrder": 9, "globalOrder": 47, "leetcodeId": 2723, "title": "Add Two Promises", "frontendRelevance": null },
      { "id": "dsa-48", "categoryId": "dsa-cat-e", "categoryCode": "E", "categoryOrder": 10, "globalOrder": 48, "leetcodeId": 2637, "title": "Promise Time Limit", "frontendRelevance": "async timeout wrapper" },
      { "id": "dsa-49", "categoryId": "dsa-cat-e", "categoryCode": "E", "categoryOrder": 11, "globalOrder": 49, "leetcodeId": 2627, "title": "Debounce", "frontendRelevance": "most-asked frontend utility" },
      { "id": "dsa-50", "categoryId": "dsa-cat-e", "categoryCode": "E", "categoryOrder": 12, "globalOrder": 50, "leetcodeId": 2625, "title": "Flatten Deeply Nested Array", "frontendRelevance": "Array.flat recursion" }
    ]
  }
}