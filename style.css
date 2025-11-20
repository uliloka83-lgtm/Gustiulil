document.addEventListener('DOMContentLoaded', function() {
    // Fungsi untuk menandai link navigasi yang aktif
    function setActiveLink() {
        const path = window.location.pathname.split('/').pop();
        const links = document.querySelectorAll('.nav-links a');

        links.forEach(link => {
            link.classList.remove('active-link');
            const href = link.getAttribute('href');
            
            // Logika untuk menandai link aktif
            if (href === path || (path === 'index.html' && href === 'index.html') || (path === '' && href === 'index.html')) {
                link.classList.add('active-link');
            }
        });
    }

    setActiveLink();
    
    // Logika sederhana untuk formulir kontak (pada halaman contact.html)
    const contactForm = document.getElementById('contact-form');
    const successMessage = document.querySelector('.success-message');

    if (contactForm) {
        contactForm.addEventListener('submit', function(e) {
            e.preventDefault();
            // Simulasi pengiriman data
            setTimeout(() => {
                successMessage.classList.add('show');
                contactForm.reset();
                // Sembunyikan pesan setelah 3 detik
                setTimeout(() => {
                    successMessage.classList.remove('show');
                }, 3000);
            }, 500);
        });
    }

    // Fungsi untuk navigasi antar halaman (Jika Anda ingin mempertahankan gaya SPA)
    // Untuk tujuan GitHub Pages, link HTML biasa lebih disarankan.
    // Kode ini hanya placeholder.
    console.log("Website Cita Rasa Maron siap!");
});
