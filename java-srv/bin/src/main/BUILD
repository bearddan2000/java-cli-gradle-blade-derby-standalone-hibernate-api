java_binary (
    name = "BazelApp",
    srcs = glob(["java/**/*.java"]),
    main_class = "example.Main",
    deps = [
      "@maven//:org_apache_derby_derbyclient",
        "@maven//:com_google_code_gson_gson",
        "@maven//:org_hibernate_hibernate_core",
        "@maven//:javax_persistence_javax_persistence_api",
        "@maven//:jakarta_xml_bind_jakarta_xml_bind_api",
        "@maven//:org_glassfish_jaxb_jaxb_runtime",
        "@maven//:org_apache_commons_commons_lang3",
        "@maven//:org_webjars_bootstrap",
        "@maven//:com_bladejava_blade_mvc"
    ],
    resources = [
      "resources/log4j.xml",
      "resources/hibernate.cfg.xml",
    ],
)
