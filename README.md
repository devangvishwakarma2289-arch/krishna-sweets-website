const products = [
  {
    id: 'kaju-katli',
    name: 'Kaju Katli',
    category: 'Barfi',
    price: 1350,
    image: 'https://images.unsplash.com/photo-1578985545062-69928b1d9587?auto=format&fit=crop&w=900&q=80',
    description: 'Silky cashew barfi with a melt-in-the-mouth finish and elegant saffron notes.',
    ingredients: 'Cashews, sugar, saffron, cardamom, ghee.'
  },
  {
    id: 'motichoor-laddu',
    name: 'Motichoor Laddu',
    category: 'Laddu',
    price: 980,
    image: 'https://images.unsplash.com/photo-1601050690597-df0568f70950?auto=format&fit=crop&w=900&q=80',
    description: 'Tiny pearl gram flour boondi coated in fragrant sugar syrup for a festive texture.',
    ingredients: 'Gram flour, sugar, saffron, cardamom, ghee.'
  },
  {
    id: 'besan-laddu',
    name: 'Besan Laddu',
    category: 'Laddu',
    price: 920,
    image: 'https://images.unsplash.com/photo-1532635241-1754a5f2f1f6?auto=format&fit=crop&w=900&q=80',
    description: 'Roasted gram flour laddus with nutty richness and aromatic cardamom.',
    ingredients: 'Gram flour, sugar, ghee, cashews, cardamom.'
  },
  {
    id: 'boondi-laddu',
    name: 'Boondi Laddu',
    category: 'Laddu',
    price: 950,
    image: 'https://images.unsplash.com/photo-1551024601-bec78aea704b?auto=format&fit=crop&w=900&q=80',
    description: 'Crunchy boondi pearls soaked in sugar and shaped into a classic festive favourite.',
    ingredients: 'Gram flour, sugar, raisins, cashews, ghee.'
  },
  {
    id: 'gulab-jamun',
    name: 'Gulab Jamun',
    category: 'Classic',
    price: 840,
    image: 'https://images.unsplash.com/photo-1617098907046-61d0d9e1a90d?auto=format&fit=crop&w=900&q=80',
    description: 'Soft khoya dumplings deep-fried and soaked in saffron-infused rose sugar syrup.',
    ingredients: 'Khoya, flour, sugar, rose water, saffron, ghee.'
  },
  {
    id: 'rasgulla',
    name: 'Rasgulla',
    category: 'Classic',
    price: 800,
    image: 'https://images.unsplash.com/photo-1542826438-bd32f43d626f?auto=format&fit=crop&w=900&q=80',
    description: 'Spongy chenna dumplings bathed in light sugar syrup for a gentle, refreshing sweetness.',
    ingredients: 'Chenna, sugar, cardamom, water.'
  },
  {
    id: 'rasmalai',
    name: 'Rasmalai',
    category: 'Classic',
    price: 880,
    image: 'https://images.unsplash.com/photo-1631452180519-c014fe946bc7?auto=format&fit=crop&w=900&q=80',
    description: 'Slow-simmered cheese patties resting in creamy saffron milk for a rich finish.',
    ingredients: 'Chenna, milk, saffron, nuts, sugar.'
  },
  {
    id: 'kalakand',
    name: 'Kalakand',
    category: 'Milk Sweets',
    price: 970,
    image: 'https://images.unsplash.com/photo-1515003197210-e0cd71810b5f?auto=format&fit=crop&w=900&q=80',
    description: 'A caramel-like milk sweet with soft grain and a subtle, toasted richness.',
    ingredients: 'Milk, sugar, cardamom, nuts, saffron.'
  },
  {
    id: 'milk-cake',
    name: 'Milk Cake',
    category: 'Milk Sweets',
    price: 940,
    image: 'https://images.unsplash.com/photo-1565958011703-44f9829ba187?auto=format&fit=crop&w=900&q=80',
    description: 'Dense and creamy milk fudge with a delicate caramel flavour and soft texture.',
    ingredients: 'Milk, sugar, ghee, cardamom, nuts.'
  },
  {
    id: 'peda',
    name: 'Peda',
    category: 'Milk Sweets',
    price: 930,
    image: 'https://images.unsplash.com/photo-1551024601-bec78aea704b?auto=format&fit=crop&w=900&q=80',
    description: 'Traditional slow-cooked milk peda finished with cardamom and a delicate floral aroma.',
    ingredients: 'Milk solids, sugar, cardamom, pistachio.'
  },
  {
    id: 'kesar-peda',
    name: 'Kesar Peda',
    category: 'Milk Sweets',
    price: 990,
    image: 'https://images.unsplash.com/photo-1582719478250-c89cae4dc85b?auto=format&fit=crop&w=900&q=80',
    description: 'Saffron-infused peda celebrated for its rich yellow tone and velvety finish.',
    ingredients: 'Milk solids, sugar, saffron, cardamom, pistachio.'
  },
  {
    id: 'mawa-barfi',
    name: 'Mawa Barfi',
    category: 'Barfi',
    price: 1150,
    image: 'https://images.unsplash.com/photo-1519864600265-abb23847ef2c?auto=format&fit=crop&w=900&q=80',
    description: 'Rich mawa-based barfi with a soft bite and elegant sweetness that lingers.',
    ingredients: 'Mawa, sugar, ghee, nuts, cardamom.'
  },
  {
    id: 'coconut-barfi',
    name: 'Coconut Barfi',
    category: 'Barfi',
    price: 910,
    image: 'https://images.unsplash.com/photo-1504674900247-0877df9cc836?auto=format&fit=crop&w=900&q=80',
    description: 'Coconut sweetness with a mellow chew, balanced with soft caramel notes.',
    ingredients: 'Coconut, milk solids, sugar, nuts, cardamom.'
  },
  {
    id: 'besan-barfi',
    name: 'Besan Barfi',
    category: 'Barfi',
    price: 900,
    image: 'https://images.unsplash.com/photo-1473093295043-cdd812d0e601?auto=format&fit=crop&w=900&q=80',
    description: 'Roasted gram flour barfi with nutty richness and deep golden flavour.',
    ingredients: 'Besan, sugar, ghee, nuts, cardamom.'
  },
  {
    id: 'soan-papdi',
    name: 'Soan Papdi',
    category: 'Fried Sweets',
    price: 820,
    image: 'https://images.unsplash.com/photo-1482049016688-2d3e1b311543?auto=format&fit=crop&w=900&q=80',
    description: 'Flaky, brittle sweet with a buttery crumb and delicate cardamom aroma.',
    ingredients: 'Gram flour, sugar, ghee, milk, pistachio.'
  },
  {
    id: 'mysore-pak',
    name: 'Mysore Pak',
    category: 'Fried Sweets',
    price: 1080,
    image: 'https://images.unsplash.com/photo-1495474472287-4d71bcdd2085?auto=format&fit=crop&w=900&q=80',
    description: 'A buttery, soft-textured sweet with a classic ghee-rich flavour.',
    ingredients: 'Gram flour, ghee, sugar, cardamom.'
  },
  {
    id: 'jalebi',
    name: 'Jalebi',
    category: 'Fried Sweets',
    price: 760,
    image: 'https://images.unsplash.com/photo-1614707267537-b85aaf00c4b7?auto=format&fit=crop&w=900&q=80',
    description: 'Crisp spiral sweets dipped in fragrant saffron sugar syrup for a zingy finish.',
    ingredients: 'Flour, sugar, saffron, yogurt, ghee.'
  },
  {
    id: 'imarti',
    name: 'Imarti',
    category: 'Fried Sweets',
    price: 780,
    image: 'https://images.unsplash.com/photo-1604908176997-125f25cc6f3d?auto=format&fit=crop&w=900&q=80',
    description: 'Deep-fried batter rings soaked in syrup, known for their rich texture and traditional taste.',
    ingredients: 'Gram flour, sugar, saffron, cardamom.'
  },
  {
    id: 'ghewar',
    name: 'Ghewar',
    category: 'Festival',
    price: 1100,
    image: 'https://images.unsplash.com/photo-1529042410759-befb1204b468?auto=format&fit=crop&w=900&q=80',
    description: 'A honeycomb-textured festive sweet known for its crispy layers and fragrant sweet syrup.',
    ingredients: 'Flour, sugar, ghee, saffron, cardamom.'
  },
  {
    id: 'mohanthal',
    name: 'Mohanthal',
    category: 'Festival',
    price: 1040,
    image: 'https://images.unsplash.com/photo-1559847844-5315695dadae?auto=format&fit=crop&w=900&q=80',
    description: 'A rich, grain-like sweet with roasted gram flour and a festive nutty finish.',
    ingredients: 'Besan, sugar, ghee, nuts, saffron.'
  },
  {
    id: 'anjeer-barfi',
    name: 'Anjeer Barfi',
    category: 'Barfi',
    price: 1180,
    image: 'https://images.unsplash.com/photo-1563379091339-03246963d7f5?auto=format&fit=crop&w=900&q=80',
    description: 'Premium fig barfi with a soft texture and naturally sweet, rich flavour.',
    ingredients: 'Anjeer, sugar, khoya, nuts, cardamom.'
  },
  {
    id: 'dry-fruit-laddu',
    name: 'Dry Fruit Laddu',
    category: 'Laddu',
    price: 1400,
    image: 'https://images.unsplash.com/photo-1512621776951-a57141f2eefd?auto=format&fit=crop&w=900&q=80',
    description: 'Dense laddu packed with almonds, cashews, dates, and elevated festive richness.',
    ingredients: 'Dry fruits, dates, sugar, ghee, nuts.'
  },
  {
    id: 'pista-roll',
    name: 'Pista Roll',
    category: 'Rolls',
    price: 1250,
    image: 'https://images.unsplash.com/photo-1505253716362-afaea1d3d1af?auto=format&fit=crop&w=900&q=80',
    description: 'Creamy pistachio roll with delicate sweetness and a smooth, elegant bite.',
    ingredients: 'Pistachios, milk solids, sugar, ghee, cardamom.'
  },
  {
    id: 'chenna-toast',
    name: 'Chenna Toast',
    category: 'Special',
    price: 870,
    image: 'https://images.unsplash.com/photo-1555939594-58d7cb561ad1?auto=format&fit=crop&w=900&q=80',
    description: 'Soft chenna-based sweet with a comforting texture and a fresh, milky finish.',
    ingredients: 'Chenna, sugar, nuts, saffron, cardamom.'
  }
];

