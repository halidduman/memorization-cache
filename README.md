# Hafıza Kullanımı (Memorization)

- Daha önce hesaplanmış bir veri ya da render edilmiş bir bileşeni yeniden işlem yapmak yerine ilk hesaplamanın sonuçlarını saklarız. Bu saklanan verileri tekrar kullanarak gereksiz işlemleri önler, performansı artırır ve sayfanın yüklenme sürelerini iyileştiririz.

## useMemo()

- Önceden yapılan hesaplamaların sonuçlarını bellekte saklayarak, tekrar hesaplama ihtiyacını ortadan kaldırır.

## useCallback()

- Daha önce oluşturulmuş bir fonksiyonu bellekte tutarak, her çağrıldığında yeniden oluşturulmasını engeller.

## React.memo()

- Önceden ekrana render edilen bir bileşeni hafızada tutar ve yalnızca prop'lar değiştiğinde yeniden render edilmesini sağlar.

# useReducer

- Daha karmaşık state yönetimi senaryolarında kullanılır.

### Dispatch (Gönderme)

- Action'ları bileşen içerisinden reducer'a ileterek işlem yapılmasını sağlar.

### Action (Eylem / Komut)

- State'in nasıl değişeceğini tanımlayan bir yapıdır.
