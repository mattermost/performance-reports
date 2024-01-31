### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| FileInfoStore.Search | avg | 0s | 18ms | 18ms | 528634.36
| SessionStore.GetSessionsExpired | avg | 2ms | 16ms | 14ms | 705.73
| TeamStore.AnalyticsTeamCount | avg | 2ms | 5ms | 3ms | 166.92
| JobStore.GetCountByStatusAndType | avg | 4ms | 9ms | 5ms | 125.95
| UserStore.GetProfilesInChannel | avg | 5ms | 10ms | 5ms | 105.62
| ChannelStore.Get | avg | 3ms | 6ms | 3ms | 97.14
| DraftStore.GetDraftsForUser | avg | 2ms | 4ms | 2ms | 91.91
| SystemStore.PermanentDeleteByName | avg | 2ms | 4ms | 2ms | 88.52
| ChannelStore.GetChannelsByUser | avg | 12ms | 22ms | 10ms | 80.26
| ChannelStore.UpdateSidebarCategories | avg | 25ms | 44ms | 19ms | 75.52
| TeamStore.GetTeamsByUserId | avg | 5ms | 8ms | 3ms | 57.73
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 16ms | 25ms | 9ms | 54.86
| ThreadStore.GetTotalUnreadMentions | avg | 4ms | 6ms | 2ms | 45.31
| ThreadStore.GetTotalThreads | avg | 4ms | 6ms | 2ms | 44.94
| ThreadStore.GetTotalUnreadThreads | avg | 4ms | 6ms | 2ms | 44.74
| ThreadStore.GetTotalUnreadUrgentMentions | avg | 5ms | 7ms | 2ms | 44.13
| JobStore.GetNewestJobByStatusesAndType | avg | 5ms | 7ms | 2ms | 42.87
| ChannelStore.AnalyticsTypeCount | avg | 5ms | 7ms | 2ms | 39.62
| TeamStore.GetAllPage | avg | 5ms | 7ms | 2ms | 39.40
| UserStore.GetUnreadCount | avg | 5ms | 7ms | 2ms | 39.25
| TeamStore.GetChannelUnreadsForAllTeams | avg | 5ms | 7ms | 2ms | 39.14
| GroupStore.GetByName | avg | 5ms | 7ms | 2ms | 36.54
| ChannelStore.GetAllChannelMemberIdsByChannelId | avg | 11ms | 15ms | 4ms | 36.15
| ThreadStore.GetTeamsUnreadForUser | avg | 6ms | 8ms | 2ms | 35.75
| ChannelStore.GetGuestCount | avg | 6ms | 8ms | 2ms | 32.12
| ChannelStore.GetPublicChannelsForTeam | avg | 11ms | 13ms | 2ms | 17.53
| ChannelStore.SaveMember | avg | 40ms | 47ms | 7ms | 17.48
| ChannelStore.CreateInitialSidebarCategories | avg | 17ms | 19ms | 2ms | 11.72
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| SessionStore.GetSessionsExpired | p99 | 5ms | 97ms | 92ms | 1858.59
| JobStore.Get | p99 | 5ms | 68ms | 63ms | 1272.73
| TeamStore.AnalyticsTeamCount | p99 | 5ms | 48ms | 43ms | 868.37
| RoleStore.ChannelHigherScopedPermissions | p99 | 5ms | 40ms | 35ms | 706.78
| ChannelStore.GetAllChannelMemberIdsByChannelId | p99 | 25ms | 178ms | 153ms | 615.09
| LinkMetadataStore.Get | p99 | 5ms | 31ms | 26ms | 520.24
| PostStore.GetSingle | p99 | 5ms | 28ms | 23ms | 460.23
| JobStore.GetCountByStatusAndType | p99 | 62ms | 335ms | 273ms | 440.32
| ComplianceStore.MessageExport | p99 | 5ms | 26ms | 21ms | 420.08
| FileInfoStore.Search | p99 | 5ms | 25ms | 20ms | 404.04
| ChannelStore.AnalyticsTypeCount | p99 | 10ms | 47ms | 37ms | 374.27
| SessionStore.Remove | p99 | 5ms | 23ms | 18ms | 363.64
| JobStore.UpdateStatusOptimistically | p99 | 9ms | 39ms | 30ms | 337.08
| PostPersistentNotificationStore.Get | p99 | 5ms | 21ms | 16ms | 323.23
| UserStore.GetProfilesInChannel | p99 | 47ms | 195ms | 148ms | 315.24
| UserStore.GetUnreadCount | p99 | 46ms | 146ms | 100ms | 218.33
| ChannelStore.Get | p99 | 44ms | 133ms | 89ms | 204.07
| ThreadStore.GetThreadForUser | p99 | 32ms | 90ms | 58ms | 181.12
| TeamStore.GetByName | p99 | 14ms | 37ms | 23ms | 167.90
| TeamStore.Get | p99 | 18ms | 47ms | 29ms | 160.59
| ChannelStore.GetPublicChannelsForTeam | p99 | 104ms | 267ms | 163ms | 156.87
| ChannelStore.UpdateSidebarCategories | p99 | 94ms | 238ms | 144ms | 153.61
| PostPriorityStore.GetForPost | p99 | 27ms | 63ms | 36ms | 135.85
| ThreadStore.GetTeamsUnreadForUser | p99 | 75ms | 155ms | 80ms | 106.16
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 73ms | 149ms | 76ms | 104.44
| ThreadStore.GetThreadUnreadReplyCount | p99 | 18ms | 36ms | 18ms | 101.64
| DraftStore.GetDraftsForUser | p99 | 5ms | 10ms | 5ms | 101.01
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 18ms | 35ms | 17ms | 93.10
| ReactionStore.GetForPost | p99 | 24ms | 46ms | 22ms | 91.24
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 224ms | 427ms | 203ms | 90.60
| ChannelStore.CreateInitialSidebarCategories | p99 | 96ms | 182ms | 86ms | 89.72
| JobStore.GetNewestJobByStatusesAndType | p99 | 89ms | 167ms | 78ms | 87.64
| ChannelStore.GetGuestCount | p99 | 101ms | 187ms | 86ms | 85.04
| TeamStore.GetTeamsByUserId | p99 | 83ms | 153ms | 70ms | 84.06
| PostPersistentNotificationStore.GetSingle | p99 | 34ms | 62ms | 28ms | 82.28
| PostPersistentNotificationStore.DeleteExpired | p99 | 5ms | 9ms | 4ms | 80.81
| PluginStore.List | p99 | 5ms | 9ms | 4ms | 80.81
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 77ms | 139ms | 62ms | 80.03
| ThreadStore.GetMembershipForUser | p99 | 34ms | 61ms | 27ms | 79.97
| TeamStore.GetAllPage | p99 | 82ms | 147ms | 65ms | 78.96
| SessionStore.Get | p99 | 97ms | 171ms | 74ms | 76.55
| ChannelStore.CreateDirectChannel | p99 | 97ms | 168ms | 71ms | 72.82
| UserStore.GetProfileByIds | p99 | 11ms | 19ms | 8ms | 72.41
| PluginStore.Get | p99 | 90ms | 155ms | 65ms | 71.96
| ChannelStore.GetPinnedPostCount | p99 | 48ms | 82ms | 34ms | 71.48
| ChannelStore.GetMembersForUser | p99 | 53ms | 91ms | 38ms | 71.26
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 67ms | 115ms | 48ms | 71.16
| PostStore.GetPosts | p99 | 82ms | 140ms | 58ms | 70.66
| ChannelStore.GetChannelsByUser | p99 | 161ms | 262ms | 101ms | 62.77
| GroupStore.GetByName | p99 | 90ms | 145ms | 55ms | 60.94
| UserStore.Get | p99 | 13ms | 21ms | 8ms | 59.56
| ThreadStore.GetTotalUnreadThreads | p99 | 66ms | 104ms | 38ms | 57.84
| ThreadStore.GetTotalThreads | p99 | 68ms | 107ms | 39ms | 57.72
| ThreadStore.GetThreadsForUser | p99 | 45ms | 71ms | 26ms | 57.45
| UserStore.Count | p99 | 248ms | 390ms | 142ms | 57.21
| PostAcknowledgementStore.GetForPosts | p99 | 41ms | 63ms | 22ms | 53.66
| UserTermsOfServiceStore.GetByUser | p99 | 95ms | 144ms | 49ms | 51.38
| UserStore.GetProfilesByUsernames | p99 | 35ms | 53ms | 18ms | 50.94
| PostStore.GetEtag | p99 | 84ms | 126ms | 42ms | 50.03
| WebhookStore.GetOutgoingByTeam | p99 | 39ms | 58ms | 19ms | 49.33
| ThreadStore.GetThreadFollowers | p99 | 43ms | 64ms | 21ms | 48.28
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 31ms | 46ms | 15ms | 48.26
| SessionStore.Save | p99 | 99ms | 146ms | 47ms | 47.29
| PostPriorityStore.GetForPosts | p99 | 45ms | 66ms | 21ms | 47.15
| ChannelStore.GetByName | p99 | 81ms | 119ms | 38ms | 46.92
| PostAcknowledgementStore.GetForPost | p99 | 28ms | 41ms | 13ms | 46.43
| StatusStore.GetByIds | p99 | 41ms | 60ms | 19ms | 45.90
| PostStore.GetPostsBefore | p99 | 46ms | 66ms | 20ms | 43.14
| PreferenceStore.GetAll | p99 | 119ms | 170ms | 51ms | 43.00
| GroupStore.GetGroups | p99 | 66ms | 94ms | 28ms | 42.26
| PreferenceStore.Get | p99 | 34ms | 48ms | 14ms | 40.93
| UserStore.GetForLogin | p99 | 99ms | 139ms | 40ms | 40.45
| ChannelStore.GetChannels | p99 | 66ms | 92ms | 26ms | 39.37
| ThreadStore.GetTotalUnreadMentions | p99 | 72ms | 100ms | 28ms | 38.93
| ChannelStore.SaveMember | p99 | 352ms | 488ms | 136ms | 38.62
| UserStore.GetAllProfiles | p99 | 69ms | 94ms | 25ms | 36.26
| PostStore.Get | p99 | 42ms | 57ms | 15ms | 35.87
| ReactionStore.GetUniqueCountForPost | p99 | 31ms | 42ms | 11ms | 35.31
| ReactionStore.ExistsOnPost | p99 | 36ms | 48ms | 12ms | 33.69
| ThreadStore.UpdateMembership | p99 | 6ms | 8ms | 2ms | 31.91
| UserStore.IsEmpty | p99 | 60ms | 77ms | 17ms | 28.45
| JobStore.GetAllByStatus | p99 | 47ms | 60ms | 13ms | 27.37
| TeamStore.GetTeamsForUser | p99 | 93ms | 116ms | 23ms | 24.76
| StatusStore.Get | p99 | 78ms | 97ms | 19ms | 24.40
| FileInfoStore.GetForPost | p99 | 15ms | 18ms | 3ms | 20.40
| PostStore.GetPostsByThread | p99 | 26ms | 31ms | 5ms | 19.24
| ChannelStore.AutocompleteInTeamForSearch | p99 | 637ms | 750ms | 113ms | 17.75
| PostStore.GetPostsSince | p99 | 79ms | 88ms | 9ms | 11.46
| PostStore.SearchPostsForUser | p99 | 1.575s | 1.755s | 180ms | 11.43
| UserStore.UpdateFailedPasswordAttempts | p99 | 18ms | 20ms | 2ms | 11.10
| ChannelStore.GetFileCount | p99 | 46ms | 51ms | 5ms | 10.84
| ChannelStore.GetMemberCount | p99 | 666ms | 724ms | 58ms | 8.71
| ChannelStore.Autocomplete | p99 | 4.928s | 4.988s | 60ms | 1.22
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ClusterDiscoveryStore.GetAll | avg | 2ms | 0s | -2ms | -133.32
| DraftStore.Upsert | avg | 3ms | 0s | -3ms | -106.27
| ChannelStore.GetByNameIncludeDeleted | avg | 2ms | 0s | -2ms | -101.72
| ChannelStore.GetMemberOnly | avg | 4ms | 0s | -4ms | -97.17
| DraftStore.Delete | avg | 3ms | 1ms | -2ms | -72.76
| PostStore.GetPostReminderMetadata | avg | 6ms | 2ms | -4ms | -69.76
| PostStore.AnalyticsPostCount | avg | 561ms | 177ms | -384ms | -68.46
| PreferenceStore.DeleteCategoryAndName | avg | 4ms | 2ms | -2ms | -55.65
| ChannelStore.GetTeamChannels | avg | 65ms | 38ms | -27ms | -41.64
| PluginStore.Get | avg | 8ms | 6ms | -2ms | -25.35
| ChannelMemberHistoryStore.GetUsersInChannelDuring | avg | 277ms | 261ms | -16ms | -5.79
| ChannelStore.GetMemberCount | avg | 146ms | 139ms | -7ms | -4.80
| UserStore.Search | avg | 89ms | 87ms | -2ms | -2.25
| ChannelStore.AutocompleteInTeamForSearch | avg | 123ms | 121ms | -2ms | -1.62
| UserStore.AutocompleteUsersInChannel | avg | 196ms | 193ms | -3ms | -1.53
| UserStore.AnalyticsActiveCount | avg | 211ms | 208ms | -3ms | -1.42
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ClusterDiscoveryStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| ChannelStore.GetByNameIncludeDeleted | p99 | 5ms | 0s | -5ms | -101.01
| ProductNoticesStore.ClearOldNotices | p99 | 5ms | 0s | -5ms | -101.01
| DraftStore.Upsert | p99 | 5ms | 0s | -5ms | -100.89
| ChannelStore.GetMemberOnly | p99 | 64ms | 0s | -64ms | -100.36
| PostStore.AnalyticsPostCount | p99 | 2.47s | 249ms | -2.221s | -89.91
| PostStore.GetPostReminderMetadata | p99 | 46ms | 5ms | -41ms | -89.62
| UserStore.GetByUsername | p99 | 51ms | 9ms | -42ms | -83.13
| PreferenceStore.DeleteCategoryAndName | p99 | 24ms | 5ms | -19ms | -80.34
| ChannelStore.GetTeamChannels | p99 | 244ms | 50ms | -194ms | -79.51
| PostStore.GetPostsAfter | p99 | 18ms | 8ms | -10ms | -55.25
| FileInfoStore.SetContent | p99 | 21ms | 10ms | -11ms | -52.79
| UserStore.GetMany | p99 | 10ms | 5ms | -5ms | -52.08
| StatusStore.UpdateExpiredDNDStatuses | p99 | 10ms | 5ms | -5ms | -51.39
| RetentionPolicyStore.GetCount | p99 | 10ms | 5ms | -5ms | -51.02
| RetentionPolicyStore.GetAll | p99 | 10ms | 5ms | -5ms | -50.76
| JobStore.UpdateStatus | p99 | 18ms | 9ms | -9ms | -48.91
| UserAccessTokenStore.GetByToken | p99 | 9ms | 5ms | -4ms | -45.68
| BotStore.Get | p99 | 9ms | 5ms | -4ms | -44.20
| JobStore.UpdateOptimistically | p99 | 8ms | 5ms | -3ms | -39.84
| ChannelStore.SearchGroupChannels | p99 | 36ms | 22ms | -14ms | -38.50
| FileInfoStore.AttachToPost | p99 | 16ms | 10ms | -6ms | -37.74
| PostStore.Update | p99 | 36ms | 25ms | -11ms | -30.24
| ClusterDiscoveryStore.SetLastPingAt | p99 | 19ms | 16ms | -3ms | -15.67
| UserStore.Search | p99 | 337ms | 292ms | -45ms | -13.34
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 72ms | 63ms | -9ms | -12.52
| ChannelStore.GetMemberForPost | p99 | 18ms | 16ms | -2ms | -11.13
| FileInfoStore.Get | p99 | 19ms | 17ms | -2ms | -10.47
| UserStore.AutocompleteUsersInChannel | p99 | 676ms | 618ms | -58ms | -8.59
| ProductNoticesStore.View | p99 | 94ms | 87ms | -7ms | -7.48
| ChannelStore.GetMembersForUserWithPagination | p99 | 91ms | 87ms | -4ms | -4.40
| UserStore.GetAllProfilesInChannel | p99 | 2.184s | 2.147s | -37ms | -1.69
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchFiles | avg | 2ms | 20ms | 18ms | 831.67
| getChannelsForUser | avg | 15ms | 28ms | 13ms | 86.04
| getFilteredUsersStats | avg | 30ms | 49ms | 19ms | 63.86
| getTeamsForUser | avg | 5ms | 8ms | 3ms | 57.00
| getSelfHostedProducts | avg | 21ms | 32ms | 11ms | 52.73
| getCategoriesForTeamForUser | avg | 17ms | 25ms | 8ms | 48.00
| getTeamsUnreadForUser | avg | 8ms | 12ms | 4ms | 47.37
| updateCategoriesForTeamForUser | avg | 35ms | 48ms | 13ms | 37.00
| getAnalytics | avg | 187ms | 249ms | 62ms | 33.14
| getPostsForChannelAroundLastUnread | avg | 41ms | 52ms | 11ms | 26.92
| getPreferences | avg | 8ms | 10ms | 2ms | 25.32
| getPostsForChannel | avg | 25ms | 30ms | 5ms | 20.22
| saveReaction | avg | 24ms | 27ms | 3ms | 12.56
| updateReadStateThreadByUser | avg | 26ms | 29ms | 3ms | 11.73
| createPost | avg | 372ms | 403ms | 31ms | 8.34
| getFilePreview | avg | 41ms | 44ms | 3ms | 7.26
| searchPostsInTeam | avg | 87ms | 93ms | 6ms | 6.87
| login | avg | 67ms | 69ms | 2ms | 2.98
| addTeamMember | avg | 1.25s | 1.283s | 33ms | 2.64
| createUser | avg | 96ms | 98ms | 2ms | 2.09
| uploadFileStream | avg | 419ms | 424ms | 5ms | 1.19
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| searchFiles | p99 | 5ms | 25ms | 20ms | 402.56
| getFilteredUsersStats | p99 | 50ms | 244ms | 194ms | 389.95
| getChannel | p99 | 26ms | 107ms | 81ms | 308.55
| getPublicChannelsForTeam | p99 | 104ms | 267ms | 163ms | 156.87
| updateCategoriesForTeamForUser | p99 | 94ms | 239ms | 145ms | 154.68
| followThreadByUser | p99 | 10ms | 24ms | 14ms | 140.66
| getSelfHostedProducts | p99 | 50ms | 98ms | 48ms | 96.97
| getChannelsForUser | p99 | 225ms | 430ms | 205ms | 91.31
| getCategoriesForTeamForUser | p99 | 225ms | 428ms | 203ms | 90.33
| getTeamsForUser | p99 | 83ms | 154ms | 71ms | 85.23
| updateReadStateThreadByUser | p99 | 95ms | 172ms | 77ms | 81.24
| getAllTeams | p99 | 86ms | 156ms | 70ms | 81.05
| getTeamsUnreadForUser | p99 | 125ms | 222ms | 97ms | 77.42
| getThreadsForUser | p99 | 51ms | 89ms | 38ms | 74.81
| getUser | p99 | 105ms | 175ms | 70ms | 66.80
| getChannelMember | p99 | 47ms | 75ms | 28ms | 59.85
| saveReaction | p99 | 217ms | 345ms | 128ms | 58.87
| getChannelMembersForTeamForUser | p99 | 61ms | 96ms | 35ms | 57.36
| getUsersByNames | p99 | 36ms | 54ms | 18ms | 50.68
| getUsers | p99 | 90ms | 134ms | 44ms | 48.66
| getPostsForChannel | p99 | 234ms | 338ms | 104ms | 44.46
| viewChannel | p99 | 86ms | 124ms | 38ms | 44.43
| getChannelsForTeamForUser | p99 | 84ms | 121ms | 37ms | 44.23
| updatePreferences | p99 | 10ms | 14ms | 4ms | 40.01
| createUser | p99 | 250ms | 347ms | 97ms | 38.86
| getPreferences | p99 | 124ms | 172ms | 48ms | 38.74
| getPostThread | p99 | 72ms | 98ms | 26ms | 36.22
| getPostsForChannelAroundLastUnread | p99 | 671ms | 884ms | 213ms | 31.74
| getTeamMembersForUser | p99 | 108ms | 140ms | 32ms | 29.50
| patchPost | p99 | 96ms | 118ms | 22ms | 23.04
| searchPostsInTeam | p99 | 1.575s | 1.89s | 315ms | 20.00
| autocompleteChannelsForTeamForSearch | p99 | 637ms | 750ms | 113ms | 17.75
| unfollowThreadByUser | p99 | 19ms | 21ms | 2ms | 10.44
| getFileThumbnail | p99 | 124ms | 135ms | 11ms | 8.87
| getFilePreview | p99 | 200ms | 216ms | 16ms | 7.99
| login | p99 | 392ms | 418ms | 26ms | 6.63
| createPost | p99 | 2.229s | 2.338s | 109ms | 4.89
| getChannelStats | p99 | 396ms | 409ms | 13ms | 3.28
| addTeamMember | p99 | 4.608s | 4.665s | 57ms | 1.24
| searchAllChannels | p99 | 4.928s | 4.988s | 60ms | 1.22
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| handleCheckCWSConnection | avg | 37ms | 0s | -37ms | -100.17
| setPostReminder | avg | 29ms | 14ms | -15ms | -51.42
| createChannel | avg | 65ms | 38ms | -27ms | -41.56
| getProfileImage | avg | 96ms | 65ms | -31ms | -32.26
| removeUserCustomStatus | avg | 169ms | 142ms | -27ms | -15.97
| getLicenseSelfServeStatus | avg | 181ms | 155ms | -26ms | -14.39
| patchPost | avg | 33ms | 29ms | -4ms | -12.21
| addChannelMember | avg | 234ms | 213ms | -21ms | -8.97
| getChannelMembersForUser | avg | 51ms | 47ms | -4ms | -7.91
| autocompleteUsers | avg | 158ms | 147ms | -11ms | -6.97
| searchUsers | avg | 91ms | 88ms | -3ms | -3.31
| createGroupChannel | avg | 342ms | 336ms | -6ms | -1.75
| autocompleteChannelsForTeamForSearch | avg | 123ms | 121ms | -2ms | -1.62
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| handleCheckCWSConnection | p99 | 50ms | 0s | -50ms | -100.50
| setPostReminder | p99 | 236ms | 25ms | -211ms | -89.22
| createChannel | p99 | 244ms | 50ms | -194ms | -79.51
| upsertDraft | p99 | 10ms | 5ms | -5ms | -50.76
| removeUserCustomStatus | p99 | 474ms | 248ms | -226ms | -47.73
| searchGroupChannels | p99 | 36ms | 22ms | -14ms | -38.50
| searchUsers | p99 | 349ms | 294ms | -55ms | -15.74
| autocompleteUsers | p99 | 517ms | 490ms | -27ms | -5.22
| addChannelMember | p99 | 500ms | 485ms | -15ms | -3.00
| getProfileImage | p99 | 463ms | 451ms | -12ms | -2.59
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 19ms | 1ms | 5.630
| BotStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -44.199
| ChannelMemberHistoryStore.GetUsersInChannelDuring |  Avg| 277ms| 261ms | -16ms | -5.786
| |  P99| 498ms| 496ms | -2ms | -0.402
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 16ms| 17ms | 1ms | 6.067
| ChannelStore.AnalyticsTypeCount |  Avg| 5ms| 7ms | 2ms | 39.618
| |  P99| 10ms| 47ms | 37ms | 374.268
| ChannelStore.Autocomplete |  Avg| 1.503s| 1.496s | -7ms | -0.466
| |  P99| 4.928s| 4.988s | 60ms | 1.218
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 123ms| 121ms | -2ms | -1.622
| |  P99| 637ms| 750ms | 113ms | 17.749
| ChannelStore.CreateDirectChannel |  Avg| 20ms| 20ms | 0s | 0.000
| |  P99| 97ms| 168ms | 71ms | 72.824
| ChannelStore.CreateInitialSidebarCategories |  Avg| 17ms| 19ms | 2ms | 11.720
| |  P99| 96ms| 182ms | 86ms | 89.716
| ChannelStore.Get |  Avg| 3ms| 6ms | 3ms | 97.139
| |  P99| 44ms| 133ms | 89ms | 204.070
| ChannelStore.GetAllChannelMemberIdsByChannelId |  Avg| 11ms| 15ms | 4ms | 36.147
| |  P99| 25ms| 178ms | 153ms | 615.089
| ChannelStore.GetAllChannelMembersForUser |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 24ms| 24ms | 0s | 0.000
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 18ms| 17ms | -1ms | -5.661
| |  P99| 72ms| 63ms | -9ms | -12.520
| ChannelStore.GetByName |  Avg| 6ms| 7ms | 1ms | 16.964
| |  P99| 81ms| 119ms | 38ms | 46.920
| ChannelStore.GetByNameIncludeDeleted |  Avg| 2ms| 0s | -2ms | -101.723
| |  P99| 5ms| 0s | -5ms | -101.010
| ChannelStore.GetChannelUnread |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.GetChannels |  Avg| 4ms| 5ms | 1ms | 23.484
| |  P99| 66ms| 92ms | 26ms | 39.366
| ChannelStore.GetChannelsByUser |  Avg| 12ms| 22ms | 10ms | 80.256
| |  P99| 161ms| 262ms | 101ms | 62.773
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 31ms| 46ms | 15ms | 48.257
| ChannelStore.GetFileCount |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 46ms| 51ms | 5ms | 10.838
| ChannelStore.GetGuestCount |  Avg| 6ms| 8ms | 2ms | 32.119
| |  P99| 101ms| 187ms | 86ms | 85.038
| ChannelStore.GetMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| ChannelStore.GetMemberCount |  Avg| 146ms| 139ms | -7ms | -4.799
| |  P99| 666ms| 724ms | 58ms | 8.714
| ChannelStore.GetMemberForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 16ms | -2ms | -11.130
| ChannelStore.GetMemberOnly |  Avg| 4ms| 0s | -4ms | -97.169
| |  P99| 64ms| 0s | -64ms | -100.356
| ChannelStore.GetMembersForUser |  Avg| 4ms| 5ms | 1ms | 24.088
| |  P99| 53ms| 91ms | 38ms | 71.261
| ChannelStore.GetMembersForUserWithPagination |  Avg| 45ms| 44ms | -1ms | -2.209
| |  P99| 91ms| 87ms | -4ms | -4.396
| ChannelStore.GetPinnedPostCount |  Avg| 3ms| 4ms | 1ms | 29.619
| |  P99| 48ms| 82ms | 34ms | 71.479
| ChannelStore.GetPublicChannelsForTeam |  Avg| 11ms| 13ms | 2ms | 17.529
| |  P99| 104ms| 267ms | 163ms | 156.873
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 16ms| 25ms | 9ms | 54.862
| |  P99| 224ms| 427ms | 203ms | 90.597
| ChannelStore.GetSidebarCategory |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 9ms| 10ms | 1ms | 11.295
| ChannelStore.GetTeamChannels |  Avg| 65ms| 38ms | -27ms | -41.639
| |  P99| 244ms| 50ms | -194ms | -79.509
| ChannelStore.IncrementMentionCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 6ms| 6ms | 0s | 0.000
| ChannelStore.InvalidateAllChannelMembersForUser |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.InvalidateChannelByName |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ChannelStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 23ms| 22ms | -1ms | -4.304
| ChannelStore.SaveMember |  Avg| 40ms| 47ms | 7ms | 17.484
| |  P99| 352ms| 488ms | 136ms | 38.616
| ChannelStore.SearchGroupChannels |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 36ms| 22ms | -14ms | -38.503
| ChannelStore.UpdateLastViewedAt |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ChannelStore.UpdateSidebarCategories |  Avg| 25ms| 44ms | 19ms | 75.525
| |  P99| 94ms| 238ms | 144ms | 153.614
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ClusterDiscoveryStore.GetAll |  Avg| 2ms| 0s | -2ms | -133.323
| |  P99| 5ms| 0s | -5ms | -101.010
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 19ms| 16ms | -3ms | -15.666
| CommandWebhookStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ComplianceStore.MessageExport |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 26ms | 21ms | 420.083
| DraftStore.Delete |  Avg| 3ms| 1ms | -2ms | -72.759
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| DraftStore.GetDraftsForUser |  Avg| 2ms| 4ms | 2ms | 91.909
| |  P99| 5ms| 10ms | 5ms | 101.010
| DraftStore.Upsert |  Avg| 3ms| 0s | -3ms | -106.266
| |  P99| 5ms| 0s | -5ms | -100.888
| EmojiStore.Search |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| FileInfoStore.AttachToPost |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 16ms| 10ms | -6ms | -37.745
| FileInfoStore.Get |  Avg| 2ms| 3ms | 1ms | 40.913
| |  P99| 19ms| 17ms | -2ms | -10.470
| FileInfoStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 15ms| 18ms | 3ms | 20.401
| FileInfoStore.Save |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.124
| FileInfoStore.Search |  Avg| 0s| 18ms | 18ms | 528634.361
| |  P99| 5ms| 25ms | 20ms | 404.040
| FileInfoStore.SetContent |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 21ms| 10ms | -11ms | -52.789
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 5ms| 6ms | 1ms | 21.991
| |  P99| 73ms| 149ms | 76ms | 104.436
| GroupStore.GetByName |  Avg| 5ms| 7ms | 2ms | 36.543
| |  P99| 90ms| 145ms | 55ms | 60.939
| GroupStore.GetGroups |  Avg| 4ms| 5ms | 1ms | 24.203
| |  P99| 66ms| 94ms | 28ms | 42.259
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.Get |  Avg| 2ms| 3ms | 1ms | 52.283
| |  P99| 5ms| 68ms | 63ms | 1272.727
| JobStore.GetAllByStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 47ms| 60ms | 13ms | 27.372
| JobStore.GetAllByTypePage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 6ms | 1ms | 20.202
| JobStore.GetCountByStatusAndType |  Avg| 4ms| 9ms | 5ms | 125.955
| |  P99| 62ms| 335ms | 273ms | 440.323
| JobStore.GetNewestJobByStatusesAndType |  Avg| 5ms| 7ms | 2ms | 42.867
| |  P99| 89ms| 167ms | 78ms | 87.640
| JobStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| JobStore.UpdateOptimistically |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 5ms | -3ms | -39.841
| JobStore.UpdateStatus |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 9ms | -9ms | -48.913
| JobStore.UpdateStatusOptimistically |  Avg| 3ms| 4ms | 1ms | 32.777
| |  P99| 9ms| 39ms | 30ms | 337.079
| LicenseStore.GetAll |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| LinkMetadataStore.Get |  Avg| 2ms| 3ms | 1ms | 49.378
| |  P99| 5ms| 31ms | 26ms | 520.241
| LinkMetadataStore.Save |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.151
| PluginStore.Delete |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PluginStore.Get |  Avg| 8ms| 6ms | -2ms | -25.354
| |  P99| 90ms| 155ms | 65ms | 71.960
| PluginStore.List |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| PluginStore.SetWithOptions |  Avg| 4ms| 5ms | 1ms | 22.964
| |  P99| 19ms| 18ms | -1ms | -5.276
| PostAcknowledgementStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 28ms| 41ms | 13ms | 46.429
| PostAcknowledgementStore.GetForPosts |  Avg| 4ms| 5ms | 1ms | 26.083
| |  P99| 41ms| 63ms | 22ms | 53.659
| PostPersistentNotificationStore.DeleteExpired |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 9ms | 4ms | 80.808
| PostPersistentNotificationStore.Get |  Avg| 1ms| 2ms | 1ms | 108.497
| |  P99| 5ms| 21ms | 16ms | 323.232
| PostPersistentNotificationStore.GetSingle |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 34ms| 62ms | 28ms | 82.276
| PostPriorityStore.GetForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 27ms| 63ms | 36ms | 135.848
| PostPriorityStore.GetForPosts |  Avg| 4ms| 5ms | 1ms | 26.115
| |  P99| 45ms| 66ms | 21ms | 47.150
| PostStore.AnalyticsPostCount |  Avg| 561ms| 177ms | -384ms | -68.456
| |  P99| 2.47s| 249ms | -2.221s | -89.914
| PostStore.Delete |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| PostStore.Get |  Avg| 5ms| 6ms | 1ms | 18.838
| |  P99| 42ms| 57ms | 15ms | 35.869
| PostStore.GetEtag |  Avg| 5ms| 6ms | 1ms | 19.586
| |  P99| 84ms| 126ms | 42ms | 50.026
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 8ms| 7ms | -1ms | -12.917
| PostStore.GetPostIdBeforeTime |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 6ms| 5ms | -1ms | -17.931
| PostStore.GetPostReminderMetadata |  Avg| 6ms| 2ms | -4ms | -69.763
| |  P99| 46ms| 5ms | -41ms | -89.619
| PostStore.GetPostReminders |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.GetPosts |  Avg| 8ms| 9ms | 1ms | 12.943
| |  P99| 82ms| 140ms | 58ms | 70.656
| PostStore.GetPostsAfter |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 8ms | -10ms | -55.249
| PostStore.GetPostsBefore |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 46ms| 66ms | 20ms | 43.141
| PostStore.GetPostsByThread |  Avg| 2ms| 3ms | 1ms | 40.735
| |  P99| 26ms| 31ms | 5ms | 19.244
| PostStore.GetPostsSince |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 79ms| 88ms | 9ms | 11.464
| PostStore.GetSingle |  Avg| 2ms| 3ms | 1ms | 45.458
| |  P99| 5ms| 28ms | 23ms | 460.233
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 25ms| 26ms | 1ms | 4.001
| PostStore.SearchPostsForUser |  Avg| 79ms| 79ms | 0s | 0.000
| |  P99| 1.575s| 1.755s | 180ms | 11.429
| PostStore.SetPostReminder |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| PostStore.Update |  Avg| 13ms| 12ms | -1ms | -7.850
| |  P99| 36ms| 25ms | -11ms | -30.241
| PreferenceStore.DeleteCategoryAndName |  Avg| 4ms| 2ms | -2ms | -55.646
| |  P99| 24ms| 5ms | -19ms | -80.338
| PreferenceStore.Get |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 34ms| 48ms | 14ms | 40.928
| PreferenceStore.GetAll |  Avg| 8ms| 9ms | 1ms | 13.065
| |  P99| 119ms| 170ms | 51ms | 43.000
| PreferenceStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 25ms| 25ms | 0s | 0.000
| ProductNoticesStore.ClearOldNotices |  Avg| 1ms| 0s | -1ms | -75.911
| |  P99| 5ms| 0s | -5ms | -101.005
| ProductNoticesStore.GetViews |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 24ms| 24ms | 0s | 0.000
| |  P99| 94ms| 87ms | -7ms | -7.476
| ReactionStore.ExistsOnPost |  Avg| 4ms| 5ms | 1ms | 25.199
| |  P99| 36ms| 48ms | 12ms | 33.690
| ReactionStore.GetForPost |  Avg| 3ms| 4ms | 1ms | 31.098
| |  P99| 24ms| 46ms | 22ms | 91.236
| ReactionStore.GetUniqueCountForPost |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 31ms| 42ms | 11ms | 35.314
| ReactionStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 18ms| 19ms | 1ms | 5.488
| RetentionPolicyStore.GetAll |  Avg| 3ms| 2ms | -1ms | -29.338
| |  P99| 10ms| 5ms | -5ms | -50.761
| RetentionPolicyStore.GetCount |  Avg| 2ms| 1ms | -1ms | -40.668
| |  P99| 10ms| 5ms | -5ms | -51.021
| RoleStore.ChannelHigherScopedPermissions |  Avg| 2ms| 3ms | 1ms | 53.486
| |  P99| 5ms| 40ms | 35ms | 706.784
| RoleStore.GetByNames |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SchemeStore.GetAllPage |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| SessionStore.Get |  Avg| 8ms| 9ms | 1ms | 13.284
| |  P99| 97ms| 171ms | 74ms | 76.554
| SessionStore.GetSessionsExpired |  Avg| 2ms| 16ms | 14ms | 705.727
| |  P99| 5ms| 97ms | 92ms | 1858.586
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 2ms| 3ms | 1ms | 41.791
| |  P99| 18ms| 35ms | 17ms | 93.103
| SessionStore.Remove |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 5ms| 23ms | 18ms | 363.636
| SessionStore.Save |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 99ms| 146ms | 47ms | 47.291
| SessionStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 7ms | 0s | 0.000
| StatusStore.Get |  Avg| 5ms| 6ms | 1ms | 21.659
| |  P99| 78ms| 97ms | 19ms | 24.399
| StatusStore.GetByIds |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 41ms| 60ms | 19ms | 45.900
| StatusStore.SaveOrUpdate |  Avg| 28ms| 29ms | 1ms | 3.520
| |  P99| 404ms| 408ms | 4ms | 0.991
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -51.388
| StatusStore.UpdateLastActivityAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 7ms| 8ms | 1ms | 14.782
| SystemStore.GetByName |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 7ms| 6ms | -1ms | -13.469
| SystemStore.PermanentDeleteByName |  Avg| 2ms| 4ms | 2ms | 88.518
| |  P99| 5ms| 5ms | 0s | 0.000
| SystemStore.SaveOrUpdate |  Avg| 2ms| 3ms | 1ms | 51.232
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.AnalyticsTeamCount |  Avg| 2ms| 5ms | 3ms | 166.922
| |  P99| 5ms| 48ms | 43ms | 868.366
| TeamStore.Get |  Avg| 2ms| 3ms | 1ms | 42.476
| |  P99| 18ms| 47ms | 29ms | 160.591
| TeamStore.GetAllPage |  Avg| 5ms| 7ms | 2ms | 39.405
| |  P99| 82ms| 147ms | 65ms | 78.958
| TeamStore.GetByName |  Avg| 2ms| 3ms | 1ms | 47.301
| |  P99| 14ms| 37ms | 23ms | 167.902
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 5ms| 7ms | 2ms | 39.136
| |  P99| 77ms| 139ms | 62ms | 80.028
| TeamStore.GetMember |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| TeamStore.GetTeamsByUserId |  Avg| 5ms| 8ms | 3ms | 57.733
| |  P99| 83ms| 153ms | 70ms | 84.056
| TeamStore.GetTeamsForUser |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 93ms| 116ms | 23ms | 24.759
| TeamStore.SaveMember |  Avg| 98ms| 99ms | 1ms | 1.024
| |  P99| 245ms| 246ms | 1ms | 0.407
| ThreadStore.Get |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.GetMembershipForUser |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 34ms| 61ms | 27ms | 79.972
| ThreadStore.GetTeamsUnreadForUser |  Avg| 6ms| 8ms | 2ms | 35.746
| |  P99| 75ms| 155ms | 80ms | 106.163
| ThreadStore.GetThreadFollowers |  Avg| 3ms| 4ms | 1ms | 32.997
| |  P99| 43ms| 64ms | 21ms | 48.276
| ThreadStore.GetThreadForUser |  Avg| 5ms| 6ms | 1ms | 21.180
| |  P99| 32ms| 90ms | 58ms | 181.116
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 18ms| 36ms | 18ms | 101.638
| ThreadStore.GetThreadsForUser |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 45ms| 71ms | 26ms | 57.454
| ThreadStore.GetTotalThreads |  Avg| 4ms| 6ms | 2ms | 44.939
| |  P99| 68ms| 107ms | 39ms | 57.721
| ThreadStore.GetTotalUnreadMentions |  Avg| 4ms| 6ms | 2ms | 45.308
| |  P99| 72ms| 100ms | 28ms | 38.929
| ThreadStore.GetTotalUnreadThreads |  Avg| 4ms| 6ms | 2ms | 44.744
| |  P99| 66ms| 104ms | 38ms | 57.845
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 5ms| 7ms | 2ms | 44.127
| |  P99| 67ms| 115ms | 48ms | 71.163
| ThreadStore.MaintainMembership |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 10ms | 0s | 0.000
| ThreadStore.MarkAllAsReadByChannels |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ThreadStore.MarkAsRead |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 8ms| 8ms | 0s | 0.000
| ThreadStore.UpdateMembership |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 6ms| 8ms | 2ms | 31.908
| TokenStore.Cleanup |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserAccessTokenStore.GetByToken |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 9ms| 5ms | -4ms | -45.684
| UserStore.AnalyticsActiveCount |  Avg| 211ms| 208ms | -3ms | -1.422
| |  P99| 249ms| 249ms | 0s | 0.000
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 1ms| 1ms | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.AutocompleteUsersInChannel |  Avg| 196ms| 193ms | -3ms | -1.527
| |  P99| 676ms| 618ms | -58ms | -8.585
| UserStore.Count |  Avg| 115ms| 115ms | 0s | 0.000
| |  P99| 248ms| 390ms | 142ms | 57.207
| UserStore.Get |  Avg| 2ms| 3ms | 1ms | 46.281
| |  P99| 13ms| 21ms | 8ms | 59.562
| UserStore.GetAllProfiles |  Avg| 6ms| 7ms | 1ms | 16.770
| |  P99| 69ms| 94ms | 25ms | 36.261
| UserStore.GetAllProfilesInChannel |  Avg| 456ms| 452ms | -4ms | -0.878
| |  P99| 2.184s| 2.147s | -37ms | -1.694
| UserStore.GetByUsername |  Avg| 3ms| 2ms | -1ms | -30.721
| |  P99| 51ms| 9ms | -42ms | -83.126
| UserStore.GetForLogin |  Avg| 6ms| 7ms | 1ms | 15.737
| |  P99| 99ms| 139ms | 40ms | 40.451
| UserStore.GetMany |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 10ms| 5ms | -5ms | -52.083
| UserStore.GetProfileByIds |  Avg| 2ms| 2ms | 0s | 0.000
| |  P99| 11ms| 19ms | 8ms | 72.408
| UserStore.GetProfilesByUsernames |  Avg| 3ms| 4ms | 1ms | 30.781
| |  P99| 35ms| 53ms | 18ms | 50.938
| UserStore.GetProfilesInChannel |  Avg| 5ms| 10ms | 5ms | 105.622
| |  P99| 47ms| 195ms | 148ms | 315.244
| UserStore.GetUnreadCount |  Avg| 5ms| 7ms | 2ms | 39.248
| |  P99| 46ms| 146ms | 100ms | 218.331
| UserStore.IsEmpty |  Avg| 3ms| 4ms | 1ms | 29.070
| |  P99| 60ms| 77ms | 17ms | 28.455
| UserStore.Save |  Avg| 67ms| 67ms | 0s | 0.000
| |  P99| 100ms| 100ms | 0s | 0.000
| UserStore.Search |  Avg| 89ms| 87ms | -2ms | -2.246
| |  P99| 337ms| 292ms | -45ms | -13.343
| UserStore.Update |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 10ms| 9ms | -1ms | -10.458
| UserStore.UpdateFailedPasswordAttempts |  Avg| 3ms| 4ms | 1ms | 29.170
| |  P99| 18ms| 20ms | 2ms | 11.099
| UserStore.UpdateLastLogin |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 14ms| 15ms | 1ms | 7.229
| UserStore.UpdateUpdateAt |  Avg| 3ms| 3ms | 0s | 0.000
| |  P99| 17ms| 18ms | 1ms | 5.850
| UserTermsOfServiceStore.GetByUser |  Avg| 6ms| 7ms | 1ms | 17.777
| |  P99| 95ms| 144ms | 49ms | 51.377
| WebhookStore.GetOutgoingByTeam |  Avg| 4ms| 4ms | 0s | 0.000
| |  P99| 39ms| 58ms | 19ms | 49.326
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 234ms| 213ms | -21ms | -8.969
| | P99| 500ms| 485ms | -15ms | -3.000
| addTeamMember | Avg| 1.25s| 1.283s | 33ms | 2.640
| | P99| 4.608s| 4.665s | 57ms | 1.237
| autocompleteChannelsForTeamForSearch | Avg| 123ms| 121ms | -2ms | -1.621
| | P99| 637ms| 750ms | 113ms | 17.749
| autocompleteEmojis | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| autocompleteUsers | Avg| 158ms| 147ms | -11ms | -6.973
| | P99| 517ms| 490ms | -27ms | -5.223
| createChannel | Avg| 65ms| 38ms | -27ms | -41.556
| | P99| 244ms| 50ms | -194ms | -79.509
| createDirectChannel | Avg| 235ms| 237ms | 2ms | 0.850
| | P99| 495ms| 494ms | -1ms | -0.202
| createGroupChannel | Avg| 342ms| 336ms | -6ms | -1.754
| | P99| 902ms| 895ms | -7ms | -0.776
| createPost | Avg| 372ms| 403ms | 31ms | 8.344
| | P99| 2.229s| 2.338s | 109ms | 4.889
| createUser | Avg| 96ms| 98ms | 2ms | 2.093
| | P99| 250ms| 347ms | 97ms | 38.864
| deleteDraft | Avg| 3ms| 2ms | -1ms | -29.335
| | P99| 10ms| 10ms | 0s | 0.000
| deletePost | Avg| 17ms| 16ms | -1ms | -5.755
| | P99| 25ms| 25ms | 0s | 0.000
| followThreadByUser | Avg| 9ms| 10ms | 1ms | 11.675
| | P99| 10ms| 24ms | 14ms | 140.661
| getAllTeams | Avg| 6ms| 7ms | 1ms | 17.569
| | P99| 86ms| 156ms | 70ms | 81.048
| getAnalytics | Avg| 187ms| 249ms | 62ms | 33.139
| | P99| 490ms| 494ms | 4ms | 0.816
| getCategoriesForTeamForUser | Avg| 17ms| 25ms | 8ms | 47.996
| | P99| 225ms| 428ms | 203ms | 90.328
| getChannel | Avg| 5ms| 6ms | 1ms | 20.414
| | P99| 26ms| 107ms | 81ms | 308.552
| getChannelMember | Avg| 3ms| 4ms | 1ms | 29.351
| | P99| 47ms| 75ms | 28ms | 59.852
| getChannelMembersForTeamForUser | Avg| 5ms| 6ms | 1ms | 21.987
| | P99| 61ms| 96ms | 35ms | 57.358
| getChannelMembersForUser | Avg| 51ms| 47ms | -4ms | -7.908
| | P99| 97ms| 97ms | 0s | 0.000
| getChannelStats | Avg| 17ms| 17ms | 0s | 0.000
| | P99| 396ms| 409ms | 13ms | 3.280
| getChannelUnread | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getChannelsForTeamForUser | Avg| 5ms| 6ms | 1ms | 19.519
| | P99| 84ms| 121ms | 37ms | 44.229
| getChannelsForUser | Avg| 15ms| 28ms | 13ms | 86.040
| | P99| 225ms| 430ms | 205ms | 91.309
| getClientConfig | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 43ms| 44ms | 1ms | 2.310
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getConfig | Avg| 25ms| 25ms | 0s | 0.000
| | P99| 75ms| 75ms | 0s | 0.000
| getDrafts | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getFilePreview | Avg| 41ms| 44ms | 3ms | 7.260
| | P99| 200ms| 216ms | 16ms | 7.993
| getFileThumbnail | Avg| 33ms| 34ms | 1ms | 3.025
| | P99| 124ms| 135ms | 11ms | 8.875
| getFilteredUsersStats | Avg| 30ms| 49ms | 19ms | 63.856
| | P99| 50ms| 244ms | 194ms | 389.950
| getGroups | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getGroupsAssociatedToChannelsByTeam | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getJobsByType | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 6ms | 1ms | 20.202
| getLicenseSelfServeStatus | Avg| 181ms| 155ms | -26ms | -14.389
| | P99| 248ms| 249ms | 1ms | 0.402
| getPostThread | Avg| 14ms| 15ms | 1ms | 7.018
| | P99| 72ms| 98ms | 26ms | 36.223
| getPostsForChannel | Avg| 25ms| 30ms | 5ms | 20.220
| | P99| 234ms| 338ms | 104ms | 44.455
| getPostsForChannelAroundLastUnread | Avg| 41ms| 52ms | 11ms | 26.925
| | P99| 671ms| 884ms | 213ms | 31.743
| getPreferences | Avg| 8ms| 10ms | 2ms | 25.319
| | P99| 124ms| 172ms | 48ms | 38.741
| getPrevTrialLicense | Avg| 1ms| 2ms | 1ms | 70.356
| | P99| 5ms| 5ms | 0s | 0.000
| getProductNotices | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getProfileImage | Avg| 96ms| 65ms | -31ms | -32.262
| | P99| 463ms| 451ms | -12ms | -2.591
| getPublicChannelsForTeam | Avg| 13ms| 14ms | 1ms | 7.962
| | P99| 104ms| 267ms | 163ms | 156.873
| getRolesByNames | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getSelfHostedProducts | Avg| 21ms| 32ms | 11ms | 52.733
| | P99| 50ms| 98ms | 48ms | 96.968
| getTeamMember | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMembersForUser | Avg| 7ms| 7ms | 0s | 0.000
| | P99| 108ms| 140ms | 32ms | 29.505
| getTeamsForUser | Avg| 5ms| 8ms | 3ms | 56.999
| | P99| 83ms| 154ms | 71ms | 85.228
| getTeamsUnreadForUser | Avg| 8ms| 12ms | 4ms | 47.365
| | P99| 125ms| 222ms | 97ms | 77.424
| getThreadsForUser | Avg| 4ms| 5ms | 1ms | 24.131
| | P99| 51ms| 89ms | 38ms | 74.812
| getUser | Avg| 8ms| 9ms | 1ms | 12.777
| | P99| 105ms| 175ms | 70ms | 66.796
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsers | Avg| 10ms| 11ms | 1ms | 10.350
| | P99| 90ms| 134ms | 44ms | 48.658
| getUsersByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUsersByNames | Avg| 3ms| 4ms | 1ms | 29.414
| | P99| 36ms| 54ms | 18ms | 50.682
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| handleCheckCWSConnection | Avg| 37ms| 0s | -37ms | -100.170
| | P99| 50ms| 0s | -50ms | -100.503
| login | Avg| 67ms| 69ms | 2ms | 2.979
| | P99| 392ms| 418ms | 26ms | 6.625
| logout | Avg| 37ms| 38ms | 1ms | 2.683
| | P99| 95ms| 94ms | -1ms | -1.058
| patchPost | Avg| 33ms| 29ms | -4ms | -12.213
| | P99| 96ms| 118ms | 22ms | 23.036
| removeUserCustomStatus | Avg| 169ms| 142ms | -27ms | -15.969
| | P99| 474ms| 248ms | -226ms | -47.730
| root | Avg| 0s| 1ms | 1ms | 804.394
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 24ms| 27ms | 3ms | 12.561
| | P99| 217ms| 345ms | 128ms | 58.870
| searchAllChannels | Avg| 1.504s| 1.496s | -8ms | -0.532
| | P99| 4.928s| 4.988s | 60ms | 1.218
| searchFiles | Avg| 2ms| 20ms | 18ms | 831.671
| | P99| 5ms| 25ms | 20ms | 402.564
| searchGroupChannels | Avg| 3ms| 3ms | 0s | 0.000
| | P99| 36ms| 22ms | -14ms | -38.503
| searchPostsInTeam | Avg| 87ms| 93ms | 6ms | 6.869
| | P99| 1.575s| 1.89s | 315ms | 20.001
| searchUsers | Avg| 91ms| 88ms | -3ms | -3.306
| | P99| 349ms| 294ms | -55ms | -15.738
| setPostReminder | Avg| 29ms| 14ms | -15ms | -51.420
| | P99| 236ms| 25ms | -211ms | -89.219
| unfollowThreadByUser | Avg| 8ms| 9ms | 1ms | 11.804
| | P99| 19ms| 21ms | 2ms | 10.442
| updateCategoriesForTeamForUser | Avg| 35ms| 48ms | 13ms | 37.001
| | P99| 94ms| 239ms | 145ms | 154.681
| updatePreferences | Avg| 6ms| 6ms | 0s | 0.000
| | P99| 10ms| 14ms | 4ms | 40.013
| updateReadStateThreadByUser | Avg| 26ms| 29ms | 3ms | 11.732
| | P99| 95ms| 172ms | 77ms | 81.238
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 419ms| 424ms | 5ms | 1.194
| | P99| 995ms| 989ms | -6ms | -0.603
| upsertDraft | Avg| 4ms| 3ms | -1ms | -22.753
| | P99| 10ms| 5ms | -5ms | -50.760
| viewChannel | Avg| 12ms| 12ms | 0s | 0.000
| | P99| 86ms| 124ms | 38ms | 44.434