const categories = ['All', ...new Set(products.map((item) => item.category))];
let selectedCategory = 'All';
let cart = [];

const productGrid = document.getElementById('productGrid');
const categoryFilters = document.getElementById('categoryFilters');
const searchInput = document.getElementById('searchInput');
const cartItemsEl = document.getElementById('cartItems');
const subtotalValue = document.getElementById('subtotalValue');
const totalValue = document.getElementById('totalValue');
const checkoutBtn = document.getElementById('checkoutBtn');
const cartCountBadge = document.getElementById('cartCountBadge');
const customerNameInput = document.getElementById('customerName');
const orderNotesInput = document.getElementById('orderNotes');

function formatCurrency(value) {
  return new Intl.NumberFormat('en-IN', {
    style: 'currency',
    currency: 'INR',
    maximumFractionDigits: 0
  }).format(value);
}

function buildCategoryFilters() {
  categoryFilters.innerHTML = categories
    .map(
      (category) => `
        <button
          class="filter-btn ${selectedCategory === category ? 'active' : ''}"
          type="button"
          data-category="${category}"
        >
          ${category}
        </button>
      `
    )
    .join('');

  document.querySelectorAll('.filter-btn').forEach((btn) => {
    btn.addEventListener('click', () => {
      selectedCategory = btn.dataset.category;
      buildCategoryFilters();
      renderProducts();
    });
  });
}

