# Whatsapp-chat-button
```
{/* WhatsApp Button */}
      <a
        href="https://wa.me/8801845058879" // Your provided number
        target="_blank"
        rel="noopener noreferrer"
        className="p-4 bg-[#25D366] text-white rounded-full shadow-lg hover:scale-110 active:scale-95 transition-all duration-300 relative group"
        title="Chat on WhatsApp"
      >
        <FaWhatsapp size={24} />
        
        {/* Pulsing Effect for WhatsApp */}
        <span className="absolute inset-0 rounded-full bg-[#25D366] animate-ping opacity-20 pointer-events-none"></span>
      </a>
```
