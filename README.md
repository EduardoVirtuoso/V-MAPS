# V-MAPS
Repositório com alguns experimentos com Sistemas de Informação Geográfica.

[<!DOCTYPE html>
<head>    
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    
        <script>
            L_NO_TOUCH = false;
            L_DISABLE_3D = false;
        </script>
    
    <script src="https://cdn.jsdelivr.net/npm/leaflet@1.6.0/dist/leaflet.js"></script>
    <script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.6.0/dist/leaflet.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap-theme.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.3/css/font-awesome.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css"/>
    <link rel="stylesheet" href="https://rawcdn.githack.com/python-visualization/folium/master/folium/templates/leaflet.awesome.rotate.css"/>
    <style>html, body {width: 100%;height: 100%;margin: 0;padding: 0;}</style>
    <style>#map {position:absolute;top:0;bottom:0;right:0;left:0;}</style>
    
            <meta name="viewport" content="width=device-width,
                initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
            <style>
                #map_7cd24502863849108046db94f05d8b7e {
                    position: relative;
                    width: 100.0%;
                    height: 100.0%;
                    left: 0.0%;
                    top: 0.0%;
                }
            </style>
        
</head>
<body>    
    
            <div class="folium-map" id="map_7cd24502863849108046db94f05d8b7e" ></div>
        
