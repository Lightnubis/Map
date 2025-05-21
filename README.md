```mermaid
graph TD
    subgraph Aethelgard: Thế Giới Của Các Vị Thần
        center["Thánh Địa Hư Vô: Cánh Cổng Tử Giới (Thần Aether)"]

        subgraph Vùng Đất Ánh Sáng và Trật Tự
            humanis["Humanis: Thành Phố Bất Bại (Thần Solus - Kiêu Hãnh)"]
        end

        subgraph Vùng Đất Bóng Đêm và Ảo Ảnh
            nocturnis["Nocturnis: Rừng U Tối (Thần Luna - Đố Kỵ)"]
        end

        subgraph Vùng Đất Đất và Sức Mạnh
            gaians["Gaians: Thung Lũng Mộ Rêu (Thần Terra - Tham Lam)"]
        end

        subgraph Vùng Đất Gió và Tự Do
            aerians["Aerians: Đỉnh Gió Hoang (Thần Ventus - Phóng Đãng)"]
        end

        subgraph Vùng Đất Nước và Cảm Xúc
            undines["Undines: Vịnh Sương Mù (Thần Aqua - Lười Biếng)"]
        end

        subgraph Vùng Đất Lửa và Đam Mê
            ignis["Ignis: Núi Lửa Bất Diệt (Thần Pyra - Giận Dữ)"]
        end

        subgraph Vùng Đất Hoang Dã và Bản Năng
            therians["Therians: Savan Vô Biên (Thần Fera - Tham Ăn)"]
        end

        humanis --- center
        nocturnis --- center
        gaians --- center
        ignis --- center
        aerians --- center
        undines --- center
        therians --- center

        humanis --- gaians
        gaians --- ignis
        ignis --- aerians
        aerians --- nocturnis
        nocturnis --- undines
        undines --- therians
        therians --- humanis
    end
