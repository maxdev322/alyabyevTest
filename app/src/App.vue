<template>
  <div>
    <list-item
      v-for="item in items"
      :key="item.id"
      :first_name="item.first_name"
      :id="item.id"
      :last_name="item.last_name"
      :email="item.email"
      :gender="item.gender"
      :ip_address="item.ip_address"
    ></list-item>
  </div>
</template>

<script>
import ListItem from "@/components/ListItem";
export default {
  components: {
    ListItem,
  },
  data() {
    return {
      items: [
        {
          id: 1,
          first_name: "Rockwell",
          last_name: "Janous",
          email: "rjanous0@unesco.org",
          gender: "Polygender",
          ip_address: "177.136.247.4",
        },
        {
          id: 2,
          first_name: "Ely",
          last_name: "McCulloch",
          email: "emcculloch1@ebay.com",
          gender: "Non-binary",
          ip_address: "229.124.48.211",
        },
        {
          id: 3,
          first_name: "Antony",
          last_name: "Goldberg",
          email: "agoldberg2@reddit.com",
          gender: "Polygender",
          ip_address: "160.126.28.37",
        },
        {
          id: 4,
          first_name: "Jeri",
          last_name: "De Gogay",
          email: "jdegogay3@amazon.com",
          gender: "Genderfluid",
          ip_address: "152.115.155.218",
        },
        {
          id: 5,
          first_name: "Benedetto",
          last_name: "Meak",
          email: "bmeak4@stanford.edu",
          gender: "Female",
          ip_address: "144.159.39.126",
        },
        {
          id: 6,
          first_name: "Andriana",
          last_name: "Lucio",
          email: "alucio5@msn.com",
          gender: "Genderqueer",
          ip_address: "232.94.92.36",
        },
        {
          id: 7,
          first_name: "Coralyn",
          last_name: "Clandillon",
          email: "cclandillon6@vk.com",
          gender: "Polygender",
          ip_address: "219.138.209.129",
        },
        {
          id: 8,
          first_name: "Thornton",
          last_name: "Perryn",
          email: "tperryn7@xing.com",
          gender: "Bigender",
          ip_address: "13.219.80.160",
        },
        {
          id: 9,
          first_name: "Hope",
          last_name: "Furmagier",
          email: "hfurmagier8@paypal.com",
          gender: "Male",
          ip_address: "146.97.65.113",
        },
        {
          id: 10,
          first_name: "Loydie",
          last_name: "Readie",
          email: "lreadie9@mapquest.com",
          gender: "Bigender",
          ip_address: "192.98.11.118",
        },
        {
          id: 11,
          first_name: "Gertruda",
          last_name: "MacDonough",
          email: "gmacdonougha@google.com.hk",
          gender: "Agender",
          ip_address: "247.135.151.86",
        },
        {
          id: 12,
          first_name: "Abdul",
          last_name: "Seegar",
          email: "aseegarb@oaic.gov.au",
          gender: "Non-binary",
          ip_address: "130.97.195.129",
        },
        {
          id: 13,
          first_name: "Gayel",
          last_name: "Shipway",
          email: "gshipwayc@toplist.cz",
          gender: "Genderfluid",
          ip_address: "230.233.44.6",
        },
        {
          id: 14,
          first_name: "Lynnet",
          last_name: "O'Hogertie",
          email: "lohogertied@fda.gov",
          gender: "Genderfluid",
          ip_address: "36.138.125.60",
        },
        {
          id: 15,
          first_name: "Milissent",
          last_name: "Reinisch",
          email: "mreinische@slideshare.net",
          gender: "Non-binary",
          ip_address: "48.176.99.243",
        },
        {
          id: 16,
          first_name: "Aubrette",
          last_name: "Gow",
          email: "agowf@google.co.uk",
          gender: "Agender",
          ip_address: "66.93.189.252",
        },
        {
          id: 17,
          first_name: "Marcellus",
          last_name: "Bainbridge",
          email: "mbainbridgeg@yolasite.com",
          gender: "Non-binary",
          ip_address: "221.242.145.236",
        },
        {
          id: 18,
          first_name: "Benita",
          last_name: "Tierney",
          email: "btierneyh@bigcartel.com",
          gender: "Genderqueer",
          ip_address: "214.65.41.153",
        },
        {
          id: 19,
          first_name: "Lamar",
          last_name: "Wimpress",
          email: "lwimpressi@ifeng.com",
          gender: "Bigender",
          ip_address: "157.185.2.225",
        },
        {
          id: 20,
          first_name: "Sharleen",
          last_name: "Cambden",
          email: "scambdenj@nbcnews.com",
          gender: "Non-binary",
          ip_address: "118.125.200.213",
        },
        {
          id: 21,
          first_name: "Elmore",
          last_name: "Dupree",
          email: "edupreek@howstuffworks.com",
          gender: "Genderfluid",
          ip_address: "223.185.47.94",
        },
        {
          id: 22,
          first_name: "Karoline",
          last_name: "Terron",
          email: "kterronl@macromedia.com",
          gender: "Genderqueer",
          ip_address: "61.31.1.42",
        },
        {
          id: 23,
          first_name: "Tierney",
          last_name: "Attersoll",
          email: "tattersollm@slideshare.net",
          gender: "Bigender",
          ip_address: "32.136.191.248",
        },
        {
          id: 24,
          first_name: "Rhonda",
          last_name: "McMurrugh",
          email: "rmcmurrughn@tiny.cc",
          gender: "Agender",
          ip_address: "21.126.142.222",
        },
        {
          id: 25,
          first_name: "Egan",
          last_name: "St. Louis",
          email: "estlouiso@boston.com",
          gender: "Genderfluid",
          ip_address: "115.157.112.209",
        },
        {
          id: 26,
          first_name: "Carmella",
          last_name: "Greenham",
          email: "cgreenhamp@cnbc.com",
          gender: "Male",
          ip_address: "89.74.222.187",
        },
        {
          id: 27,
          first_name: "Hersh",
          last_name: "Simmins",
          email: "hsimminsq@artisteer.com",
          gender: "Polygender",
          ip_address: "253.11.95.141",
        },
        {
          id: 28,
          first_name: "Logan",
          last_name: "Dutteridge",
          email: "ldutteridger@home.pl",
          gender: "Agender",
          ip_address: "99.61.86.202",
        },
        {
          id: 29,
          first_name: "Brigitta",
          last_name: "Earingey",
          email: "bearingeys@purevolume.com",
          gender: "Polygender",
          ip_address: "53.234.120.223",
        },
        {
          id: 30,
          first_name: "Onfroi",
          last_name: "Razoux",
          email: "orazouxt@a8.net",
          gender: "Genderfluid",
          ip_address: "114.252.79.186",
        },
        {
          id: 31,
          first_name: "Gunther",
          last_name: "Fawcett",
          email: "gfawcettu@icio.us",
          gender: "Male",
          ip_address: "219.103.32.47",
        },
        {
          id: 32,
          first_name: "Thoma",
          last_name: "Robion",
          email: "trobionv@google.com.br",
          gender: "Agender",
          ip_address: "200.30.45.0",
        },
        {
          id: 33,
          first_name: "Zenia",
          last_name: "Shreeve",
          email: "zshreevew@hostgator.com",
          gender: "Agender",
          ip_address: "57.17.247.12",
        },
        {
          id: 34,
          first_name: "Caryl",
          last_name: "Gauch",
          email: "cgauchx@indiegogo.com",
          gender: "Polygender",
          ip_address: "139.209.31.24",
        },
        {
          id: 35,
          first_name: "Carl",
          last_name: "Adcocks",
          email: "cadcocksy@hugedomains.com",
          gender: "Bigender",
          ip_address: "141.87.167.159",
        },
        {
          id: 36,
          first_name: "Clara",
          last_name: "Lovitt",
          email: "clovittz@aboutads.info",
          gender: "Female",
          ip_address: "188.4.213.59",
        },
        {
          id: 37,
          first_name: "Jermayne",
          last_name: "Yokley",
          email: "jyokley10@liveinternet.ru",
          gender: "Genderfluid",
          ip_address: "240.143.13.255",
        },
        {
          id: 38,
          first_name: "Car",
          last_name: "Ledgister",
          email: "cledgister11@odnoklassniki.ru",
          gender: "Non-binary",
          ip_address: "174.9.124.14",
        },
        {
          id: 39,
          first_name: "Bayard",
          last_name: "Bertomieu",
          email: "bbertomieu12@cam.ac.uk",
          gender: "Non-binary",
          ip_address: "83.252.74.243",
        },
        {
          id: 40,
          first_name: "Robbyn",
          last_name: "Gallihaulk",
          email: "rgallihaulk13@mysql.com",
          gender: "Genderqueer",
          ip_address: "142.118.242.233",
        },
        {
          id: 41,
          first_name: "Casi",
          last_name: "Hancorn",
          email: "chancorn14@house.gov",
          gender: "Genderfluid",
          ip_address: "244.16.107.12",
        },
        {
          id: 42,
          first_name: "Matti",
          last_name: "Sand",
          email: "msand15@loc.gov",
          gender: "Female",
          ip_address: "73.161.147.45",
        },
        {
          id: 43,
          first_name: "Rickard",
          last_name: "O'Hearn",
          email: "rohearn16@surveymonkey.com",
          gender: "Genderqueer",
          ip_address: "81.223.66.51",
        },
        {
          id: 44,
          first_name: "Cathyleen",
          last_name: "Arondel",
          email: "carondel17@scribd.com",
          gender: "Bigender",
          ip_address: "66.92.212.201",
        },
        {
          id: 45,
          first_name: "Kele",
          last_name: "Shawyers",
          email: "kshawyers18@photobucket.com",
          gender: "Non-binary",
          ip_address: "173.170.234.240",
        },
        {
          id: 46,
          first_name: "Bary",
          last_name: "Atyea",
          email: "batyea19@newsvine.com",
          gender: "Genderqueer",
          ip_address: "36.11.40.162",
        },
        {
          id: 47,
          first_name: "Ximenes",
          last_name: "Pleasants",
          email: "xpleasants1a@intel.com",
          gender: "Male",
          ip_address: "48.63.26.16",
        },
        {
          id: 48,
          first_name: "Adrianne",
          last_name: "Sessuns",
          email: "asessuns1b@rakuten.co.jp",
          gender: "Non-binary",
          ip_address: "194.109.99.224",
        },
        {
          id: 49,
          first_name: "Barbaraanne",
          last_name: "Bassam",
          email: "bbassam1c@pcworld.com",
          gender: "Agender",
          ip_address: "151.121.20.92",
        },
        {
          id: 50,
          first_name: "Sascha",
          last_name: "Bulteel",
          email: "sbulteel1d@scribd.com",
          gender: "Genderfluid",
          ip_address: "49.43.94.132",
        },
      ],
    };
  },
};
</script>

<style>
</style>