</body>
<script>    
    
            var map_7cd24502863849108046db94f05d8b7e = L.map(
                "map_7cd24502863849108046db94f05d8b7e",
                {
                    center: [0, 0],
                    crs: L.CRS.EPSG3857,
                    zoom: 1,
                    zoomControl: true,
                    preferCanvas: false,
                    zoomStarts: 2,
                }
            );

            

        
    
            var tile_layer_84eeca99664c41eab4ffb76cb4c45119 = L.tileLayer(
                "https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png",
                {"attribution": "Data by \u0026copy; \u003ca href=\"http://openstreetmap.org\"\u003eOpenStreetMap\u003c/a\u003e, under \u003ca href=\"http://www.openstreetmap.org/copyright\"\u003eODbL\u003c/a\u003e.", "detectRetina": false, "maxNativeZoom": 18, "maxZoom": 18, "minZoom": 0, "noWrap": false, "opacity": 1, "subdomains": "abc", "tms": false}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
            var marker_78af07b5a43d49bf975f5a01c0670dbc = L.marker(
                [-29.97399055, -51.194029188293065],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_c6107c8ed7714913bc638dde691ecddc = L.popup({"maxWidth": "100%"});

        
            var html_f5fc2ead35214876a435db95d52ef36e = $(`<div id="html_f5fc2ead35214876a435db95d52ef36e" style="width: 100.0%; height: 100.0%;">Arena do Grêmio</div>`)[0];
            popup_c6107c8ed7714913bc638dde691ecddc.setContent(html_f5fc2ead35214876a435db95d52ef36e);
        

        marker_78af07b5a43d49bf975f5a01c0670dbc.bindPopup(popup_c6107c8ed7714913bc638dde691ecddc)
        ;

        
    
    
            var marker_0199741d68ab4ceca6edb15fa96a8a07 = L.marker(
                [-27.6512563, -52.26489236225326],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_fb651335b66b4535a3fb730bf550dc4b = L.popup({"maxWidth": "100%"});

        
            var html_5d60665d07484d009b60e50ddf705fe1 = $(`<div id="html_5d60665d07484d009b60e50ddf705fe1" style="width: 100.0%; height: 100.0%;">Colosso da Lagoa</div>`)[0];
            popup_fb651335b66b4535a3fb730bf550dc4b.setContent(html_5d60665d07484d009b60e50ddf705fe1);
        

        marker_0199741d68ab4ceca6edb15fa96a8a07.bindPopup(popup_fb651335b66b4535a3fb730bf550dc4b)
        ;

        
    
    
            var marker_cf4d7923d158481cb7fe82cfcd3d6a50 = L.marker(
                [-26.31685525, -48.83349956813208],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_83d4717ae0514de5b04564c147cc99fc = L.popup({"maxWidth": "100%"});

        
            var html_aea7b71128fd421694a7fe9e472d374f = $(`<div id="html_aea7b71128fd421694a7fe9e472d374f" style="width: 100.0%; height: 100.0%;">Arena Joinville</div>`)[0];
            popup_83d4717ae0514de5b04564c147cc99fc.setContent(html_aea7b71128fd421694a7fe9e472d374f);
        

        marker_cf4d7923d158481cb7fe82cfcd3d6a50.bindPopup(popup_83d4717ae0514de5b04564c147cc99fc)
        ;

        
    
    
            var marker_d4b1e9902c394593a33d8f10b372ce98 = L.marker(
                [-29.1623097, -51.17623677246522],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_4b7102e6d1b4421b82f81dd49d074dd1 = L.popup({"maxWidth": "100%"});

        
            var html_36dabaec4b4e49309ab71751d4e34c3b = $(`<div id="html_36dabaec4b4e49309ab71751d4e34c3b" style="width: 100.0%; height: 100.0%;">Alfredo Jaconi</div>`)[0];
            popup_4b7102e6d1b4421b82f81dd49d074dd1.setContent(html_36dabaec4b4e49309ab71751d4e34c3b);
        

        marker_d4b1e9902c394593a33d8f10b372ce98.bindPopup(popup_4b7102e6d1b4421b82f81dd49d074dd1)
        ;

        
    
    
            var marker_adadf2017b734391831756c5580b6938 = L.marker(
                [-28.684339100000003, -49.36767700483055],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_8411c2acbc5d4291aa5d79aea3cb7f21 = L.popup({"maxWidth": "100%"});

        
            var html_e8e1efcc10554d39911ee2c53de572fc = $(`<div id="html_e8e1efcc10554d39911ee2c53de572fc" style="width: 100.0%; height: 100.0%;">Heriberto Hülse</div>`)[0];
            popup_8411c2acbc5d4291aa5d79aea3cb7f21.setContent(html_e8e1efcc10554d39911ee2c53de572fc);
        

        marker_adadf2017b734391831756c5580b6938.bindPopup(popup_8411c2acbc5d4291aa5d79aea3cb7f21)
        ;

        
    
    
            var marker_2e0704185447479592d7d1e3b43174ed = L.marker(
                [-27.58554625, -48.58646580892749],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_195e680d9eb247b0889c07c6ab80dd9b = L.popup({"maxWidth": "100%"});

        
            var html_bea0905e6c3f4737a9fe85477e2e9b55 = $(`<div id="html_bea0905e6c3f4737a9fe85477e2e9b55" style="width: 100.0%; height: 100.0%;">Orlando Scarpelli</div>`)[0];
            popup_195e680d9eb247b0889c07c6ab80dd9b.setContent(html_bea0905e6c3f4737a9fe85477e2e9b55);
        

        marker_2e0704185447479592d7d1e3b43174ed.bindPopup(popup_195e680d9eb247b0889c07c6ab80dd9b)
        ;

        
    
    
            var marker_3e8f23cc358f4db495dc2bfa7be7d151 = L.marker(
                [-25.439483199999998, -49.25581718514153],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_b37d05b4654249b9991c6d2b1110056e = L.popup({"maxWidth": "100%"});

        
            var html_9fb285fc0fd74926a04e11ae4a5be6df = $(`<div id="html_9fb285fc0fd74926a04e11ae4a5be6df" style="width: 100.0%; height: 100.0%;">Vila Capanema</div>`)[0];
            popup_b37d05b4654249b9991c6d2b1110056e.setContent(html_9fb285fc0fd74926a04e11ae4a5be6df);
        

        marker_3e8f23cc358f4db495dc2bfa7be7d151.bindPopup(popup_b37d05b4654249b9991c6d2b1110056e)
        ;

        
    
    
            var marker_dd748e33fd4d453eae6a2f476e154ace = L.marker(
                [-23.41415195, -51.93803540038412],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_faa1ffb363c7469a8d1fff93e5c84b5d = L.popup({"maxWidth": "100%"});

        
            var html_c0f2457ec68747d9874037e73d6aca7a = $(`<div id="html_c0f2457ec68747d9874037e73d6aca7a" style="width: 100.0%; height: 100.0%;">Willie Davids</div>`)[0];
            popup_faa1ffb363c7469a8d1fff93e5c84b5d.setContent(html_c0f2457ec68747d9874037e73d6aca7a);
        

        marker_dd748e33fd4d453eae6a2f476e154ace.bindPopup(popup_faa1ffb363c7469a8d1fff93e5c84b5d)
        ;

        
    
    
            var marker_7a083865415f4b4488e653ceafc124bb = L.marker(
                [-27.10409255, -52.60698180721067],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_f2a70ee5c08e4dd6a7e3a7b03c2d11dc = L.popup({"maxWidth": "100%"});

        
            var html_92d581c44bd14ea19d9b22a5214fc278 = $(`<div id="html_92d581c44bd14ea19d9b22a5214fc278" style="width: 100.0%; height: 100.0%;">Arena Condá</div>`)[0];
            popup_f2a70ee5c08e4dd6a7e3a7b03c2d11dc.setContent(html_92d581c44bd14ea19d9b22a5214fc278);
        

        marker_7a083865415f4b4488e653ceafc124bb.bindPopup(popup_f2a70ee5c08e4dd6a7e3a7b03c2d11dc)
        ;

        
    
    
            var marker_62864f6e724a46fe899a6e1e5adbf0af = L.marker(
                [-31.761068299999998, -52.33606216950615],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_7c61d31ada4c4c1c99f216e66f386dae = L.popup({"maxWidth": "100%"});

        
            var html_9c3c6742d77647f8853ea16b43e8f483 = $(`<div id="html_9c3c6742d77647f8853ea16b43e8f483" style="width: 100.0%; height: 100.0%;">Boca do Lobo</div>`)[0];
            popup_7c61d31ada4c4c1c99f216e66f386dae.setContent(html_9c3c6742d77647f8853ea16b43e8f483);
        

        marker_62864f6e724a46fe899a6e1e5adbf0af.bindPopup(popup_7c61d31ada4c4c1c99f216e66f386dae)
        ;

        
    
    
            var marker_77c664aeaa88465ebdbe0169cfea7230 = L.marker(
                [-28.28263935, -52.376390700313806],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_0a63d26d858f4734b907d7c372740cb3 = L.popup({"maxWidth": "100%"});

        
            var html_ac937387c48e4ac6b1ec559050d7a4be = $(`<div id="html_ac937387c48e4ac6b1ec559050d7a4be" style="width: 100.0%; height: 100.0%;">Vermelhão da Serra</div>`)[0];
            popup_0a63d26d858f4734b907d7c372740cb3.setContent(html_ac937387c48e4ac6b1ec559050d7a4be);
        

        marker_77c664aeaa88465ebdbe0169cfea7230.bindPopup(popup_0a63d26d858f4734b907d7c372740cb3)
        ;

        
    
    
            var marker_823ea3a8083245e5bb495aa3a61b15a9 = L.marker(
                [-29.1536159, -51.53660925529764],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_f07c911feef84ba8a25937d78543a056 = L.popup({"maxWidth": "100%"});

        
            var html_7b4b65762f28450e92a6d77856548080 = $(`<div id="html_7b4b65762f28450e92a6d77856548080" style="width: 100.0%; height: 100.0%;">Montanha dos Vinhedos</div>`)[0];
            popup_f07c911feef84ba8a25937d78543a056.setContent(html_7b4b65762f28450e92a6d77856548080);
        

        marker_823ea3a8083245e5bb495aa3a61b15a9.bindPopup(popup_f07c911feef84ba8a25937d78543a056)
        ;

        
    
    
            var marker_555125d1dc4743fa8f2a0a0c4569c0ba = L.marker(
                [-25.116192400000003, -50.15657943685897],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_35b2b95bab5d444b870a96a2f3c1247f = L.popup({"maxWidth": "100%"});

        
            var html_eb5ece89d8c44b4c82f25472fd81a124 = $(`<div id="html_eb5ece89d8c44b4c82f25472fd81a124" style="width: 100.0%; height: 100.0%;">Germano Krüger</div>`)[0];
            popup_35b2b95bab5d444b870a96a2f3c1247f.setContent(html_eb5ece89d8c44b4c82f25472fd81a124);
        

        marker_555125d1dc4743fa8f2a0a0c4569c0ba.bindPopup(popup_35b2b95bab5d444b870a96a2f3c1247f)
        ;

        
    
    
            var marker_b3b51e5059f3428e8d88d762cca3d12f = L.marker(
                [-30.0654898, -51.23491778159686],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_8176df1b52284df386639f2aaf2a0426 = L.popup({"maxWidth": "100%"});

        
            var html_f3b2cdc34279402a8d846c0c3e481887 = $(`<div id="html_f3b2cdc34279402a8d846c0c3e481887" style="width: 100.0%; height: 100.0%;">Beira-Rio</div>`)[0];
            popup_8176df1b52284df386639f2aaf2a0426.setContent(html_f3b2cdc34279402a8d846c0c3e481887);
        

        marker_b3b51e5059f3428e8d88d762cca3d12f.bindPopup(popup_8176df1b52284df386639f2aaf2a0426)
        ;

        
    
    
            var marker_267ab79de34244e5bf35d417d407e1ec = L.marker(
                [-25.4484176, -49.27685626521088],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_ac49102fef88410abab4e0a9a9c198c1 = L.popup({"maxWidth": "100%"});

        
            var html_f1704558d718493ba7789c9a4a5b1304 = $(`<div id="html_f1704558d718493ba7789c9a4a5b1304" style="width: 100.0%; height: 100.0%;">Arena da Baixada</div>`)[0];
            popup_ac49102fef88410abab4e0a9a9c198c1.setContent(html_f1704558d718493ba7789c9a4a5b1304);
        

        marker_267ab79de34244e5bf35d417d407e1ec.bindPopup(popup_ac49102fef88410abab4e0a9a9c198c1)
        ;

        
    
    
            var marker_4c321ac3feab4a28bb071795392c4731 = L.marker(
                [-25.421417650000002, -49.25972893497825],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_1b9f9265dbac459a83cbaf766e66a56f = L.popup({"maxWidth": "100%"});

        
            var html_c40bf6e5a6b14ed1af81f512c400737f = $(`<div id="html_c40bf6e5a6b14ed1af81f512c400737f" style="width: 100.0%; height: 100.0%;">Couto Pereira</div>`)[0];
            popup_1b9f9265dbac459a83cbaf766e66a56f.setContent(html_c40bf6e5a6b14ed1af81f512c400737f);
        

        marker_4c321ac3feab4a28bb071795392c4731.bindPopup(popup_1b9f9265dbac459a83cbaf766e66a56f)
        ;

        
    
    
            var marker_fe6734accfce409192353fe6a9dbe3c5 = L.marker(
                [-23.283655, -51.1642694],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_76d17267d2414a6892988a0be0c1a6bb = L.popup({"maxWidth": "100%"});

        
            var html_10a7c194e934486499fe8be2af54e852 = $(`<div id="html_10a7c194e934486499fe8be2af54e852" style="width: 100.0%; height: 100.0%;">Estádio do Café</div>`)[0];
            popup_76d17267d2414a6892988a0be0c1a6bb.setContent(html_10a7c194e934486499fe8be2af54e852);
        

        marker_fe6734accfce409192353fe6a9dbe3c5.bindPopup(popup_76d17267d2414a6892988a0be0c1a6bb)
        ;

        
    
    
            var marker_ef74c2bfa2c7462c95b1a72dd77e8469 = L.marker(
                [-24.9712386, -53.5060716],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_850b47d550da4f18abc15cc1112c6385 = L.popup({"maxWidth": "100%"});

        
            var html_3214f8ce2ec04ce6a0796b957a4ade4d = $(`<div id="html_3214f8ce2ec04ce6a0796b957a4ade4d" style="width: 100.0%; height: 100.0%;">Regional Arnaldo Busatto</div>`)[0];
            popup_850b47d550da4f18abc15cc1112c6385.setContent(html_3214f8ce2ec04ce6a0796b957a4ade4d);
        

        marker_ef74c2bfa2c7462c95b1a72dd77e8469.bindPopup(popup_850b47d550da4f18abc15cc1112c6385)
        ;

        
    
    
            var marker_3fb8bec54cdb40f2abe19575b8541462 = L.marker(
                [-29.1670064, -51.1977841],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_4cca133a1c5340cea73a7fb0fad27e2b = L.popup({"maxWidth": "100%"});

        
            var html_edd1c16c6eab4d60bc6fb4e8927ebfcf = $(`<div id="html_edd1c16c6eab4d60bc6fb4e8927ebfcf" style="width: 100.0%; height: 100.0%;">Centenário</div>`)[0];
            popup_4cca133a1c5340cea73a7fb0fad27e2b.setContent(html_edd1c16c6eab4d60bc6fb4e8927ebfcf);
        

        marker_3fb8bec54cdb40f2abe19575b8541462.bindPopup(popup_4cca133a1c5340cea73a7fb0fad27e2b)
        ;

        
    
    
            var marker_ab0d05d9b1a349da809fd1119fc937f1 = L.marker(
                [-27.6640339, -48.5386679],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_b9574f2a9c0c419496b8defc7e9073e5 = L.popup({"maxWidth": "100%"});

        
            var html_6c70cb61ab094bca9d7bfa08ab9d8074 = $(`<div id="html_6c70cb61ab094bca9d7bfa08ab9d8074" style="width: 100.0%; height: 100.0%;">Ressacada</div>`)[0];
            popup_b9574f2a9c0c419496b8defc7e9073e5.setContent(html_6c70cb61ab094bca9d7bfa08ab9d8074);
        

        marker_ab0d05d9b1a349da809fd1119fc937f1.bindPopup(popup_b9574f2a9c0c419496b8defc7e9073e5)
        ;

        
    
    
            var marker_ed49444b7b10494dbfbcee806cfd14ae = L.marker(
                [-24.725387, -53.7542582],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_7a528e0fab9b481db1d931811ff9a5dc = L.popup({"maxWidth": "100%"});

        
            var html_0f595a3e63624cdea4042e3edb22247b = $(`<div id="html_0f595a3e63624cdea4042e3edb22247b" style="width: 100.0%; height: 100.0%;">14 de Dezembro</div>`)[0];
            popup_7a528e0fab9b481db1d931811ff9a5dc.setContent(html_0f595a3e63624cdea4042e3edb22247b);
        

        marker_ed49444b7b10494dbfbcee806cfd14ae.bindPopup(popup_7a528e0fab9b481db1d931811ff9a5dc)
        ;

        
    
    
            var marker_ebf245630f5a4d0e89bd6f4fc501e552 = L.marker(
                [-25.5230817, -49.2320156],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_22e509a76d824bf1bb5ed7cd400be7cd = L.popup({"maxWidth": "100%"});

        
            var html_79549dee3c4c49e58370ab726f6ca52a = $(`<div id="html_79549dee3c4c49e58370ab726f6ca52a" style="width: 100.0%; height: 100.0%;">Érton Coelho Queiroz</div>`)[0];
            popup_22e509a76d824bf1bb5ed7cd400be7cd.setContent(html_79549dee3c4c49e58370ab726f6ca52a);
        

        marker_ebf245630f5a4d0e89bd6f4fc501e552.bindPopup(popup_22e509a76d824bf1bb5ed7cd400be7cd)
        ;

        
    
    
            var marker_8d40fd544c554e4d9847d8e0bb9330f6 = L.marker(
                [-29.9103393, -51.1656685],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_fec16ca8bc6e4dd486a51e0003c85279 = L.popup({"maxWidth": "100%"});

        
            var html_c9a3018cbe9d425db43572777ae3cdae = $(`<div id="html_c9a3018cbe9d425db43572777ae3cdae" style="width: 100.0%; height: 100.0%;">Complexo Esportivo da Ulbra</div>`)[0];
            popup_fec16ca8bc6e4dd486a51e0003c85279.setContent(html_c9a3018cbe9d425db43572777ae3cdae);
        

        marker_8d40fd544c554e4d9847d8e0bb9330f6.bindPopup(popup_fec16ca8bc6e4dd486a51e0003c85279)
        ;

        
    
    
            var marker_87bd7f3eb3b34a65aa8444bc4e8a03e8 = L.marker(
                [-29.97399055, -51.194029188293065],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_55ebf9579dde47e8b19f7b277cee53ea = L.popup({"maxWidth": "100%"});

        
            var html_95b3ccdb69e44abd8fe7fcd26061d0a5 = $(`<div id="html_95b3ccdb69e44abd8fe7fcd26061d0a5" style="width: 100.0%; height: 100.0%;">Arena do Grêmio<br><br>Capacidade55662</div>`)[0];
            popup_55ebf9579dde47e8b19f7b277cee53ea.setContent(html_95b3ccdb69e44abd8fe7fcd26061d0a5);
        

        marker_87bd7f3eb3b34a65aa8444bc4e8a03e8.bindPopup(popup_55ebf9579dde47e8b19f7b277cee53ea)
        ;

        
    
    
            var marker_111db6191b7742cda724154e2335ef3a = L.marker(
                [-27.6512563, -52.26489236225326],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_f2db335a848c4402a4079cbe1a0bcdf7 = L.popup({"maxWidth": "100%"});

        
            var html_6b2952c27e744a9a992cd08b7ba2492c = $(`<div id="html_6b2952c27e744a9a992cd08b7ba2492c" style="width: 100.0%; height: 100.0%;">Colosso da Lagoa<br><br>Capacidade22000</div>`)[0];
            popup_f2db335a848c4402a4079cbe1a0bcdf7.setContent(html_6b2952c27e744a9a992cd08b7ba2492c);
        

        marker_111db6191b7742cda724154e2335ef3a.bindPopup(popup_f2db335a848c4402a4079cbe1a0bcdf7)
        ;

        
    
    
            var marker_069d0e10edd444609a94393efffa346f = L.marker(
                [-26.31685525, -48.83349956813208],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_98ea14be473a47eb881f9f6d445b344e = L.popup({"maxWidth": "100%"});

        
            var html_9f4bd3ee588942b7af51c4292eee90a8 = $(`<div id="html_9f4bd3ee588942b7af51c4292eee90a8" style="width: 100.0%; height: 100.0%;">Arena Joinville<br><br>Capacidade20160</div>`)[0];
            popup_98ea14be473a47eb881f9f6d445b344e.setContent(html_9f4bd3ee588942b7af51c4292eee90a8);
        

        marker_069d0e10edd444609a94393efffa346f.bindPopup(popup_98ea14be473a47eb881f9f6d445b344e)
        ;

        
    
    
            var marker_b8a495a442a6434aa2cedc28c55cd9b6 = L.marker(
                [-29.1623097, -51.17623677246522],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_e01975a822864d59a0f888ac5a668125 = L.popup({"maxWidth": "100%"});

        
            var html_c1ce94efdbe2458aae4332f38c4694d5 = $(`<div id="html_c1ce94efdbe2458aae4332f38c4694d5" style="width: 100.0%; height: 100.0%;">Alfredo Jaconi<br><br>Capacidade19924</div>`)[0];
            popup_e01975a822864d59a0f888ac5a668125.setContent(html_c1ce94efdbe2458aae4332f38c4694d5);
        

        marker_b8a495a442a6434aa2cedc28c55cd9b6.bindPopup(popup_e01975a822864d59a0f888ac5a668125)
        ;

        
    
    
            var marker_51a25c820cfe4311873b8fa9b13b7be1 = L.marker(
                [-28.684339100000003, -49.36767700483055],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_eb42d0d9b3944598a40d8b4741fd4992 = L.popup({"maxWidth": "100%"});

        
            var html_72d9812975bf4fa48ed5c23ec5ddac7a = $(`<div id="html_72d9812975bf4fa48ed5c23ec5ddac7a" style="width: 100.0%; height: 100.0%;">Heriberto Hülse<br><br>Capacidade19900</div>`)[0];
            popup_eb42d0d9b3944598a40d8b4741fd4992.setContent(html_72d9812975bf4fa48ed5c23ec5ddac7a);
        

        marker_51a25c820cfe4311873b8fa9b13b7be1.bindPopup(popup_eb42d0d9b3944598a40d8b4741fd4992)
        ;

        
    
    
            var marker_2815a0c5adea4634aac7dfeccb193eb5 = L.marker(
                [-27.58554625, -48.58646580892749],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_f998b2682aea4b80b9d993cd99c8d10f = L.popup({"maxWidth": "100%"});

        
            var html_95cf26f88d1f4d63800fa881e6f24293 = $(`<div id="html_95cf26f88d1f4d63800fa881e6f24293" style="width: 100.0%; height: 100.0%;">Orlando Scarpelli<br><br>Capacidade19584</div>`)[0];
            popup_f998b2682aea4b80b9d993cd99c8d10f.setContent(html_95cf26f88d1f4d63800fa881e6f24293);
        

        marker_2815a0c5adea4634aac7dfeccb193eb5.bindPopup(popup_f998b2682aea4b80b9d993cd99c8d10f)
        ;

        
    
    
            var marker_b75d5536efe441aa90745bc758518e66 = L.marker(
                [-25.439483199999998, -49.25581718514153],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_fa9a3fee26bc4385a1ca2ac481b288b2 = L.popup({"maxWidth": "100%"});

        
            var html_be26a76800384a7a8ace2ab8245e6fc4 = $(`<div id="html_be26a76800384a7a8ace2ab8245e6fc4" style="width: 100.0%; height: 100.0%;">Vila Capanema<br><br>Capacidade17140</div>`)[0];
            popup_fa9a3fee26bc4385a1ca2ac481b288b2.setContent(html_be26a76800384a7a8ace2ab8245e6fc4);
        

        marker_b75d5536efe441aa90745bc758518e66.bindPopup(popup_fa9a3fee26bc4385a1ca2ac481b288b2)
        ;

        
    
    
            var marker_c229256514744218ab3a76e6ec8c3a1d = L.marker(
                [-23.41415195, -51.93803540038412],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_cc0b80f99b5e4693a0dac87257372058 = L.popup({"maxWidth": "100%"});

        
            var html_a5bc3fdbd79940c3bd73a6ea8c2e0791 = $(`<div id="html_a5bc3fdbd79940c3bd73a6ea8c2e0791" style="width: 100.0%; height: 100.0%;">Willie Davids<br><br>Capacidade16226</div>`)[0];
            popup_cc0b80f99b5e4693a0dac87257372058.setContent(html_a5bc3fdbd79940c3bd73a6ea8c2e0791);
        

        marker_c229256514744218ab3a76e6ec8c3a1d.bindPopup(popup_cc0b80f99b5e4693a0dac87257372058)
        ;

        
    
    
            var marker_70e785d2b2664d4c9f50b8f733190654 = L.marker(
                [-27.10409255, -52.60698180721067],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_62f5b55b12854bfcba15bb26c1b05ade = L.popup({"maxWidth": "100%"});

        
            var html_6e3e3abb3caa406ba830e08dd789eee5 = $(`<div id="html_6e3e3abb3caa406ba830e08dd789eee5" style="width: 100.0%; height: 100.0%;">Arena Condá<br><br>Capacidade15765</div>`)[0];
            popup_62f5b55b12854bfcba15bb26c1b05ade.setContent(html_6e3e3abb3caa406ba830e08dd789eee5);
        

        marker_70e785d2b2664d4c9f50b8f733190654.bindPopup(popup_62f5b55b12854bfcba15bb26c1b05ade)
        ;

        
    
    
            var marker_810d9aa86a89417ab76f16ce828ab50e = L.marker(
                [-31.761068299999998, -52.33606216950615],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_47af78cbd6d04a0ebacf2783b01bef40 = L.popup({"maxWidth": "100%"});

        
            var html_8efb97d1c8764f93ba4ef2fe10a6cef9 = $(`<div id="html_8efb97d1c8764f93ba4ef2fe10a6cef9" style="width: 100.0%; height: 100.0%;">Boca do Lobo<br><br>Capacidade15478</div>`)[0];
            popup_47af78cbd6d04a0ebacf2783b01bef40.setContent(html_8efb97d1c8764f93ba4ef2fe10a6cef9);
        

        marker_810d9aa86a89417ab76f16ce828ab50e.bindPopup(popup_47af78cbd6d04a0ebacf2783b01bef40)
        ;

        
    
    
            var marker_18f16c85e1414cccad7878415b61cd2e = L.marker(
                [-28.28263935, -52.376390700313806],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_c16d79eb6c154174933ca4e82974660a = L.popup({"maxWidth": "100%"});

        
            var html_17ad794ed8b742069e44d4c2a3e5255a = $(`<div id="html_17ad794ed8b742069e44d4c2a3e5255a" style="width: 100.0%; height: 100.0%;">Vermelhão da Serra<br><br>Capacidade15000</div>`)[0];
            popup_c16d79eb6c154174933ca4e82974660a.setContent(html_17ad794ed8b742069e44d4c2a3e5255a);
        

        marker_18f16c85e1414cccad7878415b61cd2e.bindPopup(popup_c16d79eb6c154174933ca4e82974660a)
        ;

        
    
    
            var marker_cf57e39b22ba492789c98247e1192c0e = L.marker(
                [-29.1536159, -51.53660925529764],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_0002d4ff2ec54c8fbe080e9f3906e7c6 = L.popup({"maxWidth": "100%"});

        
            var html_7da009cdbe204880a2fddeec5ecf6f53 = $(`<div id="html_7da009cdbe204880a2fddeec5ecf6f53" style="width: 100.0%; height: 100.0%;">Montanha dos Vinhedos<br><br>Capacidade12859</div>`)[0];
            popup_0002d4ff2ec54c8fbe080e9f3906e7c6.setContent(html_7da009cdbe204880a2fddeec5ecf6f53);
        

        marker_cf57e39b22ba492789c98247e1192c0e.bindPopup(popup_0002d4ff2ec54c8fbe080e9f3906e7c6)
        ;

        
    
    
            var marker_f1aefd4ddfe24f70b7d8175e9493e460 = L.marker(
                [-25.116192400000003, -50.15657943685897],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_e478667a2b8e4c9dadf5578a64c0926c = L.popup({"maxWidth": "100%"});

        
            var html_4772fe9f95a44f249d8d89819d81d60e = $(`<div id="html_4772fe9f95a44f249d8d89819d81d60e" style="width: 100.0%; height: 100.0%;">Germano Krüger<br><br>Capacidade10632</div>`)[0];
            popup_e478667a2b8e4c9dadf5578a64c0926c.setContent(html_4772fe9f95a44f249d8d89819d81d60e);
        

        marker_f1aefd4ddfe24f70b7d8175e9493e460.bindPopup(popup_e478667a2b8e4c9dadf5578a64c0926c)
        ;

        
    
    
            var marker_45b9c51bd7c047b5a73eb66799d4623d = L.marker(
                [-30.0654898, -51.23491778159686],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_bd6ea656a10141f9ab78f0bbf9b30b8e = L.popup({"maxWidth": "100%"});

        
            var html_36975566b4874b34bbe42ab5c265e189 = $(`<div id="html_36975566b4874b34bbe42ab5c265e189" style="width: 100.0%; height: 100.0%;">Beira-Rio<br><br>Capacidade50128</div>`)[0];
            popup_bd6ea656a10141f9ab78f0bbf9b30b8e.setContent(html_36975566b4874b34bbe42ab5c265e189);
        

        marker_45b9c51bd7c047b5a73eb66799d4623d.bindPopup(popup_bd6ea656a10141f9ab78f0bbf9b30b8e)
        ;

        
    
    
            var marker_70e7c7b038a24984bb3672018cef7bdd = L.marker(
                [-25.4484176, -49.27685626521088],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_5473521a43444e31bcb993e89d6c140a = L.popup({"maxWidth": "100%"});

        
            var html_8a6207ee48ec436f9c77eaabfe0de054 = $(`<div id="html_8a6207ee48ec436f9c77eaabfe0de054" style="width: 100.0%; height: 100.0%;">Arena da Baixada<br><br>Capacidade42372</div>`)[0];
            popup_5473521a43444e31bcb993e89d6c140a.setContent(html_8a6207ee48ec436f9c77eaabfe0de054);
        

        marker_70e7c7b038a24984bb3672018cef7bdd.bindPopup(popup_5473521a43444e31bcb993e89d6c140a)
        ;

        
    
    
            var marker_30c1cc4409ca4c819eb1c8e9f97b9b64 = L.marker(
                [-25.421417650000002, -49.25972893497825],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_b642a9c0f3d649c4bb7342508ad3003d = L.popup({"maxWidth": "100%"});

        
            var html_ab00a0e3fdb241db85234bf7dd531dd5 = $(`<div id="html_ab00a0e3fdb241db85234bf7dd531dd5" style="width: 100.0%; height: 100.0%;">Couto Pereira<br><br>Capacidade40501</div>`)[0];
            popup_b642a9c0f3d649c4bb7342508ad3003d.setContent(html_ab00a0e3fdb241db85234bf7dd531dd5);
        

        marker_30c1cc4409ca4c819eb1c8e9f97b9b64.bindPopup(popup_b642a9c0f3d649c4bb7342508ad3003d)
        ;

        
    
    
            var marker_e351d77738d54117b15ddeb4f9975442 = L.marker(
                [-23.283655, -51.1642694],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_7c11f4131d194399a43aaa448130b1bd = L.popup({"maxWidth": "100%"});

        
            var html_7924f6242be441afb968c08caa6bf171 = $(`<div id="html_7924f6242be441afb968c08caa6bf171" style="width: 100.0%; height: 100.0%;">Estádio do Café<br><br>Capacidade30000</div>`)[0];
            popup_7c11f4131d194399a43aaa448130b1bd.setContent(html_7924f6242be441afb968c08caa6bf171);
        

        marker_e351d77738d54117b15ddeb4f9975442.bindPopup(popup_7c11f4131d194399a43aaa448130b1bd)
        ;

        
    
    
            var marker_4b7a47b17fd843c6a6803c6da5b67a2c = L.marker(
                [-24.9712386, -53.5060716],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_af948426f8bd44b6a237779a2fbda674 = L.popup({"maxWidth": "100%"});

        
            var html_4a283ccaf3884bfe9a401c4a4b920810 = $(`<div id="html_4a283ccaf3884bfe9a401c4a4b920810" style="width: 100.0%; height: 100.0%;">Regional Arnaldo Busatto<br><br>Capacidade25000</div>`)[0];
            popup_af948426f8bd44b6a237779a2fbda674.setContent(html_4a283ccaf3884bfe9a401c4a4b920810);
        

        marker_4b7a47b17fd843c6a6803c6da5b67a2c.bindPopup(popup_af948426f8bd44b6a237779a2fbda674)
        ;

        
    
    
            var marker_d338425f396f4550b18f083614c8e3dd = L.marker(
                [-29.1670064, -51.1977841],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_199977d3f29640008bf0f89dc3828696 = L.popup({"maxWidth": "100%"});

        
            var html_7d9dda490566452885bd27b6d7cd6476 = $(`<div id="html_7d9dda490566452885bd27b6d7cd6476" style="width: 100.0%; height: 100.0%;">Centenário<br><br>Capacidade22131</div>`)[0];
            popup_199977d3f29640008bf0f89dc3828696.setContent(html_7d9dda490566452885bd27b6d7cd6476);
        

        marker_d338425f396f4550b18f083614c8e3dd.bindPopup(popup_199977d3f29640008bf0f89dc3828696)
        ;

        
    
    
            var marker_d989f7c96c084bf2b3f3cf733586e42b = L.marker(
                [-27.6640339, -48.5386679],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_ebd057634d674f389086323033c1d53f = L.popup({"maxWidth": "100%"});

        
            var html_530079adcf294cbd84c50ef8b89223e5 = $(`<div id="html_530079adcf294cbd84c50ef8b89223e5" style="width: 100.0%; height: 100.0%;">Ressacada<br><br>Capacidade17826</div>`)[0];
            popup_ebd057634d674f389086323033c1d53f.setContent(html_530079adcf294cbd84c50ef8b89223e5);
        

        marker_d989f7c96c084bf2b3f3cf733586e42b.bindPopup(popup_ebd057634d674f389086323033c1d53f)
        ;

        
    
    
            var marker_9c9d80e3d4294503a07b3e1f34c2b2c2 = L.marker(
                [-24.725387, -53.7542582],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_1c20c5483788481886e72783e62f1e18 = L.popup({"maxWidth": "100%"});

        
            var html_d64e9e6c78114cad891d1971d1ca19fa = $(`<div id="html_d64e9e6c78114cad891d1971d1ca19fa" style="width: 100.0%; height: 100.0%;">14 de Dezembro<br><br>Capacidade12500</div>`)[0];
            popup_1c20c5483788481886e72783e62f1e18.setContent(html_d64e9e6c78114cad891d1971d1ca19fa);
        

        marker_9c9d80e3d4294503a07b3e1f34c2b2c2.bindPopup(popup_1c20c5483788481886e72783e62f1e18)
        ;

        
    
    
            var marker_51f11959aca54e238d9aa405dd8982e3 = L.marker(
                [-25.5230817, -49.2320156],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_d4e11f2bbd454b31ab018f560292b0a9 = L.popup({"maxWidth": "100%"});

        
            var html_fac3dcc8e9484e73acc6687e5c369fb7 = $(`<div id="html_fac3dcc8e9484e73acc6687e5c369fb7" style="width: 100.0%; height: 100.0%;">Érton Coelho Queiroz<br><br>Capacidade10000</div>`)[0];
            popup_d4e11f2bbd454b31ab018f560292b0a9.setContent(html_fac3dcc8e9484e73acc6687e5c369fb7);
        

        marker_51f11959aca54e238d9aa405dd8982e3.bindPopup(popup_d4e11f2bbd454b31ab018f560292b0a9)
        ;

        
    
    
            var marker_f350e424c1854ee9858d57eec5ad9530 = L.marker(
                [-29.9103393, -51.1656685],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_c1880c5029d041518fe47ee5102e8f89 = L.popup({"maxWidth": "100%"});

        
            var html_883a8dad22b944af98a63fc2c8cd2603 = $(`<div id="html_883a8dad22b944af98a63fc2c8cd2603" style="width: 100.0%; height: 100.0%;">Complexo Esportivo da Ulbra<br><br>Capacidade10000</div>`)[0];
            popup_c1880c5029d041518fe47ee5102e8f89.setContent(html_883a8dad22b944af98a63fc2c8cd2603);
        

        marker_f350e424c1854ee9858d57eec5ad9530.bindPopup(popup_c1880c5029d041518fe47ee5102e8f89)
        ;

        
    
    
            var marker_c263d29aec4a468fad117c1f61432076 = L.marker(
                [-29.97399055, -51.194029188293065],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_60ec3830d4c14a038109780704580d02 = L.popup({"maxWidth": "100%"});

        
            var html_2757608bbece4d9a8dab70b059a23261 = $(`<div id="html_2757608bbece4d9a8dab70b059a23261" style="width: 100.0%; height: 100.0%;">Arena do Grêmio<br><br>Capacidade: 55662</div>`)[0];
            popup_60ec3830d4c14a038109780704580d02.setContent(html_2757608bbece4d9a8dab70b059a23261);
        

        marker_c263d29aec4a468fad117c1f61432076.bindPopup(popup_60ec3830d4c14a038109780704580d02)
        ;

        
    
    
            var marker_5500531167a544ebbb5cd7e61c515e12 = L.marker(
                [-27.6512563, -52.26489236225326],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_adbd11549af1477b805e0c8d3f764fd3 = L.popup({"maxWidth": "100%"});

        
            var html_e715ae7c05c04178b012f5975240ceaa = $(`<div id="html_e715ae7c05c04178b012f5975240ceaa" style="width: 100.0%; height: 100.0%;">Colosso da Lagoa<br><br>Capacidade: 22000</div>`)[0];
            popup_adbd11549af1477b805e0c8d3f764fd3.setContent(html_e715ae7c05c04178b012f5975240ceaa);
        

        marker_5500531167a544ebbb5cd7e61c515e12.bindPopup(popup_adbd11549af1477b805e0c8d3f764fd3)
        ;

        
    
    
            var marker_4e08e858f89d46b186e15563bc42611c = L.marker(
                [-26.31685525, -48.83349956813208],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_6eeaa14d9c8747cfa1b54fbaa1600dd8 = L.popup({"maxWidth": "100%"});

        
            var html_f609c746db4d4fc1af19c25da3b36d69 = $(`<div id="html_f609c746db4d4fc1af19c25da3b36d69" style="width: 100.0%; height: 100.0%;">Arena Joinville<br><br>Capacidade: 20160</div>`)[0];
            popup_6eeaa14d9c8747cfa1b54fbaa1600dd8.setContent(html_f609c746db4d4fc1af19c25da3b36d69);
        

        marker_4e08e858f89d46b186e15563bc42611c.bindPopup(popup_6eeaa14d9c8747cfa1b54fbaa1600dd8)
        ;

        
    
    
            var marker_751cd26c7cbb49c39be84584bd98e26f = L.marker(
                [-29.1623097, -51.17623677246522],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_0439d81951374b95a036514df7080e94 = L.popup({"maxWidth": "100%"});

        
            var html_c9a939d98b824149841fbc0a2b60d6ac = $(`<div id="html_c9a939d98b824149841fbc0a2b60d6ac" style="width: 100.0%; height: 100.0%;">Alfredo Jaconi<br><br>Capacidade: 19924</div>`)[0];
            popup_0439d81951374b95a036514df7080e94.setContent(html_c9a939d98b824149841fbc0a2b60d6ac);
        

        marker_751cd26c7cbb49c39be84584bd98e26f.bindPopup(popup_0439d81951374b95a036514df7080e94)
        ;

        
    
    
            var marker_bbccb6a54a244bc0adc95c0b83375edc = L.marker(
                [-28.684339100000003, -49.36767700483055],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_af844f3a04f640ecb85f787afd55544a = L.popup({"maxWidth": "100%"});

        
            var html_eedb056ea29b4becb0b66bff1b1af358 = $(`<div id="html_eedb056ea29b4becb0b66bff1b1af358" style="width: 100.0%; height: 100.0%;">Heriberto Hülse<br><br>Capacidade: 19900</div>`)[0];
            popup_af844f3a04f640ecb85f787afd55544a.setContent(html_eedb056ea29b4becb0b66bff1b1af358);
        

        marker_bbccb6a54a244bc0adc95c0b83375edc.bindPopup(popup_af844f3a04f640ecb85f787afd55544a)
        ;

        
    
    
            var marker_a8866ac9256a4199977c4c323aeff218 = L.marker(
                [-27.58554625, -48.58646580892749],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_d22ba9c11217495d97d9908f92c1c6fd = L.popup({"maxWidth": "100%"});

        
            var html_d39c0c6b0fc446a2859aefa7b49160c9 = $(`<div id="html_d39c0c6b0fc446a2859aefa7b49160c9" style="width: 100.0%; height: 100.0%;">Orlando Scarpelli<br><br>Capacidade: 19584</div>`)[0];
            popup_d22ba9c11217495d97d9908f92c1c6fd.setContent(html_d39c0c6b0fc446a2859aefa7b49160c9);
        

        marker_a8866ac9256a4199977c4c323aeff218.bindPopup(popup_d22ba9c11217495d97d9908f92c1c6fd)
        ;

        
    
    
            var marker_93d59be491b84fe49ddd5e4c4f9d8cd8 = L.marker(
                [-25.439483199999998, -49.25581718514153],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_c836de065a994c9e80d9da438fd4be49 = L.popup({"maxWidth": "100%"});

        
            var html_cac4fb07eefc4598a502137f8fe3e7a3 = $(`<div id="html_cac4fb07eefc4598a502137f8fe3e7a3" style="width: 100.0%; height: 100.0%;">Vila Capanema<br><br>Capacidade: 17140</div>`)[0];
            popup_c836de065a994c9e80d9da438fd4be49.setContent(html_cac4fb07eefc4598a502137f8fe3e7a3);
        

        marker_93d59be491b84fe49ddd5e4c4f9d8cd8.bindPopup(popup_c836de065a994c9e80d9da438fd4be49)
        ;

        
    
    
            var marker_391a5a6c19cc4420b82f5d0508c117ea = L.marker(
                [-23.41415195, -51.93803540038412],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_9407d86addad40b8bbc3d11960e01c79 = L.popup({"maxWidth": "100%"});

        
            var html_856a926c57b7464ba35f9a7c77db076a = $(`<div id="html_856a926c57b7464ba35f9a7c77db076a" style="width: 100.0%; height: 100.0%;">Willie Davids<br><br>Capacidade: 16226</div>`)[0];
            popup_9407d86addad40b8bbc3d11960e01c79.setContent(html_856a926c57b7464ba35f9a7c77db076a);
        

        marker_391a5a6c19cc4420b82f5d0508c117ea.bindPopup(popup_9407d86addad40b8bbc3d11960e01c79)
        ;

        
    
    
            var marker_0359f5fe82e4491bbebfad05a68d682e = L.marker(
                [-27.10409255, -52.60698180721067],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_c360e9d1811b4bb5a044a91bbdbafa7a = L.popup({"maxWidth": "100%"});

        
            var html_033dfe8a71aa424d86adb6c63c681e7d = $(`<div id="html_033dfe8a71aa424d86adb6c63c681e7d" style="width: 100.0%; height: 100.0%;">Arena Condá<br><br>Capacidade: 15765</div>`)[0];
            popup_c360e9d1811b4bb5a044a91bbdbafa7a.setContent(html_033dfe8a71aa424d86adb6c63c681e7d);
        

        marker_0359f5fe82e4491bbebfad05a68d682e.bindPopup(popup_c360e9d1811b4bb5a044a91bbdbafa7a)
        ;

        
    
    
            var marker_95d4f4f1fe384528b2b0607aad70863e = L.marker(
                [-31.761068299999998, -52.33606216950615],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_0cf8b920dfda47b1bc721ffc398568ba = L.popup({"maxWidth": "100%"});

        
            var html_34c0540205154b04a09176cc12add902 = $(`<div id="html_34c0540205154b04a09176cc12add902" style="width: 100.0%; height: 100.0%;">Boca do Lobo<br><br>Capacidade: 15478</div>`)[0];
            popup_0cf8b920dfda47b1bc721ffc398568ba.setContent(html_34c0540205154b04a09176cc12add902);
        

        marker_95d4f4f1fe384528b2b0607aad70863e.bindPopup(popup_0cf8b920dfda47b1bc721ffc398568ba)
        ;

        
    
    
            var marker_fe4f11ba9aab4d4a9afcf19c02c51e9f = L.marker(
                [-28.28263935, -52.376390700313806],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_1b30492a1aa64a9cbe23cbd2a633f147 = L.popup({"maxWidth": "100%"});

        
            var html_e1006e9415f64e469fa028a369118c6e = $(`<div id="html_e1006e9415f64e469fa028a369118c6e" style="width: 100.0%; height: 100.0%;">Vermelhão da Serra<br><br>Capacidade: 15000</div>`)[0];
            popup_1b30492a1aa64a9cbe23cbd2a633f147.setContent(html_e1006e9415f64e469fa028a369118c6e);
        

        marker_fe4f11ba9aab4d4a9afcf19c02c51e9f.bindPopup(popup_1b30492a1aa64a9cbe23cbd2a633f147)
        ;

        
    
    
            var marker_5492aa905d5748229024f95468972361 = L.marker(
                [-29.1536159, -51.53660925529764],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_193923d03b6f4dc18098ac4eb9df03c1 = L.popup({"maxWidth": "100%"});

        
            var html_878c8dcde8954a82aaad96cad8104109 = $(`<div id="html_878c8dcde8954a82aaad96cad8104109" style="width: 100.0%; height: 100.0%;">Montanha dos Vinhedos<br><br>Capacidade: 12859</div>`)[0];
            popup_193923d03b6f4dc18098ac4eb9df03c1.setContent(html_878c8dcde8954a82aaad96cad8104109);
        

        marker_5492aa905d5748229024f95468972361.bindPopup(popup_193923d03b6f4dc18098ac4eb9df03c1)
        ;

        
    
    
            var marker_1447a4f94e904b62a2a6929973f00500 = L.marker(
                [-25.116192400000003, -50.15657943685897],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_f83dd24a81d1477fb8e6704c5a99d549 = L.popup({"maxWidth": "100%"});

        
            var html_ea52c2cf5c904d8b99054ae9f4dbd380 = $(`<div id="html_ea52c2cf5c904d8b99054ae9f4dbd380" style="width: 100.0%; height: 100.0%;">Germano Krüger<br><br>Capacidade: 10632</div>`)[0];
            popup_f83dd24a81d1477fb8e6704c5a99d549.setContent(html_ea52c2cf5c904d8b99054ae9f4dbd380);
        

        marker_1447a4f94e904b62a2a6929973f00500.bindPopup(popup_f83dd24a81d1477fb8e6704c5a99d549)
        ;

        
    
    
            var marker_7354ccc39fd742dc82d97c988524da29 = L.marker(
                [-30.0654898, -51.23491778159686],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_163c2517606a4ce2852d6804d29d4e2a = L.popup({"maxWidth": "100%"});

        
            var html_15c7f93977e642f2bc0e7030c8a02905 = $(`<div id="html_15c7f93977e642f2bc0e7030c8a02905" style="width: 100.0%; height: 100.0%;">Beira-Rio<br><br>Capacidade: 50128</div>`)[0];
            popup_163c2517606a4ce2852d6804d29d4e2a.setContent(html_15c7f93977e642f2bc0e7030c8a02905);
        

        marker_7354ccc39fd742dc82d97c988524da29.bindPopup(popup_163c2517606a4ce2852d6804d29d4e2a)
        ;

        
    
    
            var marker_9f5fec7483db436db6eb3f7b13a06b40 = L.marker(
                [-25.4484176, -49.27685626521088],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_a2ceac6c63c1418cb1df80fc3356f143 = L.popup({"maxWidth": "100%"});

        
            var html_bf4e7d0e9e844f8f8936392cd92ef992 = $(`<div id="html_bf4e7d0e9e844f8f8936392cd92ef992" style="width: 100.0%; height: 100.0%;">Arena da Baixada<br><br>Capacidade: 42372</div>`)[0];
            popup_a2ceac6c63c1418cb1df80fc3356f143.setContent(html_bf4e7d0e9e844f8f8936392cd92ef992);
        

        marker_9f5fec7483db436db6eb3f7b13a06b40.bindPopup(popup_a2ceac6c63c1418cb1df80fc3356f143)
        ;

        
    
    
            var marker_127d708e57f14f65a856d4e766927033 = L.marker(
                [-25.421417650000002, -49.25972893497825],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_0d8125ee1dfb4274a42e5645f066f1d5 = L.popup({"maxWidth": "100%"});

        
            var html_22414c8f0f2d4379b22f946b5a7dbe29 = $(`<div id="html_22414c8f0f2d4379b22f946b5a7dbe29" style="width: 100.0%; height: 100.0%;">Couto Pereira<br><br>Capacidade: 40501</div>`)[0];
            popup_0d8125ee1dfb4274a42e5645f066f1d5.setContent(html_22414c8f0f2d4379b22f946b5a7dbe29);
        

        marker_127d708e57f14f65a856d4e766927033.bindPopup(popup_0d8125ee1dfb4274a42e5645f066f1d5)
        ;

        
    
    
            var marker_0aecb057d7d6441d8a29f50b61578f05 = L.marker(
                [-23.283655, -51.1642694],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_02a7e3bb52be4db988989d6804497d19 = L.popup({"maxWidth": "100%"});

        
            var html_19dca0363991439c9a72634bfd91149c = $(`<div id="html_19dca0363991439c9a72634bfd91149c" style="width: 100.0%; height: 100.0%;">Estádio do Café<br><br>Capacidade: 30000</div>`)[0];
            popup_02a7e3bb52be4db988989d6804497d19.setContent(html_19dca0363991439c9a72634bfd91149c);
        

        marker_0aecb057d7d6441d8a29f50b61578f05.bindPopup(popup_02a7e3bb52be4db988989d6804497d19)
        ;

        
    
    
            var marker_c593615bea81421e906d1b73a1547372 = L.marker(
                [-24.9712386, -53.5060716],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_02792203d3554ea6b06799061cf78bde = L.popup({"maxWidth": "100%"});

        
            var html_6f39b6eb7cb042eeabcd04a17f0655b5 = $(`<div id="html_6f39b6eb7cb042eeabcd04a17f0655b5" style="width: 100.0%; height: 100.0%;">Regional Arnaldo Busatto<br><br>Capacidade: 25000</div>`)[0];
            popup_02792203d3554ea6b06799061cf78bde.setContent(html_6f39b6eb7cb042eeabcd04a17f0655b5);
        

        marker_c593615bea81421e906d1b73a1547372.bindPopup(popup_02792203d3554ea6b06799061cf78bde)
        ;

        
    
    
            var marker_490203d77d6d4086aba6ac84170dee51 = L.marker(
                [-29.1670064, -51.1977841],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_60a2741deb234f6e80396ea2ba24378d = L.popup({"maxWidth": "100%"});

        
            var html_42b28b944bcb4ccc8b67d4a640506ff1 = $(`<div id="html_42b28b944bcb4ccc8b67d4a640506ff1" style="width: 100.0%; height: 100.0%;">Centenário<br><br>Capacidade: 22131</div>`)[0];
            popup_60a2741deb234f6e80396ea2ba24378d.setContent(html_42b28b944bcb4ccc8b67d4a640506ff1);
        

        marker_490203d77d6d4086aba6ac84170dee51.bindPopup(popup_60a2741deb234f6e80396ea2ba24378d)
        ;

        
    
    
            var marker_b6b4aba6701c45ff8b2ec1423837ab90 = L.marker(
                [-27.6640339, -48.5386679],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_deeba8579b964e098c77b19a2bbf53cc = L.popup({"maxWidth": "100%"});

        
            var html_74e04706f06a4f4a9122c3491be589c2 = $(`<div id="html_74e04706f06a4f4a9122c3491be589c2" style="width: 100.0%; height: 100.0%;">Ressacada<br><br>Capacidade: 17826</div>`)[0];
            popup_deeba8579b964e098c77b19a2bbf53cc.setContent(html_74e04706f06a4f4a9122c3491be589c2);
        

        marker_b6b4aba6701c45ff8b2ec1423837ab90.bindPopup(popup_deeba8579b964e098c77b19a2bbf53cc)
        ;

        
    
    
            var marker_6b0874f26e9c4c39aba878d23b4d3423 = L.marker(
                [-24.725387, -53.7542582],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_8b7f586880564e21ad4d7a24359c2aac = L.popup({"maxWidth": "100%"});

        
            var html_e814539149674332a2476f6f2228b711 = $(`<div id="html_e814539149674332a2476f6f2228b711" style="width: 100.0%; height: 100.0%;">14 de Dezembro<br><br>Capacidade: 12500</div>`)[0];
            popup_8b7f586880564e21ad4d7a24359c2aac.setContent(html_e814539149674332a2476f6f2228b711);
        

        marker_6b0874f26e9c4c39aba878d23b4d3423.bindPopup(popup_8b7f586880564e21ad4d7a24359c2aac)
        ;

        
    
    
            var marker_f052642152d942dd85dc9ff7cf2b5a6c = L.marker(
                [-25.5230817, -49.2320156],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_4731ef67f86e41c1a8ec0b39be8c850c = L.popup({"maxWidth": "100%"});

        
            var html_418758f40aaf4fc7a319e27931a935cb = $(`<div id="html_418758f40aaf4fc7a319e27931a935cb" style="width: 100.0%; height: 100.0%;">Érton Coelho Queiroz<br><br>Capacidade: 10000</div>`)[0];
            popup_4731ef67f86e41c1a8ec0b39be8c850c.setContent(html_418758f40aaf4fc7a319e27931a935cb);
        

        marker_f052642152d942dd85dc9ff7cf2b5a6c.bindPopup(popup_4731ef67f86e41c1a8ec0b39be8c850c)
        ;

        
    
    
            var marker_07130fd2a707403ca66e7c8e209d2e8e = L.marker(
                [-29.9103393, -51.1656685],
                {}
            ).addTo(map_7cd24502863849108046db94f05d8b7e);
        
    
        var popup_61ee7a90c5074871be82f2a1753cc00e = L.popup({"maxWidth": "100%"});

        
            var html_3c5d4818de384591b5a8496ee169a922 = $(`<div id="html_3c5d4818de384591b5a8496ee169a922" style="width: 100.0%; height: 100.0%;">Complexo Esportivo da Ulbra<br><br>Capacidade: 10000</div>`)[0];
            popup_61ee7a90c5074871be82f2a1753cc00e.setContent(html_3c5d4818de384591b5a8496ee169a922);
        

        marker_07130fd2a707403ca66e7c8e209d2e8e.bindPopup(popup_61ee7a90c5074871be82f2a1753cc00e)
        ;

        
    
</script>](https://eduardovirtuoso.github.io/V-MAPS/)
