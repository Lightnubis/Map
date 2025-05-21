graph TD
    center["Thánh Địa Hư Vô: Cánh Cổng Tử Giới (Thần Aether)"]

    subgraph Vòng Tròn Đại Tội
        gaians["Gaians: Thung Lũng Mộ Rêu (Thần Terra - Tham Lam)"]
        ignis["Ignis: Núi Lửa Bất Diệt (Thần Pyra - Giận Dữ)"]
        aerians["Aerians: Đỉnh Gió Hoang (Thần Ventus - Phóng Đãng)"]
        nocturnis["Nocturnis: Rừng U Tối (Thần Luna - Đố Kỵ)"]
        humanis["Humanis: Thành Phố Bất Bại (Thần Solus - Kiêu Hãnh)"]
        undines["Undines: Vịnh Sương Mù (Thần Aqua - Lười Biếng)"]
        therians["Therians: Savan Vô Biên (Thần Fera - Tham Ăn)"]
    end

    gaians --> ignis
    ignis --> aerians
    aerians --> nocturnis
    nocturnis --> humanis
    humanis --> undines
    undines --> therians
    therians --> gaians

    gaians --- center
    ignis --- center
    aerians --- center
    nocturnis --- center
    humanis --- center
    undines --- center
    therians --- center
