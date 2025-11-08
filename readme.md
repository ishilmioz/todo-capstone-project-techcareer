# Todo Capstone Project Techcareer


Sunum için: https://www.canva.com/design/DAFtJnUzNr8/tAOZPMeFiPfS9Ai_yUMEMg/edit?utm_content=DAFtJnUzNr8&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

Kullanıcıların görevlerini yönetmelerine, düzenlemelerine ve silmelerine izin veren kapsamlı bir **Todo** uygulaması.

**İÇİNDEKİLER**
____________________

**BACKEND**

- Model
  
- Repository

- Service

- Controller

- Configuration

**FRONTEND (REACT JS)**

- App Component

- TaskList Component

- Additional Components

____________________

**PROJEYİ ÇALIŞTIRMA**

- Repository clone: https://github.com/ishilmioz/todo-capstone-project-techcareer.git
- cd techcareer_toDoCapstone
______________________
  
**BACKEND KATMANLARI**

Backend Spring Boot kullanılarak geliştirilmiştir.

- **Model (Entity):** ID, Name ve Completion statuslarla beraber Task Entiysini temsil eder.

- **Repository:** Extends JpaRepository. CRUD işlemleri için gerekli. findByCompleted() gibi özel sorgu metotlarını içerir.

- **Service:** Projenin iş mantığının yer aldığı katmandır. getAllTasks(), saveTask() gibi operasyonları yönetir.

- **Controller:** Gelen API isteklerini yönetir, yanıtları geri gönderir. Task oluşturma, düzenleme, silme endpointlerini içerir.

- **Configuration:** localhost:3000 üzerinde çalışan frontend'den gelen isteklere izin vermek için CORS ayarlarını yapar.
______________________

**FRONTEND**

Frontend React kullanılarak geliştirilmiştir.

**App.js**

- Uygulamayı yöneten merkezi bileşen

- Task ekleme, değiştirme, silme gibi özellikleri uygular.

- HTTP istekleri için axios kullanarak backendle entegre olur.

**TaskList.js**

- Tüm görevleri listeler, kullanıcılara her görevi değiştirme, düzenleme veya silme olanağı tanır.

- Listede doğrudan görev düzenlemek için etkileşimli bir kullanıcı arayüzü sunar.

**Diğer ek bileşenler:**

- **TaskInput:** Yeni görev eklemek için bileşen.

- **FilterButtons:** Tamamlanma durumlarına göre görev filtrelemeyi sağlar.

- **DeleteButtons:** Toplu silme işlemleri için düğmeleri sağlar.

______________________

**TESTING**

Backend'de API'ye istekler göndermek ve yanıtları doğrulamak için Postman kullanın.

______________________


**Todo Capstone Project Techcareer**

For presentation: https://www.canva.com/design/DAFtJnUzNr8/tAOZPMeFiPfS9Ai_yUMEMg/edit?utm_content=DAFtJnUzNr8&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

A comprehensive **Todo** application that allows users to manage, edit, and delete their tasks.

**CONTENTS**
____________________

**BACKEND**

- Model

- Repository

- Service

- Controller

- Configuration

**FRONTEND (REACT JS)**

- App Component

- TaskList Component

- Additional Components
____________________

**RUNNING THE PROJECT**

- Repository clone: https://github.com/ishilmioz/todo-capstone-project-techcareer.git
- cd techcareer_toDoCapstone

____________________

**BACKEND LAYERS**

The backend was developed using Spring Boot.

- **Model (Entity):** Represents the Task Entity with ID, Name and Completion statuses.

- **Repository:** Extends JpaRepository. Required for CRUD operations. Contains custom query methods such as findByCompleted().

- **Service:** The layer where the business logic of the project is placed. Manages operations such as getAllTasks(), saveTask() etc.

- **Controller:** Handles incoming API requests and returns responses. Includes endpoints for creating, editing, deleting tasks.

- **Configuration:** Configures CORS to allow requests coming from the frontend running on localhost:3000.

**FRONTEND**

The frontend was developed using React.

**App.js**

- The central component that manages the application

- Implements features such as adding, editing, deleting tasks.

- Integrates with the backend using axios for HTTP requests.

**TaskList.js**

- Lists all tasks and allows users to modify, edit, or delete each task.

- Provides an interactive user interface to edit tasks directly in the list.

**Other additional components:**

- **TaskInput:** Component for adding new tasks.

- **FilterButtons:** Allows filtering tasks based on completion statuses.

- **DeleteButtons:** Provides buttons for bulk delete operations.
  
______________________

**TESTING**

Use Postman to send requests to the backend API and validate responses.



