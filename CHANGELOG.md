# Changelog

Tutte le modifiche rilevanti a questo plugin sono documentate in questo file.

Il formato è basato su [Keep a Changelog](https://keepachangelog.com/it/1.1.0/)
e questo progetto aderisce al [Semantic Versioning](https://semver.org/lang/it/).

## [1.0.0] - 2026-10-21

### Added
- Barra di avanzamento verso la spedizione gratuita con gli stati carrello vuoto, in corso e raggiunto.
- Posizioni: carrello, checkout e mini-cart, a blocchi (Store API + `assets/js/blocks.js`) e classici
  (`woocommerce_before_cart`, `woocommerce_before_checkout_form`, widget mini-cart con frammenti Ajax).
- Soglia personalizzata con eccezioni per paese, oppure letta dal metodo Spedizione gratuita di WooCommerce.
- Importo con IVA inclusa o esclusa, sconti dei coupon e coupon con spedizione gratuita.
- Pannello *WooCommerce → Free Shipping Bar* con messaggi, colori e posizioni; traduzione italiana.
- Dichiarazione di compatibilità con HPOS e con i blocchi Carrello/Checkout.
