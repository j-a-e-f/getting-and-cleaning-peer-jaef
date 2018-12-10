From the data authors: The dataset includes the following files: =========================================

-   'README.txt'

-   'features\_info.txt': Shows information about the variables used on the feature vector.

-   'features.txt': List of all features.

-   'activity\_labels.txt': Links the class labels with their activity name.

-   'train/X\_train.txt': Training set.

-   'train/y\_train.txt': Training labels.

-   'test/X\_test.txt': Test set.

-   'test/y\_test.txt': Test labels.

The following files are available for the train and test data. Their descriptions are equivalent.

-   'train/subject\_train.txt': Each row identifies the subject who performed the activity for each window sample. Its range is from 1 to 30.

-   'train/Inertial Signals/total\_acc\_x\_train.txt': The acceleration signal from the smartphone accelerometer X axis in standard gravity units 'g'. Every row shows a 128 element vector. The same description applies for the 'total\_acc\_x\_train.txt' and 'total\_acc\_z\_train.txt' files for the Y and Z axis.

-   'train/Inertial Signals/body\_acc\_x\_train.txt': The body acceleration signal obtained by subtracting the gravity from the total acceleration.

-   'train/Inertial Signals/body\_gyro\_x\_train.txt': The angular velocity vector measured by the gyroscope for each window sample. The units are radians/second.

------------------------------------------------------------------------

After modification with the `run_analysis.R` script, new variables are created:

#### Subject

The id number of a subject, ranges from 1-30

#### A series of measurement columns

These columns were cleaned, with special characters removed and more descriptive titles given.

#### Activity

Ranges from walking, sitting, standing, laying, and walking up or down stairs.

This CodeBook files goes alongside the `run_analysis.R` script and README found in the repository
