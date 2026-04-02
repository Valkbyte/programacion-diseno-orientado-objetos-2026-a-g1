# ¿Dónde aplicaste polimorfismo? 
**El polimorfismo se evidencia principalmente en el ciclo for, donde se recorre la lista y se llama al método calcularCosto() sin necesidad de usar condicionales para identificar el tipo de envío.**

# ¿Qué método sobrescribiste y por qué? 
**El método sobrescrito fue calcularCosto(), el cual se definió en la clase base Envio y luego se redefinió en cada subclase usando la anotación @Override, lo anterior se hizo porque así cada tipo de envío puede tener su propia lógica de cálculo según sus características.**

# ¿Qué pasaría si agregas un nuevo tipo de envío?
**Si se desea agregar un nuevo tipo de envío, solo sería necesario crear una nueva subclase que extienda de Envio y sobrescriba el método calcularCosto(), osea, usar @Override.**
