# knuhs.cn.test
사대부고 기말 시험대비용 단어 생성기

기본 단어 목록
     { zh: "我", py: "Wǒ", ko: "나는", target: "나" },
        { zh: "你", py: "Nǐ", ko: "너는", target: "너" },
        { zh: "他", py: "Tā", ko: "그는", target: "그" },
        { zh: "哥哥", py: "Gēge", ko: "우리 형은", target: "우리 형" },
        { zh: "姐姐", py: "Jiějie", ko: "우리 누나는", target: "우리 누나" },
        { zh: "妹妹", py: "Mèimei", ko: "내 여동생은", target: "내 여동생" },
        { zh: "弟弟", py: "Dìdi", ko: "내 남동생은", target: "내 남동생" },
        { zh: "妈妈", py: "Māma", ko: "우리 엄마는", target: "우리 엄마" },
        { zh: "爸爸", py: "Bàba", ko: "우리 아빠는", target: "우리 아빠" },
        { zh: "朋友", py: "Péngyou", ko: "내 친구는", target: "내 친구" },
        { zh: "班长", py: "Bānzhǎng", ko: "우리 반 반장은", target: "우리 반 반장" },
        { zh: "老师", py: "Lǎoshī", ko: "우리 선생님은", target: "우리 선생님" }
    

    const places = [
        { zh: "商店", py: "shāngdiàn", ko: "마트(상점)" },
        { zh: "学校", py: "xuéxiào", ko: "학교" },
        { zh: "医院", py: "yīyuàn", ko: "병원" },
        { zh: "咖啡店", py: "kāfēidiàn", ko: "카페" },
        { zh: "家", py: "jiā", ko: "집" }
    ];

    const foods = [
        { zh: "麻辣烫", py: "málàtàng", ko: "마라탕" },
        { zh: "面包", py: "miànbāo", ko: "빵" },
        { zh: "菜", py: "cài", ko: "요리" }
    ];

    const drinks = [
        { zh: "咖啡", py: "kāfēi", ko: "커피" },
        { zh: "牛奶", py: "niúnǎi", ko: "우유" },
        { zh: "红茶", py: "hóngchá", ko: "홍차" }
    ];

    const adjs = [
        { zh: "困", py: "kùn", ko: "졸려" },
        { zh: "累", py: "lèi", ko: "피곤해" },
        { zh: "饿", py: "è", ko: "배고파" },
        { zh: "气", py: "qì", ko: "화나" }
    ];

    const statusAdjs = [
        { zh: "幸福", py: "xìngfú", ko: "행복하다" },
        { zh: "高兴", py: "gāoxìng", ko: "기쁘다" },
        { zh: "舒服", py: "shūfu", ko: "편안하다" },
        { zh: "难过", py: "nánguò", ko: "슬프다" },
        { zh: "聪明", py: "cōngmíng", ko: "똑똑하다" }
    ];
    