function getFilteredProducts() {
  const term = searchInput.value.trim().toLowerCase();

  return products.filter((product) => {
    const matchesCategory = selectedCategory === 'All' || product.category === selectedCategory;
    const matchesSearch = product.name.toLowerCase().includes(term);
    return matchesCategory && matchesSearch;
  });
}

function renderProducts() {
  const filteredProducts = getFilteredProducts();

  if (!filteredProducts.length) {
    productGrid.innerHTML = `
      <div class="empty-cart" style="grid-column: 1 / -1; min-height: 220px;">
        <div>
          <h3>No sweets match your search.</h3>
          <p>Try a different name or switch category filters.</p>
        </div>
      </div>
    `;
    return;
  }

  productGrid.innerHTML = filteredProducts
    .map(
      (product) => `
        <article class="product-card">
          <img src="${product.image}" alt="${product.name}" loading="lazy" />
          <div class="product-body">
            <div class="product-topline">
              <span class="product-tag">${product.category}</span>
              <span class="product-price">${formatCurrency(product.price)}/kg</span>
            </div>
            <h3>${product.name}</h3>
            <p>${product.description}</p>
            <div class="product-ingredients">
              <strong>Typical ingredients:</strong> ${product.ingredients}
            </div>
            <div class="product-actions">
              <button class="add-btn" type="button" data-add-id="${product.id}">Add to Cart</button>
            </div>
          </div>
        </article>
      `
    )
    .join('');

  document.querySelectorAll('[data-add-id]').forEach((btn) => {
    btn.addEventListener('click', () => addToCart(btn.dataset.addId));
  });
}

