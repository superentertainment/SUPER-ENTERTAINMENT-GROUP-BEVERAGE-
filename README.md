        .text-secondary-gold { color: var(--color-secondary-gold); }
        .bg-accent-teal { background-color: var(--color-accent-teal); }
        .text-accent-teal { color: var(--color-accent-teal); }
        .border-accent-teal { border-color: var(--color-accent-teal); }

        /* Custom scroll behavior for smooth navigation */
        html {
            scroll-behavior: smooth;
        }

        /* Set the Inter font globally */
        body {
            font-family: 'Inter', sans-serif;
        }

        /* Styling for the custom logo */
        .header-logo {
            height: 60px; /* Adjust height as needed */
            width: auto;
        }

        /* Hide scrollbar but allow scrolling */
        body {
            -ms-overflow-style: none;  /* IE and Edge */
            scrollbar-width: none;  /* Firefox */
        }
        body::-webkit-scrollbar {
            display: none; /* Chrome, Safari, Opera */
        }
    </style>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        'primary-dark': 'var(--color-primary-dark)',
                        'secondary-gold': 'var(--color-secondary-gold)',
                        'accent-teal': 'var(--color-accent-teal)',
                    },
                },
            },
        }
    </script>
</head>
<body class="bg-primary-dark text-gray-100 min-h-screen">

    <!-- Navigation Bar -->
    <header class="sticky top-0 z-50 bg-primary-dark/95 shadow-lg border-b border-gray-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
