document.addEventListener('DOMContentLoaded', function () {
    const productItems = document.querySelectorAll('.product-item');

    productItems.forEach(item => {
        item.addEventListener('mouseenter', function () {
            const randomColor = getRandomColor();
            this.style.borderColor = randomColor;
        });

        item.addEventListener('mouseleave', function () {
            this.style.borderColor = 'transparent';
        });
    });

    function getRandomColor() {
        const letters = '0123456789ABCDEF';
        let color = '#';
        for (let i = 0; i < 6; i++) {
            color += letters[Math.floor(Math.random() * 16)];
        }
        return color;
    }
});
