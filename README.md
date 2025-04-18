# MediSync Microservices

This repository contains the main repository for the MediSync project, which integrates four microservices as submodules:

1. **AppointmentService**
2. **DoctorService**
3. **FeedbackService**
4. **AuthenticationService**

Each service is maintained in its own repository and added here as a submodule.

## Steps to Clone and Initialize the Repository

Follow these steps to set up the project from scratch:

### 1. Clone the Main Repository
```bash
git clone https://github.com/TechVisionaries/MediSync.git
cd MediSync
```

### 2. Initialize and Update Submodules
To fetch the content of all submodules, run:
```bash
git submodule update --init --recursive
```

If you only want to fetch a specific submodule (e.g., `AppointmentService`), run:
```bash
git submodule update --init AppointmentService
```

### 3. Navigate to a Specific Service
To work on a specific service, navigate to its directory. For example:
```bash
cd AppointmentService
```

After navigating, follow the `README.md` file in that specific service's directory for further instructions.

## Notes
- Ensure you have `git` and `npm` installed on your system.
- For any issues, refer to the documentation or contact the maintainers.