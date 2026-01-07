document.getElementById('surpriseBtn').addEventListener('click', function() {
    const surprise = document.getElementById('surprise');
    surprise.classList.toggle('hidden');
    if (!surprise.classList.contains('hidden')) {
        // Add confetti effect (optional, requires a library like canvas-confetti)
        // For simplicity, just show the message
        alert('Surprise! ðŸŽ‰');
    }
});
