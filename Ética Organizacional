import streamlit as st

# Configuración de la página
st.set_page_config(
    page_title="Dashboard: IA en Psicología Organizacional",
    page_icon="🧠",
    layout="wide"
)

# Estilos personalizados para mejorar la estética
st.markdown("""
    <style>
    .main {
        background-color: #f8f9fa;
    }
    .stAlert {
        border-radius: 15px;
    }
    h1 {
        color: #1E3A8A;
    }
    h2 {
        color: #2563EB;
        border-bottom: 2px solid #E5E7EB;
        padding-bottom: 10px;
    }
    </style>
    """, unsafe_allow_html=True)

# --- NAVEGACIÓN LATERAL ---
with st.sidebar:
    st.image("https://www.uady.mx/sites/default/files/logo-uady.png", width=150) # Logo genérico UADY
    st.title("Navegación")
    seccion = st.radio(
        "Selecciona una sección:",
        ["Portada", "Automatización y Eficiencia", "Desafíos Éticos", "IA Generativa", "Reflexión Final", "Referencias"]
    )
    
    st.divider()
    st.info(f"**Autora:**\n\nSuárez Robertos Karla Gabriela [cite: 3]")
    st.caption("Fecha: 12 de febrero del 2026 [cite: 4]")

# --- SECCIÓN: PORTADA ---
if seccion == "Portada":
    st.title("MARCO TEÓRICO: USO ÉTICO DE LA IA EN PSICOLOGÍA ORGANIZACIONAL [cite: 5]")
    st.subheader("Facultad de Psicología UADY [cite: 1]")
    
    col1, col2 = st.columns([2, 1])
    
    with col1:
        st.markdown("""
        La integración de la Inteligencia Artificial (IA) en las organizaciones ha dejado de ser una tendencia emergente para convertirse en un componente estructural de la competitividad contemporánea[cite: 6]. 
        
        En la Gestión de Recursos Humanos (GRH), la IA transforma:
        * **Eficiencia operativa.** [cite: 7]
        * **Toma de decisiones estratégicas.** [cite: 7]
        * **Análisis crítico de desafíos éticos.** [cite: 8]
        """)
    
    with col2:
        st.success("**Ejes de Análisis:**\n1. Automatización\n2. Riesgos Éticos\n3. Factor Humano [cite: 9]")

# --- SECCIÓN: AUTOMATIZACIÓN ---
elif seccion == "Automatización y Eficiencia":
    st.header("2. Automatización y Eficiencia en los Procesos de GRH [cite: 11]")
    
    col_a, col_b = st.columns(2)
    
    with col_a:
        st.subheader("Optimización de Procesos")
        st.write("Permite automatizar tareas repetitivas como el cribado de currículos y programación de entrevistas[cite: 13].")
        st.write("Esto libera a los profesionales de RR.HH. para actividades estratégicas de desarrollo de talento[cite: 14].")
        
    with col_b:
        st.subheader("Analítica Predictiva")
        st.info("Yawson (2024) señala que analizar grandes volúmenes de datos permite prever la rotación de personal y necesidades de capacitación[cite: 16].")

    st.warning("**Nota importante:** La implementación es un 'mixed bag' (bolsa mixta) de ventajas y limitaciones técnicas[cite: 18, 19].")

# --- SECCIÓN: ÉTICA ---
elif seccion == "Desafíos Éticos":
    st.header("3. Desafíos Éticos: Sesgo, Explicabilidad y Privacidad [cite: 20]")
    
    tab1, tab2, tab3 = st.tabs(["Sesgo Algorítmico", "Explicabilidad (XAI)", "Privacidad"])
    
    with tab1:
        st.error("Los sistemas entrenados con datos históricos pueden reproducir prejuicios estructurales en selección y promoción[cite: 22].")
        
    with tab2:
        st.write("La **Explainable AI (XAI)** permite la detección y supervisión de sesgos en sistemas automatizados[cite: 24].")
        st.caption("Esto fomenta la transparencia y confianza del candidato[cite: 25].")
        
    with tab3:
        st.write("La recopilación masiva plantea desafíos regulatorios (como el GDPR) y éticos[cite: 27].")
        st.write("La 'caja negra' algorítmica puede erosionar la legitimidad institucional[cite: 28].")

# --- SECCIÓN: IA GENERATIVA ---
elif seccion == "IA Generativa":
    st.header("4. IA Generativa y el Factor Humano [cite: 29]")
    
    st.markdown("""
    La IA generativa optimiza la redacción de descripciones de puestos y comunicación, pero presenta riesgos de **desinformación**[cite: 31, 32].
    """)
    
    st.divider()
    
    c1, c2 = st.columns(2)
    with c1:
        st.subheader("Lo que la IA aporta")
        st.write("- Soporte analítico [cite: 34]")
        st.write("- Fortalecimiento de investigación [cite: 33]")
    with c2:
        st.subheader("Lo que el Humano aporta")
        st.write("- Empatía y juicio ético [cite: 33]")
        st.write("- Responsabilidad decisional final [cite: 35]")

# --- SECCIÓN: REFLEXIÓN ---
elif seccion == "Reflexión Final":
    st.header("5. Reflexión Personal [cite: 37]")
    
    st.chat_message("user").write("**¿Cómo percibiste las capacidades de la IA para apoyar la elaboración de textos académicos?** [cite: 38]")
    
    st.write("La IA demostró ser eficaz para estructurar, organizar y reformular información con claridad[cite: 39].")
    
    with st.expander("Ver ventajas e inconvenientes identificados"):
        st.markdown("""
        * **Ventajas:** Sintetizar múltiples fuentes y mantener consistencia de estilo[cite: 40].
        * **Limitaciones:** No sustituye el criterio crítico ni la interpretación profunda del investigador[cite: 41].
        * **Conclusión:** La validación académica y responsabilidad intelectual siguen siendo tareas humanas fundamentales[cite: 43].
        """)

# --- SECCIÓN: REFERENCIAS ---
elif seccion == "Referencias":
    st.header("6. Referencias Bibliográficas [cite: 44]")
    referencias = [
        "Albaroudi, A., Mansouri, H., & Alameer, R. (2024). IRE Journals. [cite: 45, 46]",
        "Chávez-Betancourt, R., et al. (2024). GADE: Revista Científica. [cite: 47, 48]",
        "David, R. (2023). Ethical Role of Generative AI. [cite: 49]",
        "Ghosh, S., et al. (2024). Human Resource Development International. [cite: 50, 51]",
        "Malik, N., et al. (2023). Journal of Business Research. [cite: 52]",
        "Ncube, S. (2024). SA Journal of Human Resource Management. [cite: 53, 54]",
        "Nicholas, V., & Umarani, C. (2025). SSRN. [cite: 55]",
        "Radonjic, A., et al. (2024). Int. Journal of Productivity and Performance Management. [cite: 56, 57]",
        "Rane, N., et al. (2023). Explainable AI (XAI). [cite: 58]",
        "Yawson, R. (2024). HRM Review. [cite: 59]"
    ]
    for ref in referencias:
        st.text(ref)

# --- PIE DE PÁGINA ---
st.divider()
st.caption("Dashboard desarrollado para el ADA 5 - Herramientas de IA [cite: 2]")