function addToCart(productId) {
  const existingItem = cart.find((item) => item.id === productId);

  if (existingItem) {
    existingItem.quantity += 1;
  } else {
    cart.push({ id: productId, quantity: 1 });
  }

  updateCart();
}

function updateCart() {
  if (!cart.length) {
    cartItemsEl.innerHTML = `
      <div class="empty-cart">
        <div>
          <h4>Your cart is empty</h4>
          <p>Add a few favourites to create your mithai order.</p>
        </div>
      </div>
    `;
  } else {
    cartItemsEl.innerHTML = cart
      .map((item) => {
        const product = products.find((entry) => entry.id === item.id);
        const lineTotal = product.price * item.quantity;
        return `
          <div class="cart-item">
            <div>
              <h4>${product.name}</h4>
              <div class="item-price">${formatCurrency(product.price)}/kg</div>
              <div class="qty-controls">
                <button type="button" data-decrease="${product.id}" aria-label="Decrease quantity">−</button>
                <span>${item.quantity}</span>
                <button type="button" data-increase="${product.id}" aria-label="Increase quantity">+</button>
              </div>
            </div>
            <div>
              <div class="item-price">${formatCurrency(lineTotal)}</div>
              <button class="remove-item" type="button" data-remove="${product.id}">Remove</button>
            </div>
          </div>
        `;
      })
      .join('');

    document.querySelectorAll('[data-increase]').forEach((button) => {
      button.addEventListener('click', () => {
        const id = button.dataset.increase;
        const item = cart.find((entry) => entry.id === id);
        if (item) item.quantity += 1;
        updateCart();
      });
    });

    document.querySelectorAll('[data-decrease]').forEach((button) => {
      button.addEventListener('click', () => {
        const id = button.dataset.decrease;
        const item = cart.find((entry) => entry.id === id);
        if (item) {
          item.quantity -= 1;
          if (item.quantity <= 0) {
            cart = cart.filter((entry) => entry.id !== id);
          }
        }
        updateCart();
      });
    });

    document.querySelectorAll('[data-remove]').forEach((button) => {
      button.addEventListener('click', () => {
        const id = button.dataset.remove;
        cart = cart.filter((entry) => entry.id !== id);
        updateCart();
      });
    });
  }

  const totalQty = cart.reduce((sum, item) => sum + item.quantity, 0);
  cartCountBadge.textContent = totalQty;

  const subtotal = cart.reduce((sum, item) => {
    const product = products.find((entry) => entry.id === item.id);
    return sum + product.price * item.quantity;
  }, 0);

  subtotalValue.textContent = formatCurrency(subtotal);
  totalValue.textContent = formatCurrency(subtotal);
}

function buildWhatsAppOrder() {
  if (!cart.length) {
    alert('Please add at least one sweet before sending your order.');
    return;
  }

  const customerName = customerNameInput.value.trim() || 'Not provided';
  const notes = orderNotesInput.value.trim() || 'None';

  const orderLines = cart
    .map((item) => {
      const product = products.find((entry) => entry.id === item.id);
      return `- ${product.name} x${item.quantity} (${formatCurrency(product.price)}/kg) = ${formatCurrency(product.price * item.quantity)}`;
    })
    .join('\n');

  const subtotal = cart.reduce((sum, item) => {
    const product = products.find((entry) => entry.id === item.id);
    return sum + product.price * item.quantity;
  }, 0);

  const message = `Hello KRISHNA SWEETS, I would like to place an order.%0A%0A` +
    `Customer Name: ${encodeURIComponent(customerName)}%0A` +
    `Order Notes: ${encodeURIComponent(notes)}%0A%0A` +
    `Items:%0A${encodeURIComponent(orderLines)}%0A%0A` +
    `Estimated Total: ${encodeURIComponent(formatCurrency(subtotal))}%0A%0A` +
    `Please confirm the final order, available quantities, and pricing before preparing it.`;

  window.open(`https://wa.me/917023560701?text=${message}`, '_blank', 'noopener');
}

searchInput.addEventListener('input', renderProducts);
checkoutBtn.addEventListener('click', buildWhatsAppOrder);

buildCategoryFilters();
renderProducts();
updateCart();
